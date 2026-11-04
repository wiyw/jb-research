# Glossary

Terms used throughout this repository.

## Firmware and platform

**IPSW**
: Apple firmware restore archive (`.ipsw`). Contains the OS images, kernel,
  device tree, and restore metadata for a device/build.

**Build**
: The firmware build identifier, for example `24A446` or `24B119`. More
  precise than the marketing version (`27.0.1`, `27.2`).

**vresearch101**
: Apple's Virtualization.framework research platform (board `vresearch101ap`)
  used by Private Cloud Compute research VMs. The boot chain in this project
  targets it.

**vphone600**
: The runtime platform used by vphone VMs for kernel/DeviceTree/SEP, paired
  with an iPhone userland.

**SEP**
: Secure Enclave Processor. Handles keybag and security services.

**SPTM / TXM**
: Apple's security monitors in the boot chain (Secure Page Table Monitor and
  Trusted Execution Monitor).

**ExclaveOS**
: The ExclaveKit/ExclaveOS components in the firmware, separate from the main
  SystemOS/AppOS images.

**SystemOS / AppOS / filesystem**
: The three Mach-O scopes compared by `ipsw diff`. `filesystem` is the root
  filesystem image, `SystemOS` is the system volume, and `AppOS` holds app
  binaries.

## Mach-O and dyld

**Mach-O**
: Apple's executable/object format. The dylibs here are 64-bit `arm64e`.

**dylib**
: Dynamic library (shared library), analogous to a `.so` or `.dll`.

**DSC / dyld shared cache**
: A prelinked collection of system dylibs loaded by dyld. Extracting an image
  from it produces a standalone Mach-O.

**Subcache**
: A shard of the shared cache. The main `dyld_shared_cache_arm64e` file is
  small; the `.NN` subcaches hold most of the code and data. Keep them
  together when using `ipsw dyld`.

**arm64e**
: AArch64 with Apple's pointer-authentication extensions (PAC). Pointers carry
  signing metadata and are authenticated on use.

**PAC**
: Pointer Authentication Code. A cryptographic signature embedded in unused
  pointer bits, verified before the pointer is used.

**Slide**
: Address randomization applied to the shared cache at load time. The
  extracted dylibs have cache addresses baked in, which is why tools that
  expect a normal Mach-O base address can fail.

**UUID**
: `LC_UUID` build identifier for a Mach-O image. Changes whenever the image is
  rebuilt, so it is a quick way to tell two builds apart.

**LC_SOURCE_VERSION**
: The source revision embedded in a Mach-O. Useful when the marketing
  `current version` does not change between releases.

**ObjC / Swift metadata**
: Class, method, protocol, and type metadata embedded in the binary. Tools
  like `ipsw class-dump` reconstruct headers from it.

**Kext / kernelcache**
: Kernel extension and the prelinked kernel image that contains them.

## Tooling

**ipsw**
: blacktop's CLI for downloading, extracting, diffing, and inspecting Apple
  firmware and Mach-O files.

**Ghidra**
: NSA's reverse-engineering suite. Used here to disassemble and decompile the
  extracted dylibs.

**Ghidra project (`.gpr` / `.rep`)**
: The project pointer file and its database directory. The database is local,
  stateful, and intentionally untracked.

**CppExporter**
: Ghidra's **C/C++** export format. Produces the whole-program `.c` files in
  `decompiled/`.

**class-dump**
: Extract Objective-C declarations from a Mach-O or shared-cache image. In
  this repo, use `ipsw class-dump <DSC> <image path>`.

**vphone-launchpad**
: The notarized graphical front end for vphone-cli, used to create and boot
  the virtual iPhone.

**vresearch101 / vphone600 pairing**
: vphone combines a vresearch101 boot chain with a vphone600 runtime and an
  iPhone userland to produce a bootable virtual device.
