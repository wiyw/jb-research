# Release diff highlights: 27.0.1 (24A446) to 27.2 (24B119)

A curated summary of the generated diff in
`analysis/27_0_1_24A446_vs_27_2_24B119/`. The full lists, including every
updated file, are in that report; this page highlights the shape of the
release and the areas most relevant to this repository.

## Kernel

| iOS | Kernel version | Build | Date |
| :-- | :------------- | :---- | :--- |
| 27.0.1 (24A446) | 27.0.0 | 13432.2.10~2 | 2026-08-13 21:39:16 PDT |
| 27.2 (24B119) | 27.2.0 | 13432.42.3~28 | 2026-10-13 21:27:45 PDT |

- 1 new kext: `com.apple.iokit.AppleSecurityResearch`
- 236 kexts updated

## Mach-O changes

| Area | New | Removed | Updated |
| :--- | --: | ------: | ------: |
| filesystem | 78 | 18 | 2006 |
| SystemOS | 0 | 2 | 15 |
| AppOS | 0 | 0 | 11 |
| ExclaveOS | 0 | 3 | 12 |

### Filesystem additions worth noting

- `/Applications/Siri AI.app/Siri AI`
- `/Applications/HomeProximityDynamicIslandUIService.app/HomeProximityDynamicIslandUIService`
- `/usr/libexec/appledepthd`
- `/System/Library/PreferenceBundles/HomeDeveloperSettings.bundle/HomeDeveloperSettings`
- A large set of migration/replacement extensions under
  `/System/Library/ExtensionKit/Extensions/` (app migration, app replacement,
  data migration)

### Filesystem removals worth noting

- `/Applications/Campo.app/Campo`
- `/System/Library/PrivateFrameworks/AggregateDictionary.framework/Support/aggregated`
- `/usr/libexec/chassisplatformhostd`
- `speechmodeltrainingd` is removed from
  `CoreSpeech.framework` and appears under
  `CoreEmbeddedSpeechRecognition.framework` instead

### ExclaveOS

- Removed: `TokenGeneration`, `TokenGenerationInference`, and
  `TokenGenerationInferenceExclaveComponent`
- Updated: `dyld`, dispatch variants, and several audio/exclave components

## Dyld shared cache

| Metric | 27.0.1 | 27.2 |
| :----- | -----: | ---: |
| WebKit version | 625.1.29.10.33 | 625.2.8.10.7 |
| Images | 4695 | 4770 |
| Subcaches | 77 | 81 |
| Shared region | 5 GB | 6 GB |
| New dylibs | - | 82 |
| Removed dylibs | - | 7 |
| Updated dylibs | - | 2820 |

### New dylib families

The largest cluster is health-related:

- `HealthReport`, `HealthReportCoreUI`, `HealthReportUI`,
  `HealthReportPlatform`, `HealthReportHealthDaemon`
- `HealthAgents`, `HealthContent`, `HealthContentUI`,
  `HealthContentGeneration`, `HealthContentDaemon`
- `HealthEvaluations`, `HealthEvaluationsUI`, `HealthFacts`,
  `HealthHistory`, `HealthIntelligence`, `HealthPlans`, `HealthNarrator`
- `LabKit`, `LabKitUI`, `LabKitDaemon`, `SurveyKit`, `SurveyKitUI`,
  `SurveyKitDaemon`

Other notable additions:

- `ASRKit`, `SiriProcessing`, `PommesRanking`, `SpotlightUIRanking`
- `PebblePlayCore`, `PebblePlayKit`, `PebblePlayDaemon`, `PebblePlayFeatures`
- `MomentsAlgorithms`, `MotionHealthAlgorithms`
- `ProcessorTrace`, `MemoryUsage`, `Human`
- `/usr/lib/libEndpointSecurity.dylib`, `/usr/lib/libfabric.dylib`
- `libobjcMsgSend34.dylib` and `libobjcMsgSend35.dylib` move from SystemOS
  standalone binaries into the shared cache

### Removed dylibs

- `CameraKit`
- `ChassisTriagePlaneClient`
- `MTInferenceToolLib`
- `NonverbalCues`
- `ODDAnalytics`
- `RelevanceServicesCompanion`
- `SiriBaseTypes`

`ExclavesStats` is removed as a standalone filesystem Mach-O and appears in
the shared cache instead.

## Framework source versions

| Framework | 27.0.1 source | 27.2 source |
| :-------- | :------------ | :---------- |
| CoreGraphics | 2050.0 | 2050.1.6 |
| ImageIO | 2851.0 | 2851.1.8 |
| IMCore / IMDPersistence | 1491.100.1.2.28 | 1491.200.101.2.5 |
| libxpc.dylib | 3298.2.1 | 3298.42.1 |

`CoreGraphics`, `ImageIO`, `IMCore`, `IMDPersistence`, and `libxpc.dylib` are
tracked in this repository. CoreGraphics and ImageIO are the focus of the
committed Ghidra exports. Their section-level changes are in the
`analysis/.../DYLIBS/` reports if those image names are present in the
generated diff.

## Caveats

- Counts come from `ipsw diff` and depend on the `--fw` option and the build
  pairing.
- "New" and "removed" mean the path was absent or present in the other
  build's diff scope, not necessarily a new feature.
- Renames and moves can appear as a removal plus an addition.
- Re-run the diff yourself if you need a different build pair or additional
  options; see [analysis.md](analysis.md).
