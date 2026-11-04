# Virtual device (vphone)

The virtual device is a `vresearch101` / `vphone600` iOS guest running on an
Apple Silicon Mac through Apple's Virtualization.framework. This repository
uses the notarized **vphone-launchpad** build.

Upstream project: [Lakr233/vphone-cli](https://github.com/Lakr233/vphone-cli).

## Host requirements

- A physical Apple Silicon Mac running macOS 15 or newer
- Enough free disk space (each VM uses a large virtual disk by default)
- Network access for firmware download and restore tickets
- The research-guest host settings enabled in Recovery:

  ```sh
  csrutil enable --without debug
  csrutil allow-research-guests enable
  ```

  Reboot after changing these. SIP stays enabled; only debugging restrictions
  are relaxed. This is the configuration the notarized launchpad expects.

## Install the notarized launchpad

1. Open the [releases page](https://github.com/Lakr233/vphone-cli/releases).
2. Download a `vphone-launchpad-<version>-notarized.zip` asset. Not every
   release is notarized; if the latest one has no notarized archive, pick a
   notarized version from the downloads list.
3. Unzip and open the launchpad.
4. In **Host Setup**, grant Developer Tools access and install the helper.
5. In **Core Bundle**, click **Download and Install** to fetch and verify
   `VPhone.bundle`.

The launchpad must be the notarized build; CI-built zips are blocked by macOS
on first open.

## Create and boot a VM

1. Open **Machines** and click **New Machine**.
2. Choose a firmware pairing. For `iPhone17,3` guests the upstream
   compatibility table lists the verified iOS / cloudOS pairings.
3. Click **Create**. The launchpad downloads the firmware, patches it,
   restores the system, and boots the VM.

Firmware and VM bundles are stored outside this repository, normally under
`~/.vphone/`. They are not committed.

## Logs

`vphone/log.txt` in this repository (when present) is a captured serial/boot
log from a `test-phone` VM. It shows iBoot loading, the kernel slide, panic
output, host security configuration, and the entitlements used for research
guests. It is a snapshot, not a live log.

For live output, use the launchpad's console/serial view or the VM's serial
device, and consult the upstream documentation for the current command-line
interface.
