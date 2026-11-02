## SiriInstrumentation

> `/System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation`

```diff

-3600.85.1.0.0
-  __TEXT.__text: 0xd92138
-  __TEXT.__objc_methlist: 0x10ad94
-  __TEXT.__const: 0x17bc4
-  __TEXT.__swift5_typeref: 0x1edc
-  __TEXT.__cstring: 0x95c1d
-  __TEXT.__constg_swiftt: 0x7f74
-  __TEXT.__swift5_reflstr: 0x21d
-  __TEXT.__swift5_fieldmd: 0x45c
-  __TEXT.__swift5_builtin: 0x4a60
+3605.33.1.0.0
+  __TEXT.__text: 0xdf613c
+  __TEXT.__objc_methlist: 0x111c94
+  __TEXT.__const: 0x18fc4
+  __TEXT.__swift5_typeref: 0x2012
+  __TEXT.__cstring: 0x99424
+  __TEXT.__constg_swiftt: 0x84b8
+  __TEXT.__swift5_reflstr: 0x22d
+  __TEXT.__swift5_fieldmd: 0x488
+  __TEXT.__swift5_builtin: 0x4d6c
   __TEXT.__swift5_assocty: 0x150
-  __TEXT.__swift5_proto: 0x139c
-  __TEXT.__swift5_types: 0xf34
-  __TEXT.__oslogstring: 0xc1
-  __TEXT.__swift5_protos: 0x24
-  __TEXT.__unwind_info: 0x32f68
-  __TEXT.__eh_frame: 0x4db8
+  __TEXT.__swift5_proto: 0x15b8
+  __TEXT.__swift5_types: 0xfd4
+  __TEXT.__oslogstring: 0x111
+  __TEXT.__swift5_protos: 0x28
+  __TEXT.__swift5_capture: 0x14
+  __TEXT.__unwind_info: 0x34bc0
+  __TEXT.__eh_frame: 0x4cf0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3d8d0
-  __DATA_CONST.__objc_classlist: 0x6878
+  __DATA_CONST.__const: 0x400f8
+  __DATA_CONST.__objc_classlist: 0x6b28
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x42ed0
+  __DATA_CONST.__objc_selrefs: 0x44650
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x6828
-  __DATA_CONST.__got: 0x69b0
-  __AUTH_CONST.__const: 0x25be9
-  __AUTH_CONST.__cfstring: 0x80460
-  __AUTH_CONST.__objc_const: 0x17da90
-  __AUTH_CONST.__objc_intobj: 0xcf0
-  __AUTH_CONST.__auth_got: 0x928
-  __AUTH_CONST.__auth_ptr: 0x2180
-  __AUTH.__objc_data: 0x29db0
-  __AUTH.__data: 0x160
-  __DATA.__objc_ivar: 0x12be8
-  __DATA.__data: 0x3508
-  __DATA.__bss: 0x1f980
-  __DATA.__common: 0x20
-  __DATA_DIRTY.__objc_data: 0x17970
-  __DATA_DIRTY.__data: 0x238
+  __DATA_CONST.__objc_superrefs: 0x6ad8
+  __DATA_CONST.__got: 0x6c80
+  __AUTH_CONST.__const: 0x271f0
+  __AUTH_CONST.__cfstring: 0x83aa0
+  __AUTH_CONST.__objc_const: 0x1877b0
+  __AUTH_CONST.__objc_intobj: 0xd38
+  __AUTH_CONST.__auth_got: 0x9c8
+  __AUTH_CONST.__auth_ptr: 0x22c8
+  __AUTH.__objc_data: 0x140
+  __DATA.__objc_ivar: 0x1337c
+  __DATA.__data: 0x3570
+  __DATA.__bss: 0x20d00
+  __DATA.__common: 0x38
+  __DATA_DIRTY.__objc_data: 0x430c0
+  __DATA_DIRTY.__data: 0x518
   __DATA_DIRTY.__common: 0x38
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 94031
-  Symbols:   132275
+  Functions: 96883
+  Symbols:   135706
   CStrings:  0
 
Symbols:
+ +[RISchemaRIClientEvent(Component) joinability]
+ +[RISchemaRIClientEvent(InnerEventContainer) getInnerTypeStringByTag:]
+ +[RISessionSchemaRISessionClientEvent(Component) joinability]
+ +[RISessionSchemaRISessionClientEvent(InnerEventContainer) getInnerTypeStringByTag:]
+ +[TCSchemaTCClientEvent(Component) joinability]
+ +[TCSchemaTCClientEvent(InnerEventContainer) getInnerTypeStringByTag:]
+ -[ASRSchemaASRRecognitionMetrics deleteNumActivatedNCBVQEntitiesFromJIT]
+ -[ASRSchemaASRRecognitionMetrics hasNumActivatedNCBVQEntitiesFromJIT]
+ -[ASRSchemaASRRecognitionMetrics numActivatedNCBVQEntitiesFromJIT]
+ -[ASRSchemaASRRecognitionMetrics setHasNumActivatedNCBVQEntitiesFromJIT:]
+ -[ASRSchemaASRRecognitionMetrics setNumActivatedNCBVQEntitiesFromJIT:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated .cxx_destruct]
+ -[CHSchemaCHAgenticGradingInferenceGenerated deleteEvaluatorMetadata]
+ -[CHSchemaCHAgenticGradingInferenceGenerated deleteGraderResult]
+ -[CHSchemaCHAgenticGradingInferenceGenerated deleteGraderType]
+ -[CHSchemaCHAgenticGradingInferenceGenerated dictionaryRepresentation]
+ -[CHSchemaCHAgenticGradingInferenceGenerated evaluatorMetadata]
+ -[CHSchemaCHAgenticGradingInferenceGenerated graderResult]
+ -[CHSchemaCHAgenticGradingInferenceGenerated graderType]
+ -[CHSchemaCHAgenticGradingInferenceGenerated hasEvaluatorMetadata]
+ -[CHSchemaCHAgenticGradingInferenceGenerated hasGraderResult]
+ -[CHSchemaCHAgenticGradingInferenceGenerated hasGraderType]
+ -[CHSchemaCHAgenticGradingInferenceGenerated hash]
+ -[CHSchemaCHAgenticGradingInferenceGenerated initWithDictionary:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated initWithJSON:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated isEqual:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated jsonData]
+ -[CHSchemaCHAgenticGradingInferenceGenerated readFrom:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated setEvaluatorMetadata:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated setGraderResult:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated setGraderType:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated setHasEvaluatorMetadata:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated setHasGraderResult:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated setHasGraderType:]
+ -[CHSchemaCHAgenticGradingInferenceGenerated writeTo:]
+ -[CHSchemaCHClientEvent agenticGradingInferenceGenerated]
+ -[CHSchemaCHClientEvent deleteAgenticGradingInferenceGenerated]
+ -[CHSchemaCHClientEvent hasAgenticGradingInferenceGenerated]
+ -[CHSchemaCHClientEvent setAgenticGradingInferenceGenerated:]
+ -[CHSchemaCHClientEvent setHasAgenticGradingInferenceGenerated:]
+ -[CHSchemaCHGraderResult .cxx_destruct]
+ -[CHSchemaCHGraderResult deleteSpeechGradingInferenceMetadata]
+ -[CHSchemaCHGraderResult dictionaryRepresentation]
+ -[CHSchemaCHGraderResult hasSpeechGradingInferenceMetadata]
+ -[CHSchemaCHGraderResult hash]
+ -[CHSchemaCHGraderResult initWithDictionary:]
+ -[CHSchemaCHGraderResult initWithJSON:]
+ -[CHSchemaCHGraderResult isEqual:]
+ -[CHSchemaCHGraderResult jsonData]
+ -[CHSchemaCHGraderResult readFrom:]
+ -[CHSchemaCHGraderResult setHasSpeechGradingInferenceMetadata:]
+ -[CHSchemaCHGraderResult setSpeechGradingInferenceMetadata:]
+ -[CHSchemaCHGraderResult speechGradingInferenceMetadata]
+ -[CHSchemaCHGraderResult whichGraderresult]
+ -[CHSchemaCHGraderResult writeTo:]
+ -[CHSchemaCHSpeechCriterionResult categoryScore]
+ -[CHSchemaCHSpeechCriterionResult criterionId]
+ -[CHSchemaCHSpeechCriterionResult deleteCategoryScore]
+ -[CHSchemaCHSpeechCriterionResult deleteCriterionId]
+ -[CHSchemaCHSpeechCriterionResult deleteVerdict]
+ -[CHSchemaCHSpeechCriterionResult dictionaryRepresentation]
+ -[CHSchemaCHSpeechCriterionResult hasCategoryScore]
+ -[CHSchemaCHSpeechCriterionResult hasCriterionId]
+ -[CHSchemaCHSpeechCriterionResult hasVerdict]
+ -[CHSchemaCHSpeechCriterionResult hash]
+ -[CHSchemaCHSpeechCriterionResult initWithDictionary:]
+ -[CHSchemaCHSpeechCriterionResult initWithJSON:]
+ -[CHSchemaCHSpeechCriterionResult isEqual:]
+ -[CHSchemaCHSpeechCriterionResult jsonData]
+ -[CHSchemaCHSpeechCriterionResult readFrom:]
+ -[CHSchemaCHSpeechCriterionResult setCategoryScore:]
+ -[CHSchemaCHSpeechCriterionResult setCriterionId:]
+ -[CHSchemaCHSpeechCriterionResult setHasCategoryScore:]
+ -[CHSchemaCHSpeechCriterionResult setHasCriterionId:]
+ -[CHSchemaCHSpeechCriterionResult setHasVerdict:]
+ -[CHSchemaCHSpeechCriterionResult setVerdict:]
+ -[CHSchemaCHSpeechCriterionResult verdict]
+ -[CHSchemaCHSpeechCriterionResult writeTo:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata .cxx_destruct]
+ -[CHSchemaCHSpeechGradingInferenceMetadata addCriterionResults:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata applicableWeightMilliunits]
+ -[CHSchemaCHSpeechGradingInferenceMetadata asrRisk]
+ -[CHSchemaCHSpeechGradingInferenceMetadata clearCriterionResults]
+ -[CHSchemaCHSpeechGradingInferenceMetadata confMarginBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata criterionResultsAtIndex:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata criterionResultsCount]
+ -[CHSchemaCHSpeechGradingInferenceMetadata criterionResults]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteApplicableWeightMilliunits]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteAsrRisk]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteConfMarginBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteCriterionResults]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteErrorClass]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteGated]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteJudged]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteLatencyBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteMode]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteNBestPhrases]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteNotJudgedReason]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteNumInteractionsConsidered]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteNumInteractionsGraded]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteParseOutcome]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deletePhrasesWithChoice]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteProvider]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteQueryRewritten]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteRegrade]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteRetries]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteRubricVersion]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteRunId]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteRunSampleProbability]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteSampleAgreement]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteSamples]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteScore]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteSelectedHypothesisIndex]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteSelectionOutcome]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteThin]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteTopHypothesisConfBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata deleteTotalWeightMilliunits]
+ -[CHSchemaCHSpeechGradingInferenceMetadata dictionaryRepresentation]
+ -[CHSchemaCHSpeechGradingInferenceMetadata errorClass]
+ -[CHSchemaCHSpeechGradingInferenceMetadata gated]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasApplicableWeightMilliunits]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasAsrRisk]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasConfMarginBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasErrorClass]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasGated]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasJudged]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasLatencyBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasMode]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasNBestPhrases]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasNotJudgedReason]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasNumInteractionsConsidered]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasNumInteractionsGraded]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasParseOutcome]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasPhrasesWithChoice]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasProvider]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasQueryRewritten]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasRegrade]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasRetries]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasRubricVersion]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasRunId]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasRunSampleProbability]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasSampleAgreement]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasSamples]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasScore]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasSelectedHypothesisIndex]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasSelectionOutcome]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasThin]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasTopHypothesisConfBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hasTotalWeightMilliunits]
+ -[CHSchemaCHSpeechGradingInferenceMetadata hash]
+ -[CHSchemaCHSpeechGradingInferenceMetadata initWithDictionary:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata initWithJSON:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata isEqual:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata jsonData]
+ -[CHSchemaCHSpeechGradingInferenceMetadata judged]
+ -[CHSchemaCHSpeechGradingInferenceMetadata latencyBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata mode]
+ -[CHSchemaCHSpeechGradingInferenceMetadata nBestPhrases]
+ -[CHSchemaCHSpeechGradingInferenceMetadata notJudgedReason]
+ -[CHSchemaCHSpeechGradingInferenceMetadata numInteractionsConsidered]
+ -[CHSchemaCHSpeechGradingInferenceMetadata numInteractionsGraded]
+ -[CHSchemaCHSpeechGradingInferenceMetadata parseOutcome]
+ -[CHSchemaCHSpeechGradingInferenceMetadata phrasesWithChoice]
+ -[CHSchemaCHSpeechGradingInferenceMetadata provider]
+ -[CHSchemaCHSpeechGradingInferenceMetadata queryRewritten]
+ -[CHSchemaCHSpeechGradingInferenceMetadata readFrom:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata regrade]
+ -[CHSchemaCHSpeechGradingInferenceMetadata retries]
+ -[CHSchemaCHSpeechGradingInferenceMetadata rubricVersion]
+ -[CHSchemaCHSpeechGradingInferenceMetadata runId]
+ -[CHSchemaCHSpeechGradingInferenceMetadata runSampleProbability]
+ -[CHSchemaCHSpeechGradingInferenceMetadata sampleAgreement]
+ -[CHSchemaCHSpeechGradingInferenceMetadata samples]
+ -[CHSchemaCHSpeechGradingInferenceMetadata score]
+ -[CHSchemaCHSpeechGradingInferenceMetadata selectedHypothesisIndex]
+ -[CHSchemaCHSpeechGradingInferenceMetadata selectionOutcome]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setApplicableWeightMilliunits:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setAsrRisk:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setConfMarginBucket:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setCriterionResults:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setErrorClass:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setGated:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasApplicableWeightMilliunits:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasAsrRisk:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasConfMarginBucket:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasErrorClass:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasGated:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasJudged:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasLatencyBucket:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasMode:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasNBestPhrases:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasNotJudgedReason:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasNumInteractionsConsidered:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasNumInteractionsGraded:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasParseOutcome:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasPhrasesWithChoice:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasProvider:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasQueryRewritten:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasRegrade:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasRetries:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasRubricVersion:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasRunId:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasRunSampleProbability:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasSampleAgreement:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasSamples:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasScore:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasSelectedHypothesisIndex:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasSelectionOutcome:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasThin:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasTopHypothesisConfBucket:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setHasTotalWeightMilliunits:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setJudged:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setLatencyBucket:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setMode:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setNBestPhrases:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setNotJudgedReason:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setNumInteractionsConsidered:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setNumInteractionsGraded:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setParseOutcome:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setPhrasesWithChoice:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setProvider:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setQueryRewritten:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setRegrade:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setRetries:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setRubricVersion:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setRunId:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setRunSampleProbability:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setSampleAgreement:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setSamples:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setScore:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setSelectedHypothesisIndex:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setSelectionOutcome:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setThin:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setTopHypothesisConfBucket:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata setTotalWeightMilliunits:]
+ -[CHSchemaCHSpeechGradingInferenceMetadata thin]
+ -[CHSchemaCHSpeechGradingInferenceMetadata topHypothesisConfBucket]
+ -[CHSchemaCHSpeechGradingInferenceMetadata totalWeightMilliunits]
+ -[CHSchemaCHSpeechGradingInferenceMetadata writeTo:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted .cxx_destruct]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted deleteOutcome]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted deleteReason]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted dictionaryRepresentation]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted hasOutcome]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted hasReason]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted hash]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted initWithDictionary:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted initWithJSON:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted isEqual:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted jsonData]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted outcome]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted readFrom:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted reason]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted setHasOutcome:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted setHasReason:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted setOutcome:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted setReason:]
+ -[CPRSchemaCPRActiveRuntimeSwitchAttempted writeTo:]
+ -[CPRSchemaCPRArchitectureUsed .cxx_destruct]
+ -[CPRSchemaCPRArchitectureUsed activeRuntimeAtRequestStart]
+ -[CPRSchemaCPRArchitectureUsed deleteActiveRuntimeAtRequestStart]
+ -[CPRSchemaCPRArchitectureUsed deleteRootIfSessionId]
+ -[CPRSchemaCPRArchitectureUsed dictionaryRepresentation]
+ -[CPRSchemaCPRArchitectureUsed hasActiveRuntimeAtRequestStart]
+ -[CPRSchemaCPRArchitectureUsed hasRootIfSessionId]
+ -[CPRSchemaCPRArchitectureUsed hash]
+ -[CPRSchemaCPRArchitectureUsed initWithDictionary:]
+ -[CPRSchemaCPRArchitectureUsed initWithJSON:]
+ -[CPRSchemaCPRArchitectureUsed isEqual:]
+ -[CPRSchemaCPRArchitectureUsed jsonData]
+ -[CPRSchemaCPRArchitectureUsed readFrom:]
+ -[CPRSchemaCPRArchitectureUsed rootIfSessionId]
+ -[CPRSchemaCPRArchitectureUsed setActiveRuntimeAtRequestStart:]
+ -[CPRSchemaCPRArchitectureUsed setHasActiveRuntimeAtRequestStart:]
+ -[CPRSchemaCPRArchitectureUsed setHasRootIfSessionId:]
+ -[CPRSchemaCPRArchitectureUsed setRootIfSessionId:]
+ -[CPRSchemaCPRArchitectureUsed writeTo:]
+ -[CPRSchemaCPRClientEvent activeRuntimeSwitchAttempted]
+ -[CPRSchemaCPRClientEvent architectureUsed]
+ -[CPRSchemaCPRClientEvent deleteActiveRuntimeSwitchAttempted]
+ -[CPRSchemaCPRClientEvent deleteArchitectureUsed]
+ -[CPRSchemaCPRClientEvent hasActiveRuntimeSwitchAttempted]
+ -[CPRSchemaCPRClientEvent hasArchitectureUsed]
+ -[CPRSchemaCPRClientEvent setActiveRuntimeSwitchAttempted:]
+ -[CPRSchemaCPRClientEvent setArchitectureUsed:]
+ -[CPRSchemaCPRClientEvent setHasActiveRuntimeSwitchAttempted:]
+ -[CPRSchemaCPRClientEvent setHasArchitectureUsed:]
+ -[DIMSchemaDIMDeviceFixedContext dataSharingPromptVersion]
+ -[DIMSchemaDIMDeviceFixedContext deleteDataSharingPromptVersion]
+ -[DIMSchemaDIMDeviceFixedContext hasDataSharingPromptVersion]
+ -[DIMSchemaDIMDeviceFixedContext setDataSharingPromptVersion:]
+ -[DIMSchemaDIMDeviceFixedContext setHasDataSharingPromptVersion:]
+ -[ExecutorSiriSchemaExecutorActionPoisoningClassifierCallEnded deleteInputCharCount]
+ -[ExecutorSiriSchemaExecutorActionPoisoningClassifierCallEnded hasInputCharCount]
+ -[ExecutorSiriSchemaExecutorActionPoisoningClassifierCallEnded inputCharCount]
+ -[ExecutorSiriSchemaExecutorActionPoisoningClassifierCallEnded setHasInputCharCount:]
+ -[ExecutorSiriSchemaExecutorActionPoisoningClassifierCallEnded setInputCharCount:]
+ -[ExecutorSiriSchemaExecutorAppIntentMetrics deleteIsRemoteExecution]
+ -[ExecutorSiriSchemaExecutorAppIntentMetrics hasIsRemoteExecution]
+ -[ExecutorSiriSchemaExecutorAppIntentMetrics isRemoteExecution]
+ -[ExecutorSiriSchemaExecutorAppIntentMetrics setHasIsRemoteExecution:]
+ -[ExecutorSiriSchemaExecutorAppIntentMetrics setIsRemoteExecution:]
+ -[ExecutorSiriSchemaExecutorClientEvent deleteExecutorInjectableContentClassifierCallContext]
+ -[ExecutorSiriSchemaExecutorClientEvent executorInjectableContentClassifierCallContext]
+ -[ExecutorSiriSchemaExecutorClientEvent hasExecutorInjectableContentClassifierCallContext]
+ -[ExecutorSiriSchemaExecutorClientEvent setExecutorInjectableContentClassifierCallContext:]
+ -[ExecutorSiriSchemaExecutorClientEvent setHasExecutorInjectableContentClassifierCallContext:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled deleteExists]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled dictionaryRepresentation]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled exists]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled hasExists]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled hash]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled initWithDictionary:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled initWithJSON:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled isEqual:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled jsonData]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled readFrom:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled setExists:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled setHasExists:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled writeTo:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext .cxx_destruct]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext appIntentSessionId]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext canceled]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext deleteAppIntentSessionId]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext deleteCanceled]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext deleteEnded]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext deleteFailed]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext deleteStartedOrChanged]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext dictionaryRepresentation]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext ended]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext failed]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext hasAppIntentSessionId]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext hasCanceled]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext hasEnded]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext hasFailed]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext hasStartedOrChanged]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext hash]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext initWithDictionary:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext initWithJSON:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext isEqual:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext jsonData]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext readFrom:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setAppIntentSessionId:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setCanceled:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setEnded:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setFailed:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setHasAppIntentSessionId:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setHasCanceled:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setHasEnded:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setHasFailed:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setHasStartedOrChanged:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext setStartedOrChanged:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext startedOrChanged]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext whichContextevent]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext writeTo:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded classifierOutcome]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded deleteClassifierOutcome]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded deleteInputCharCount]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded dictionaryRepresentation]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded hasClassifierOutcome]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded hasInputCharCount]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded hash]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded initWithDictionary:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded initWithJSON:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded inputCharCount]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded isEqual:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded jsonData]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded readFrom:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded setClassifierOutcome:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded setHasClassifierOutcome:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded setHasInputCharCount:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded setInputCharCount:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded writeTo:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed .cxx_destruct]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed addErrors:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed clearErrors]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed deleteErrors]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed dictionaryRepresentation]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed errorsAtIndex:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed errorsCount]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed errors]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed hash]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed initWithDictionary:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed initWithJSON:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed isEqual:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed jsonData]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed readFrom:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed setErrors:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed writeTo:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted deleteExists]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted dictionaryRepresentation]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted exists]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted hasExists]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted hash]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted initWithDictionary:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted initWithJSON:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted isEqual:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted jsonData]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted readFrom:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted setExists:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted setHasExists:]
+ -[ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted writeTo:]
+ -[GMSSchemaGMSExtendedInferenceMetrics deleteRoutingDecision]
+ -[GMSSchemaGMSExtendedInferenceMetrics hasRoutingDecision]
+ -[GMSSchemaGMSExtendedInferenceMetrics routingDecision]
+ -[GMSSchemaGMSExtendedInferenceMetrics setHasRoutingDecision:]
+ -[GMSSchemaGMSExtendedInferenceMetrics setRoutingDecision:]
+ -[IDENTITYSchemaIDENTITYClientEvent deleteSpeakerIdResultReceived]
+ -[IDENTITYSchemaIDENTITYClientEvent hasSpeakerIdResultReceived]
+ -[IDENTITYSchemaIDENTITYClientEvent setHasSpeakerIdResultReceived:]
+ -[IDENTITYSchemaIDENTITYClientEvent setSpeakerIdResultReceived:]
+ -[IDENTITYSchemaIDENTITYClientEvent speakerIdResultReceived]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived deleteHasVoiceTrigger]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived deleteMilestone]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived deletePerceptionClassification]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived dictionaryRepresentation]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived hasHasVoiceTrigger]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived hasMilestone]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived hasPerceptionClassification]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived hasVoiceTrigger]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived hash]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived initWithDictionary:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived initWithJSON:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived isEqual:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived jsonData]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived milestone]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived perceptionClassification]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived readFrom:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived setHasHasVoiceTrigger:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived setHasMilestone:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived setHasPerceptionClassification:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived setHasVoiceTrigger:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived setMilestone:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived setPerceptionClassification:]
+ -[IDENTITYSchemaIDENTITYSpeakerIdResultReceived writeTo:]
+ -[LRSchemaLRRedactionExclusionSignal .cxx_destruct]
+ -[LRSchemaLRRedactionExclusionSignal deleteExcludedScope]
+ -[LRSchemaLRRedactionExclusionSignal deleteReason]
+ -[LRSchemaLRRedactionExclusionSignal dictionaryRepresentation]
+ -[LRSchemaLRRedactionExclusionSignal excludedScope]
+ -[LRSchemaLRRedactionExclusionSignal hasExcludedScope]
+ -[LRSchemaLRRedactionExclusionSignal hasReason]
+ -[LRSchemaLRRedactionExclusionSignal hash]
+ -[LRSchemaLRRedactionExclusionSignal initWithDictionary:]
+ -[LRSchemaLRRedactionExclusionSignal initWithJSON:]
+ -[LRSchemaLRRedactionExclusionSignal isEqual:]
+ -[LRSchemaLRRedactionExclusionSignal jsonData]
+ -[LRSchemaLRRedactionExclusionSignal readFrom:]
+ -[LRSchemaLRRedactionExclusionSignal reason]
+ -[LRSchemaLRRedactionExclusionSignal setExcludedScope:]
+ -[LRSchemaLRRedactionExclusionSignal setHasExcludedScope:]
+ -[LRSchemaLRRedactionExclusionSignal setHasReason:]
+ -[LRSchemaLRRedactionExclusionSignal setReason:]
+ -[LRSchemaLRRedactionExclusionSignal writeTo:]
+ -[LRSchemaLRRedactionSignal addExcludedSignals:]
+ -[LRSchemaLRRedactionSignal clearExcludedSignals]
+ -[LRSchemaLRRedactionSignal deleteExcludedSignals]
+ -[LRSchemaLRRedactionSignal excludedSignalsAtIndex:]
+ -[LRSchemaLRRedactionSignal excludedSignalsCount]
+ -[LRSchemaLRRedactionSignal excludedSignals]
+ -[LRSchemaLRRedactionSignal setExcludedSignals:]
+ -[NLXSchemaNLXClientEventMetadata deleteRequesterFlow]
+ -[NLXSchemaNLXClientEventMetadata hasRequesterFlow]
+ -[NLXSchemaNLXClientEventMetadata requesterFlow]
+ -[NLXSchemaNLXClientEventMetadata setHasRequesterFlow:]
+ -[NLXSchemaNLXClientEventMetadata setRequesterFlow:]
+ -[ODDSiriSchemaODDAnnounceProperties deleteIsAnnounceEligible]
+ -[ODDSiriSchemaODDAnnounceProperties hasIsAnnounceEligible]
+ -[ODDSiriSchemaODDAnnounceProperties isAnnounceEligible]
+ -[ODDSiriSchemaODDAnnounceProperties setHasIsAnnounceEligible:]
+ -[ODDSiriSchemaODDAnnounceProperties setIsAnnounceEligible:]
+ -[ODDSiriSchemaODDAssetBringUpStatus countOfFactoryAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus countOfOTAAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus countOfPSUSAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus currentBuildVersion]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteCountOfFactoryAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteCountOfOTAAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteCountOfPSUSAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteCurrentBuildVersion]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteTotalSizeOfFactoryAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteTotalSizeOfOTAAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus deleteTotalSizeOfPSUSAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasCountOfFactoryAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasCountOfOTAAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasCountOfPSUSAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasCurrentBuildVersion]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasTotalSizeOfFactoryAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasTotalSizeOfOTAAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus hasTotalSizeOfPSUSAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus setCountOfFactoryAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setCountOfOTAAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setCountOfPSUSAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setCurrentBuildVersion:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasCountOfFactoryAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasCountOfOTAAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasCountOfPSUSAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasCurrentBuildVersion:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasTotalSizeOfFactoryAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasTotalSizeOfOTAAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setHasTotalSizeOfPSUSAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setTotalSizeOfFactoryAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setTotalSizeOfOTAAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus setTotalSizeOfPSUSAssetsInAssetSet:]
+ -[ODDSiriSchemaODDAssetBringUpStatus totalSizeOfFactoryAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus totalSizeOfOTAAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssetBringUpStatus totalSizeOfPSUSAssetsInAssetSet]
+ -[ODDSiriSchemaODDAssistantLLMSiriCounts deleteTokenCounts]
+ -[ODDSiriSchemaODDAssistantLLMSiriCounts hasTokenCounts]
+ -[ODDSiriSchemaODDAssistantLLMSiriCounts setHasTokenCounts:]
+ -[ODDSiriSchemaODDAssistantLLMSiriCounts setTokenCounts:]
+ -[ODDSiriSchemaODDAssistantLLMSiriCounts tokenCounts]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions addAppPartyTypes:]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions appPartyTypesAtIndex:]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions appPartyTypesCount]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions appPartyTypes]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions clearAppPartyTypes]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions deleteAppPartyTypes]
+ -[ODDSiriSchemaODDAssistantLLMSiriDimensions setAppPartyTypes:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteEventStreamResultType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deletePromptType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteProvider]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions eventStreamResultType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasEventStreamResultType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasPromptType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasProvider]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions promptType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions provider]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setEventStreamResultType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasEventStreamResultType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasPromptType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasProvider:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setPromptType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setProvider:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteInputTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteInputTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteOutputTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteOutputTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteTokenBucketScheme]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteTotalTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts deleteTotalTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts dictionaryRepresentation]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasInputTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasInputTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasOutputTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasOutputTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasTokenBucketScheme]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasTotalTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hasTotalTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts hash]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts initWithDictionary:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts initWithJSON:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts inputTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts inputTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts isEqual:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts jsonData]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts outputTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts outputTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts readFrom:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasInputTokenBucketOdm:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasInputTokenBucketPcc:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasOutputTokenBucketOdm:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasOutputTokenBucketPcc:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasTokenBucketScheme:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasTotalTokenBucketOdm:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setHasTotalTokenBucketPcc:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setInputTokenBucketOdm:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setInputTokenBucketPcc:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setOutputTokenBucketOdm:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setOutputTokenBucketPcc:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setTokenBucketScheme:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setTotalTokenBucketOdm:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts setTotalTokenBucketPcc:]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts tokenBucketScheme]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts totalTokenBucketOdm]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts totalTokenBucketPcc]
+ -[ODDSiriSchemaODDLLMSiriTokenCounts writeTo:]
+ -[ODDSiriSchemaODDwatchOSAssistantProperties announce]
+ -[ODDSiriSchemaODDwatchOSAssistantProperties deleteAnnounce]
+ -[ODDSiriSchemaODDwatchOSAssistantProperties hasAnnounce]
+ -[ODDSiriSchemaODDwatchOSAssistantProperties setAnnounce:]
+ -[ODDSiriSchemaODDwatchOSAssistantProperties setHasAnnounce:]
+ -[ORCHSchemaORCHClientEvent deleteSpeakerIdentificationResultReceived]
+ -[ORCHSchemaORCHClientEvent deleteSpeakerIdentificationSettled]
+ -[ORCHSchemaORCHClientEvent hasSpeakerIdentificationResultReceived]
+ -[ORCHSchemaORCHClientEvent hasSpeakerIdentificationSettled]
+ -[ORCHSchemaORCHClientEvent setHasSpeakerIdentificationResultReceived:]
+ -[ORCHSchemaORCHClientEvent setHasSpeakerIdentificationSettled:]
+ -[ORCHSchemaORCHClientEvent setSpeakerIdentificationResultReceived:]
+ -[ORCHSchemaORCHClientEvent setSpeakerIdentificationSettled:]
+ -[ORCHSchemaORCHClientEvent speakerIdentificationResultReceived]
+ -[ORCHSchemaORCHClientEvent speakerIdentificationSettled]
+ -[ORCHSchemaORCHIFProxyRequestFailed addErrors:]
+ -[ORCHSchemaORCHIFProxyRequestFailed clearErrors]
+ -[ORCHSchemaORCHIFProxyRequestFailed deleteErrors]
+ -[ORCHSchemaORCHIFProxyRequestFailed errorsAtIndex:]
+ -[ORCHSchemaORCHIFProxyRequestFailed errorsCount]
+ -[ORCHSchemaORCHIFProxyRequestFailed errors]
+ -[ORCHSchemaORCHIFProxyRequestFailed setErrors:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived .cxx_destruct]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived addIdentityAggressors:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived clearIdentityAggressors]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteDropReason]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteElapsedSinceActivationInMs]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteElapsedToForwardCompletedInMs]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteFailureReason]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteIdentityAggressors]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteIsGuest]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteIsRecentlySeen]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deletePhase]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteResultOrdinal]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteUserIdentityClassification]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteWasForwarded]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteWasIdentityTransition]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived dictionaryRepresentation]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived dropReason]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived elapsedSinceActivationInMs]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived elapsedToForwardCompletedInMs]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived failureReason]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasDropReason]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasElapsedSinceActivationInMs]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasElapsedToForwardCompletedInMs]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasFailureReason]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasIsGuest]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasIsRecentlySeen]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasPhase]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasResultOrdinal]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasUserIdentityClassification]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasWasForwarded]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasWasIdentityTransition]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hash]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived identityAggressorsAtIndex:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived identityAggressorsCount]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived identityAggressors]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived initWithDictionary:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived initWithJSON:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived isEqual:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived isGuest]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived isRecentlySeen]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived jsonData]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived phase]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived readFrom:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived resultOrdinal]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setDropReason:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setElapsedSinceActivationInMs:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setElapsedToForwardCompletedInMs:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setFailureReason:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasDropReason:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasElapsedSinceActivationInMs:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasElapsedToForwardCompletedInMs:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasFailureReason:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasIsGuest:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasIsRecentlySeen:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasPhase:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasResultOrdinal:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasUserIdentityClassification:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasWasForwarded:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasWasIdentityTransition:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setIdentityAggressors:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setIsGuest:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setIsRecentlySeen:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setPhase:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setResultOrdinal:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setUserIdentityClassification:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setWasForwarded:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setWasIdentityTransition:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived userIdentityClassification]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived wasForwarded]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived wasIdentityTransition]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived writeTo:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled deleteNumEnrolledMembers]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled deleteNumIdentityTransitions]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled deleteNumResultsReceived]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled deleteStateAtSettlement]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled dictionaryRepresentation]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled hasNumEnrolledMembers]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled hasNumIdentityTransitions]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled hasNumResultsReceived]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled hasStateAtSettlement]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled hash]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled initWithDictionary:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled initWithJSON:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled isEqual:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled jsonData]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled numEnrolledMembers]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled numIdentityTransitions]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled numResultsReceived]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled readFrom:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setHasNumEnrolledMembers:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setHasNumIdentityTransitions:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setHasNumResultsReceived:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setHasStateAtSettlement:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setNumEnrolledMembers:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setNumIdentityTransitions:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setNumResultsReceived:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled setStateAtSettlement:]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled stateAtSettlement]
+ -[ORCHSchemaORCHSpeakerIdentificationSettled writeTo:]
+ -[PLANNERSchemaPLANNERClientEvent deleteUserIdentityChecked]
+ -[PLANNERSchemaPLANNERClientEvent deleteUserIdentityConfirmationRequested]
+ -[PLANNERSchemaPLANNERClientEvent deleteUserIdentityConfirmationResolved]
+ -[PLANNERSchemaPLANNERClientEvent hasUserIdentityChecked]
+ -[PLANNERSchemaPLANNERClientEvent hasUserIdentityConfirmationRequested]
+ -[PLANNERSchemaPLANNERClientEvent hasUserIdentityConfirmationResolved]
+ -[PLANNERSchemaPLANNERClientEvent setHasUserIdentityChecked:]
+ -[PLANNERSchemaPLANNERClientEvent setHasUserIdentityConfirmationRequested:]
+ -[PLANNERSchemaPLANNERClientEvent setHasUserIdentityConfirmationResolved:]
+ -[PLANNERSchemaPLANNERClientEvent setUserIdentityChecked:]
+ -[PLANNERSchemaPLANNERClientEvent setUserIdentityConfirmationRequested:]
+ -[PLANNERSchemaPLANNERClientEvent setUserIdentityConfirmationResolved:]
+ -[PLANNERSchemaPLANNERClientEvent userIdentityChecked]
+ -[PLANNERSchemaPLANNERClientEvent userIdentityConfirmationRequested]
+ -[PLANNERSchemaPLANNERClientEvent userIdentityConfirmationResolved]
+ -[PLANNERSchemaPLANNERIPIClassifierEnded deleteInputCharCount]
+ -[PLANNERSchemaPLANNERIPIClassifierEnded hasInputCharCount]
+ -[PLANNERSchemaPLANNERIPIClassifierEnded inputCharCount]
+ -[PLANNERSchemaPLANNERIPIClassifierEnded setHasInputCharCount:]
+ -[PLANNERSchemaPLANNERIPIClassifierEnded setInputCharCount:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked deleteGate]
+ -[PLANNERSchemaPLANNERUserIdentityChecked deleteIsRecentlySeen]
+ -[PLANNERSchemaPLANNERUserIdentityChecked deleteOutcome]
+ -[PLANNERSchemaPLANNERUserIdentityChecked deleteUserClassification]
+ -[PLANNERSchemaPLANNERUserIdentityChecked dictionaryRepresentation]
+ -[PLANNERSchemaPLANNERUserIdentityChecked gate]
+ -[PLANNERSchemaPLANNERUserIdentityChecked hasGate]
+ -[PLANNERSchemaPLANNERUserIdentityChecked hasIsRecentlySeen]
+ -[PLANNERSchemaPLANNERUserIdentityChecked hasOutcome]
+ -[PLANNERSchemaPLANNERUserIdentityChecked hasUserClassification]
+ -[PLANNERSchemaPLANNERUserIdentityChecked hash]
+ -[PLANNERSchemaPLANNERUserIdentityChecked initWithDictionary:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked initWithJSON:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked isEqual:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked isRecentlySeen]
+ -[PLANNERSchemaPLANNERUserIdentityChecked jsonData]
+ -[PLANNERSchemaPLANNERUserIdentityChecked outcome]
+ -[PLANNERSchemaPLANNERUserIdentityChecked readFrom:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setGate:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setHasGate:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setHasIsRecentlySeen:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setHasOutcome:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setHasUserClassification:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setIsRecentlySeen:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setOutcome:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setUserClassification:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked userClassification]
+ -[PLANNERSchemaPLANNERUserIdentityChecked writeTo:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested deletePromptOrdinal]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested deleteUserClassification]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested dictionaryRepresentation]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested hasPromptOrdinal]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested hasUserClassification]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested hash]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested initWithDictionary:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested initWithJSON:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested isEqual:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested jsonData]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested promptOrdinal]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested readFrom:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested setHasPromptOrdinal:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested setHasUserClassification:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested setPromptOrdinal:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested setUserClassification:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested userClassification]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationRequested writeTo:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved .cxx_destruct]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved deleteError]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved deleteOutcome]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved deletePromptOrdinal]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved dictionaryRepresentation]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved error]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved hasError]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved hasOutcome]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved hasPromptOrdinal]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved hash]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved initWithDictionary:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved initWithJSON:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved isEqual:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved jsonData]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved outcome]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved promptOrdinal]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved readFrom:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved setError:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved setHasError:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved setHasOutcome:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved setHasPromptOrdinal:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved setOutcome:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved setPromptOrdinal:]
+ -[PLANNERSchemaPLANNERUserIdentityConfirmationResolved writeTo:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSEntityRef deleteProvenance]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSEntityRef hasProvenance]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSEntityRef provenance]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSEntityRef setHasProvenance:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSEntityRef setProvenance:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded deleteErrorResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded deleteGeneralResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded deleteSuccessResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded errorResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded generalResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded hasErrorResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded hasGeneralResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded hasSuccessResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded setErrorResults:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded setGeneralResults:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded setHasErrorResults:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded setHasGeneralResults:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded setHasSuccessResults:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded setSuccessResults:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded successResults]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded whichPlannertoolsresult]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult .cxx_destruct]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult deleteErrorCode]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult deleteErrorKind]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult dictionaryRepresentation]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult errorCode]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult errorKind]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult hasErrorCode]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult hasErrorKind]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult hash]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult initWithDictionary:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult initWithJSON:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult isEqual:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult jsonData]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult readFrom:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult setErrorCode:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult setErrorKind:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult setHasErrorCode:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult setHasErrorKind:]
+ -[PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult writeTo:]
+ -[RISchemaRIClientEvent .cxx_destruct]
+ -[RISchemaRIClientEvent deleteEventMetadata]
+ -[RISchemaRIClientEvent deleteRemoteContext]
+ -[RISchemaRIClientEvent deleteSourceContext]
+ -[RISchemaRIClientEvent dictionaryRepresentation]
+ -[RISchemaRIClientEvent eventMetadata]
+ -[RISchemaRIClientEvent hasEventMetadata]
+ -[RISchemaRIClientEvent hasRemoteContext]
+ -[RISchemaRIClientEvent hasSourceContext]
+ -[RISchemaRIClientEvent hash]
+ -[RISchemaRIClientEvent initWithDictionary:]
+ -[RISchemaRIClientEvent initWithJSON:]
+ -[RISchemaRIClientEvent isEqual:]
+ -[RISchemaRIClientEvent jsonData]
+ -[RISchemaRIClientEvent qualifiedMessageName]
+ -[RISchemaRIClientEvent readFrom:]
+ -[RISchemaRIClientEvent remoteContext]
+ -[RISchemaRIClientEvent setEventMetadata:]
+ -[RISchemaRIClientEvent setHasEventMetadata:]
+ -[RISchemaRIClientEvent setHasRemoteContext:]
+ -[RISchemaRIClientEvent setHasSourceContext:]
+ -[RISchemaRIClientEvent setRemoteContext:]
+ -[RISchemaRIClientEvent setSourceContext:]
+ -[RISchemaRIClientEvent sourceContext]
+ -[RISchemaRIClientEvent whichEvent_Type]
+ -[RISchemaRIClientEvent writeTo:]
+ -[RISchemaRIClientEvent(Component) componentName]
+ -[RISchemaRIClientEvent(Component) getComponentId]
+ -[RISchemaRIClientEvent(InnerEventContainer) innerEvent]
+ -[RISchemaRIClientEvent(InnerEventContainer) whichInnerEventType]
+ -[RISchemaRIClientEvent(InstrumentationAdditions) getAnyEventType]
+ -[RISchemaRIClientEventMetadata .cxx_destruct]
+ -[RISchemaRIClientEventMetadata deleteRiId]
+ -[RISchemaRIClientEventMetadata dictionaryRepresentation]
+ -[RISchemaRIClientEventMetadata hasRiId]
+ -[RISchemaRIClientEventMetadata hash]
+ -[RISchemaRIClientEventMetadata initWithDictionary:]
+ -[RISchemaRIClientEventMetadata initWithJSON:]
+ -[RISchemaRIClientEventMetadata isEqual:]
+ -[RISchemaRIClientEventMetadata jsonData]
+ -[RISchemaRIClientEventMetadata readFrom:]
+ -[RISchemaRIClientEventMetadata riId]
+ -[RISchemaRIClientEventMetadata setHasRiId:]
+ -[RISchemaRIClientEventMetadata setRiId:]
+ -[RISchemaRIClientEventMetadata writeTo:]
+ -[RISchemaRIError .cxx_destruct]
+ -[RISchemaRIError deleteErrorCode]
+ -[RISchemaRIError deleteErrorDomain]
+ -[RISchemaRIError dictionaryRepresentation]
+ -[RISchemaRIError errorCode]
+ -[RISchemaRIError errorDomain]
+ -[RISchemaRIError hasErrorCode]
+ -[RISchemaRIError hasErrorDomain]
+ -[RISchemaRIError hash]
+ -[RISchemaRIError initWithDictionary:]
+ -[RISchemaRIError initWithJSON:]
+ -[RISchemaRIError isEqual:]
+ -[RISchemaRIError jsonData]
+ -[RISchemaRIError readFrom:]
+ -[RISchemaRIError setErrorCode:]
+ -[RISchemaRIError setErrorDomain:]
+ -[RISchemaRIError setHasErrorCode:]
+ -[RISchemaRIError setHasErrorDomain:]
+ -[RISchemaRIError writeTo:]
+ -[RISchemaRIRemoteContext .cxx_destruct]
+ -[RISchemaRIRemoteContext deleteEnded]
+ -[RISchemaRIRemoteContext deleteFailed]
+ -[RISchemaRIRemoteContext deleteStartedOrChanged]
+ -[RISchemaRIRemoteContext dictionaryRepresentation]
+ -[RISchemaRIRemoteContext ended]
+ -[RISchemaRIRemoteContext failed]
+ -[RISchemaRIRemoteContext hasEnded]
+ -[RISchemaRIRemoteContext hasFailed]
+ -[RISchemaRIRemoteContext hasStartedOrChanged]
+ -[RISchemaRIRemoteContext hash]
+ -[RISchemaRIRemoteContext initWithDictionary:]
+ -[RISchemaRIRemoteContext initWithJSON:]
+ -[RISchemaRIRemoteContext isEqual:]
+ -[RISchemaRIRemoteContext jsonData]
+ -[RISchemaRIRemoteContext readFrom:]
+ -[RISchemaRIRemoteContext setEnded:]
+ -[RISchemaRIRemoteContext setFailed:]
+ -[RISchemaRIRemoteContext setHasEnded:]
+ -[RISchemaRIRemoteContext setHasFailed:]
+ -[RISchemaRIRemoteContext setHasStartedOrChanged:]
+ -[RISchemaRIRemoteContext setStartedOrChanged:]
+ -[RISchemaRIRemoteContext startedOrChanged]
+ -[RISchemaRIRemoteContext whichContextevent]
+ -[RISchemaRIRemoteContext writeTo:]
+ -[RISchemaRIRemoteEnded deleteExists]
+ -[RISchemaRIRemoteEnded dictionaryRepresentation]
+ -[RISchemaRIRemoteEnded exists]
+ -[RISchemaRIRemoteEnded hasExists]
+ -[RISchemaRIRemoteEnded hash]
+ -[RISchemaRIRemoteEnded initWithDictionary:]
+ -[RISchemaRIRemoteEnded initWithJSON:]
+ -[RISchemaRIRemoteEnded isEqual:]
+ -[RISchemaRIRemoteEnded jsonData]
+ -[RISchemaRIRemoteEnded readFrom:]
+ -[RISchemaRIRemoteEnded setExists:]
+ -[RISchemaRIRemoteEnded setHasExists:]
+ -[RISchemaRIRemoteEnded writeTo:]
+ -[RISchemaRIRemoteFailed .cxx_destruct]
+ -[RISchemaRIRemoteFailed deleteError]
+ -[RISchemaRIRemoteFailed deleteExists]
+ -[RISchemaRIRemoteFailed deleteUnderUnderlyingError]
+ -[RISchemaRIRemoteFailed deleteUnderlyingError]
+ -[RISchemaRIRemoteFailed dictionaryRepresentation]
+ -[RISchemaRIRemoteFailed error]
+ -[RISchemaRIRemoteFailed exists]
+ -[RISchemaRIRemoteFailed hasError]
+ -[RISchemaRIRemoteFailed hasExists]
+ -[RISchemaRIRemoteFailed hasUnderUnderlyingError]
+ -[RISchemaRIRemoteFailed hasUnderlyingError]
+ -[RISchemaRIRemoteFailed hash]
+ -[RISchemaRIRemoteFailed initWithDictionary:]
+ -[RISchemaRIRemoteFailed initWithJSON:]
+ -[RISchemaRIRemoteFailed isEqual:]
+ -[RISchemaRIRemoteFailed jsonData]
+ -[RISchemaRIRemoteFailed readFrom:]
+ -[RISchemaRIRemoteFailed setError:]
+ -[RISchemaRIRemoteFailed setExists:]
+ -[RISchemaRIRemoteFailed setHasError:]
+ -[RISchemaRIRemoteFailed setHasExists:]
+ -[RISchemaRIRemoteFailed setHasUnderUnderlyingError:]
+ -[RISchemaRIRemoteFailed setHasUnderlyingError:]
+ -[RISchemaRIRemoteFailed setUnderUnderlyingError:]
+ -[RISchemaRIRemoteFailed setUnderlyingError:]
+ -[RISchemaRIRemoteFailed underUnderlyingError]
+ -[RISchemaRIRemoteFailed underlyingError]
+ -[RISchemaRIRemoteFailed writeTo:]
+ -[RISchemaRIRemoteStarted .cxx_destruct]
+ -[RISchemaRIRemoteStarted deleteIsColdLaunch]
+ -[RISchemaRIRemoteStarted deleteRiSessionId]
+ -[RISchemaRIRemoteStarted dictionaryRepresentation]
+ -[RISchemaRIRemoteStarted hasIsColdLaunch]
+ -[RISchemaRIRemoteStarted hasRiSessionId]
+ -[RISchemaRIRemoteStarted hash]
+ -[RISchemaRIRemoteStarted initWithDictionary:]
+ -[RISchemaRIRemoteStarted initWithJSON:]
+ -[RISchemaRIRemoteStarted isColdLaunch]
+ -[RISchemaRIRemoteStarted isEqual:]
+ -[RISchemaRIRemoteStarted jsonData]
+ -[RISchemaRIRemoteStarted readFrom:]
+ -[RISchemaRIRemoteStarted riSessionId]
+ -[RISchemaRIRemoteStarted setHasIsColdLaunch:]
+ -[RISchemaRIRemoteStarted setHasRiSessionId:]
+ -[RISchemaRIRemoteStarted setIsColdLaunch:]
+ -[RISchemaRIRemoteStarted setRiSessionId:]
+ -[RISchemaRIRemoteStarted writeTo:]
+ -[RISchemaRISourceContext .cxx_destruct]
+ -[RISchemaRISourceContext deleteEnded]
+ -[RISchemaRISourceContext deleteFailed]
+ -[RISchemaRISourceContext deleteStartedOrChanged]
+ -[RISchemaRISourceContext dictionaryRepresentation]
+ -[RISchemaRISourceContext ended]
+ -[RISchemaRISourceContext failed]
+ -[RISchemaRISourceContext hasEnded]
+ -[RISchemaRISourceContext hasFailed]
+ -[RISchemaRISourceContext hasStartedOrChanged]
+ -[RISchemaRISourceContext hash]
+ -[RISchemaRISourceContext initWithDictionary:]
+ -[RISchemaRISourceContext initWithJSON:]
+ -[RISchemaRISourceContext isEqual:]
+ -[RISchemaRISourceContext jsonData]
+ -[RISchemaRISourceContext readFrom:]
+ -[RISchemaRISourceContext setEnded:]
+ -[RISchemaRISourceContext setFailed:]
+ -[RISchemaRISourceContext setHasEnded:]
+ -[RISchemaRISourceContext setHasFailed:]
+ -[RISchemaRISourceContext setHasStartedOrChanged:]
+ -[RISchemaRISourceContext setStartedOrChanged:]
+ -[RISchemaRISourceContext startedOrChanged]
+ -[RISchemaRISourceContext whichContextevent]
+ -[RISchemaRISourceContext writeTo:]
+ -[RISchemaRISourceEnded deleteExists]
+ -[RISchemaRISourceEnded deleteRemoteTimeInMs]
+ -[RISchemaRISourceEnded deleteRoundTripCount]
+ -[RISchemaRISourceEnded deleteSizeInBytes]
+ -[RISchemaRISourceEnded dictionaryRepresentation]
+ -[RISchemaRISourceEnded exists]
+ -[RISchemaRISourceEnded hasExists]
+ -[RISchemaRISourceEnded hasRemoteTimeInMs]
+ -[RISchemaRISourceEnded hasRoundTripCount]
+ -[RISchemaRISourceEnded hasSizeInBytes]
+ -[RISchemaRISourceEnded hash]
+ -[RISchemaRISourceEnded initWithDictionary:]
+ -[RISchemaRISourceEnded initWithJSON:]
+ -[RISchemaRISourceEnded isEqual:]
+ -[RISchemaRISourceEnded jsonData]
+ -[RISchemaRISourceEnded readFrom:]
+ -[RISchemaRISourceEnded remoteTimeInMs]
+ -[RISchemaRISourceEnded roundTripCount]
+ -[RISchemaRISourceEnded setExists:]
+ -[RISchemaRISourceEnded setHasExists:]
+ -[RISchemaRISourceEnded setHasRemoteTimeInMs:]
+ -[RISchemaRISourceEnded setHasRoundTripCount:]
+ -[RISchemaRISourceEnded setHasSizeInBytes:]
+ -[RISchemaRISourceEnded setRemoteTimeInMs:]
+ -[RISchemaRISourceEnded setRoundTripCount:]
+ -[RISchemaRISourceEnded setSizeInBytes:]
+ -[RISchemaRISourceEnded sizeInBytes]
+ -[RISchemaRISourceEnded writeTo:]
+ -[RISchemaRISourceFailed .cxx_destruct]
+ -[RISchemaRISourceFailed deleteError]
+ -[RISchemaRISourceFailed deleteExists]
+ -[RISchemaRISourceFailed deleteUnderUnderlyingError]
+ -[RISchemaRISourceFailed deleteUnderlyingError]
+ -[RISchemaRISourceFailed dictionaryRepresentation]
+ -[RISchemaRISourceFailed error]
+ -[RISchemaRISourceFailed exists]
+ -[RISchemaRISourceFailed hasError]
+ -[RISchemaRISourceFailed hasExists]
+ -[RISchemaRISourceFailed hasUnderUnderlyingError]
+ -[RISchemaRISourceFailed hasUnderlyingError]
+ -[RISchemaRISourceFailed hash]
+ -[RISchemaRISourceFailed initWithDictionary:]
+ -[RISchemaRISourceFailed initWithJSON:]
+ -[RISchemaRISourceFailed isEqual:]
+ -[RISchemaRISourceFailed jsonData]
+ -[RISchemaRISourceFailed readFrom:]
+ -[RISchemaRISourceFailed setError:]
+ -[RISchemaRISourceFailed setExists:]
+ -[RISchemaRISourceFailed setHasError:]
+ -[RISchemaRISourceFailed setHasExists:]
+ -[RISchemaRISourceFailed setHasUnderUnderlyingError:]
+ -[RISchemaRISourceFailed setHasUnderlyingError:]
+ -[RISchemaRISourceFailed setUnderUnderlyingError:]
+ -[RISchemaRISourceFailed setUnderlyingError:]
+ -[RISchemaRISourceFailed underUnderlyingError]
+ -[RISchemaRISourceFailed underlyingError]
+ -[RISchemaRISourceFailed writeTo:]
+ -[RISchemaRISourceStarted .cxx_destruct]
+ -[RISchemaRISourceStarted communicationType]
+ -[RISchemaRISourceStarted deleteCommunicationType]
+ -[RISchemaRISourceStarted deleteRiSessionId]
+ -[RISchemaRISourceStarted dictionaryRepresentation]
+ -[RISchemaRISourceStarted hasCommunicationType]
+ -[RISchemaRISourceStarted hasRiSessionId]
+ -[RISchemaRISourceStarted hash]
+ -[RISchemaRISourceStarted initWithDictionary:]
+ -[RISchemaRISourceStarted initWithJSON:]
+ -[RISchemaRISourceStarted isEqual:]
+ -[RISchemaRISourceStarted jsonData]
+ -[RISchemaRISourceStarted readFrom:]
+ -[RISchemaRISourceStarted riSessionId]
+ -[RISchemaRISourceStarted setCommunicationType:]
+ -[RISchemaRISourceStarted setHasCommunicationType:]
+ -[RISchemaRISourceStarted setHasRiSessionId:]
+ -[RISchemaRISourceStarted setRiSessionId:]
+ -[RISchemaRISourceStarted writeTo:]
+ -[RISessionSchemaRISessionClientEvent .cxx_destruct]
+ -[RISessionSchemaRISessionClientEvent deleteEventMetadata]
+ -[RISessionSchemaRISessionClientEvent deleteRemoteSessionContext]
+ -[RISessionSchemaRISessionClientEvent deleteSourceSessionContext]
+ -[RISessionSchemaRISessionClientEvent dictionaryRepresentation]
+ -[RISessionSchemaRISessionClientEvent eventMetadata]
+ -[RISessionSchemaRISessionClientEvent hasEventMetadata]
+ -[RISessionSchemaRISessionClientEvent hasRemoteSessionContext]
+ -[RISessionSchemaRISessionClientEvent hasSourceSessionContext]
+ -[RISessionSchemaRISessionClientEvent hash]
+ -[RISessionSchemaRISessionClientEvent initWithDictionary:]
+ -[RISessionSchemaRISessionClientEvent initWithJSON:]
+ -[RISessionSchemaRISessionClientEvent isEqual:]
+ -[RISessionSchemaRISessionClientEvent jsonData]
+ -[RISessionSchemaRISessionClientEvent qualifiedMessageName]
+ -[RISessionSchemaRISessionClientEvent readFrom:]
+ -[RISessionSchemaRISessionClientEvent remoteSessionContext]
+ -[RISessionSchemaRISessionClientEvent setEventMetadata:]
+ -[RISessionSchemaRISessionClientEvent setHasEventMetadata:]
+ -[RISessionSchemaRISessionClientEvent setHasRemoteSessionContext:]
+ -[RISessionSchemaRISessionClientEvent setHasSourceSessionContext:]
+ -[RISessionSchemaRISessionClientEvent setRemoteSessionContext:]
+ -[RISessionSchemaRISessionClientEvent setSourceSessionContext:]
+ -[RISessionSchemaRISessionClientEvent sourceSessionContext]
+ -[RISessionSchemaRISessionClientEvent whichEvent_Type]
+ -[RISessionSchemaRISessionClientEvent writeTo:]
+ -[RISessionSchemaRISessionClientEvent(Component) componentName]
+ -[RISessionSchemaRISessionClientEvent(Component) getComponentId]
+ -[RISessionSchemaRISessionClientEvent(InnerEventContainer) innerEvent]
+ -[RISessionSchemaRISessionClientEvent(InnerEventContainer) whichInnerEventType]
+ -[RISessionSchemaRISessionClientEvent(InstrumentationAdditions) getAnyEventType]
+ -[RISessionSchemaRISessionClientEventMetadata .cxx_destruct]
+ -[RISessionSchemaRISessionClientEventMetadata deleteRiSessionId]
+ -[RISessionSchemaRISessionClientEventMetadata dictionaryRepresentation]
+ -[RISessionSchemaRISessionClientEventMetadata hasRiSessionId]
+ -[RISessionSchemaRISessionClientEventMetadata hash]
+ -[RISessionSchemaRISessionClientEventMetadata initWithDictionary:]
+ -[RISessionSchemaRISessionClientEventMetadata initWithJSON:]
+ -[RISessionSchemaRISessionClientEventMetadata isEqual:]
+ -[RISessionSchemaRISessionClientEventMetadata jsonData]
+ -[RISessionSchemaRISessionClientEventMetadata readFrom:]
+ -[RISessionSchemaRISessionClientEventMetadata riSessionId]
+ -[RISessionSchemaRISessionClientEventMetadata setHasRiSessionId:]
+ -[RISessionSchemaRISessionClientEventMetadata setRiSessionId:]
+ -[RISessionSchemaRISessionClientEventMetadata writeTo:]
+ -[RISessionSchemaRISessionError .cxx_destruct]
+ -[RISessionSchemaRISessionError deleteErrorCode]
+ -[RISessionSchemaRISessionError deleteErrorDomain]
+ -[RISessionSchemaRISessionError dictionaryRepresentation]
+ -[RISessionSchemaRISessionError errorCode]
+ -[RISessionSchemaRISessionError errorDomain]
+ -[RISessionSchemaRISessionError hasErrorCode]
+ -[RISessionSchemaRISessionError hasErrorDomain]
+ -[RISessionSchemaRISessionError hash]
+ -[RISessionSchemaRISessionError initWithDictionary:]
+ -[RISessionSchemaRISessionError initWithJSON:]
+ -[RISessionSchemaRISessionError isEqual:]
+ -[RISessionSchemaRISessionError jsonData]
+ -[RISessionSchemaRISessionError readFrom:]
+ -[RISessionSchemaRISessionError setErrorCode:]
+ -[RISessionSchemaRISessionError setErrorDomain:]
+ -[RISessionSchemaRISessionError setHasErrorCode:]
+ -[RISessionSchemaRISessionError setHasErrorDomain:]
+ -[RISessionSchemaRISessionError writeTo:]
+ -[RISessionSchemaRISessionRemoteContext .cxx_destruct]
+ -[RISessionSchemaRISessionRemoteContext deleteEnded]
+ -[RISessionSchemaRISessionRemoteContext deleteFailed]
+ -[RISessionSchemaRISessionRemoteContext deleteStartedOrChanged]
+ -[RISessionSchemaRISessionRemoteContext dictionaryRepresentation]
+ -[RISessionSchemaRISessionRemoteContext ended]
+ -[RISessionSchemaRISessionRemoteContext failed]
+ -[RISessionSchemaRISessionRemoteContext hasEnded]
+ -[RISessionSchemaRISessionRemoteContext hasFailed]
+ -[RISessionSchemaRISessionRemoteContext hasStartedOrChanged]
+ -[RISessionSchemaRISessionRemoteContext hash]
+ -[RISessionSchemaRISessionRemoteContext initWithDictionary:]
+ -[RISessionSchemaRISessionRemoteContext initWithJSON:]
+ -[RISessionSchemaRISessionRemoteContext isEqual:]
+ -[RISessionSchemaRISessionRemoteContext jsonData]
+ -[RISessionSchemaRISessionRemoteContext readFrom:]
+ -[RISessionSchemaRISessionRemoteContext setEnded:]
+ -[RISessionSchemaRISessionRemoteContext setFailed:]
+ -[RISessionSchemaRISessionRemoteContext setHasEnded:]
+ -[RISessionSchemaRISessionRemoteContext setHasFailed:]
+ -[RISessionSchemaRISessionRemoteContext setHasStartedOrChanged:]
+ -[RISessionSchemaRISessionRemoteContext setStartedOrChanged:]
+ -[RISessionSchemaRISessionRemoteContext startedOrChanged]
+ -[RISessionSchemaRISessionRemoteContext whichContextevent]
+ -[RISessionSchemaRISessionRemoteContext writeTo:]
+ -[RISessionSchemaRISessionRemoteEnded deleteExists]
+ -[RISessionSchemaRISessionRemoteEnded dictionaryRepresentation]
+ -[RISessionSchemaRISessionRemoteEnded exists]
+ -[RISessionSchemaRISessionRemoteEnded hasExists]
+ -[RISessionSchemaRISessionRemoteEnded hash]
+ -[RISessionSchemaRISessionRemoteEnded initWithDictionary:]
+ -[RISessionSchemaRISessionRemoteEnded initWithJSON:]
+ -[RISessionSchemaRISessionRemoteEnded isEqual:]
+ -[RISessionSchemaRISessionRemoteEnded jsonData]
+ -[RISessionSchemaRISessionRemoteEnded readFrom:]
+ -[RISessionSchemaRISessionRemoteEnded setExists:]
+ -[RISessionSchemaRISessionRemoteEnded setHasExists:]
+ -[RISessionSchemaRISessionRemoteEnded writeTo:]
+ -[RISessionSchemaRISessionRemoteFailed .cxx_destruct]
+ -[RISessionSchemaRISessionRemoteFailed deleteError]
+ -[RISessionSchemaRISessionRemoteFailed deleteExists]
+ -[RISessionSchemaRISessionRemoteFailed deleteUnderUnderlyingError]
+ -[RISessionSchemaRISessionRemoteFailed deleteUnderlyingError]
+ -[RISessionSchemaRISessionRemoteFailed dictionaryRepresentation]
+ -[RISessionSchemaRISessionRemoteFailed error]
+ -[RISessionSchemaRISessionRemoteFailed exists]
+ -[RISessionSchemaRISessionRemoteFailed hasError]
+ -[RISessionSchemaRISessionRemoteFailed hasExists]
+ -[RISessionSchemaRISessionRemoteFailed hasUnderUnderlyingError]
+ -[RISessionSchemaRISessionRemoteFailed hasUnderlyingError]
+ -[RISessionSchemaRISessionRemoteFailed hash]
+ -[RISessionSchemaRISessionRemoteFailed initWithDictionary:]
+ -[RISessionSchemaRISessionRemoteFailed initWithJSON:]
+ -[RISessionSchemaRISessionRemoteFailed isEqual:]
+ -[RISessionSchemaRISessionRemoteFailed jsonData]
+ -[RISessionSchemaRISessionRemoteFailed readFrom:]
+ -[RISessionSchemaRISessionRemoteFailed setError:]
+ -[RISessionSchemaRISessionRemoteFailed setExists:]
+ -[RISessionSchemaRISessionRemoteFailed setHasError:]
+ -[RISessionSchemaRISessionRemoteFailed setHasExists:]
+ -[RISessionSchemaRISessionRemoteFailed setHasUnderUnderlyingError:]
+ -[RISessionSchemaRISessionRemoteFailed setHasUnderlyingError:]
+ -[RISessionSchemaRISessionRemoteFailed setUnderUnderlyingError:]
+ -[RISessionSchemaRISessionRemoteFailed setUnderlyingError:]
+ -[RISessionSchemaRISessionRemoteFailed underUnderlyingError]
+ -[RISessionSchemaRISessionRemoteFailed underlyingError]
+ -[RISessionSchemaRISessionRemoteFailed writeTo:]
+ -[RISessionSchemaRISessionRemoteStarted deleteExists]
+ -[RISessionSchemaRISessionRemoteStarted dictionaryRepresentation]
+ -[RISessionSchemaRISessionRemoteStarted exists]
+ -[RISessionSchemaRISessionRemoteStarted hasExists]
+ -[RISessionSchemaRISessionRemoteStarted hash]
+ -[RISessionSchemaRISessionRemoteStarted initWithDictionary:]
+ -[RISessionSchemaRISessionRemoteStarted initWithJSON:]
+ -[RISessionSchemaRISessionRemoteStarted isEqual:]
+ -[RISessionSchemaRISessionRemoteStarted jsonData]
+ -[RISessionSchemaRISessionRemoteStarted readFrom:]
+ -[RISessionSchemaRISessionRemoteStarted setExists:]
+ -[RISessionSchemaRISessionRemoteStarted setHasExists:]
+ -[RISessionSchemaRISessionRemoteStarted writeTo:]
+ -[RISessionSchemaRISessionSourceContext .cxx_destruct]
+ -[RISessionSchemaRISessionSourceContext deleteEnded]
+ -[RISessionSchemaRISessionSourceContext deleteFailed]
+ -[RISessionSchemaRISessionSourceContext deleteStartedOrChanged]
+ -[RISessionSchemaRISessionSourceContext dictionaryRepresentation]
+ -[RISessionSchemaRISessionSourceContext ended]
+ -[RISessionSchemaRISessionSourceContext failed]
+ -[RISessionSchemaRISessionSourceContext hasEnded]
+ -[RISessionSchemaRISessionSourceContext hasFailed]
+ -[RISessionSchemaRISessionSourceContext hasStartedOrChanged]
+ -[RISessionSchemaRISessionSourceContext hash]
+ -[RISessionSchemaRISessionSourceContext initWithDictionary:]
+ -[RISessionSchemaRISessionSourceContext initWithJSON:]
+ -[RISessionSchemaRISessionSourceContext isEqual:]
+ -[RISessionSchemaRISessionSourceContext jsonData]
+ -[RISessionSchemaRISessionSourceContext readFrom:]
+ -[RISessionSchemaRISessionSourceContext setEnded:]
+ -[RISessionSchemaRISessionSourceContext setFailed:]
+ -[RISessionSchemaRISessionSourceContext setHasEnded:]
+ -[RISessionSchemaRISessionSourceContext setHasFailed:]
+ -[RISessionSchemaRISessionSourceContext setHasStartedOrChanged:]
+ -[RISessionSchemaRISessionSourceContext setStartedOrChanged:]
+ -[RISessionSchemaRISessionSourceContext startedOrChanged]
+ -[RISessionSchemaRISessionSourceContext whichContextevent]
+ -[RISessionSchemaRISessionSourceContext writeTo:]
+ -[RISessionSchemaRISessionSourceEnded deleteExists]
+ -[RISessionSchemaRISessionSourceEnded dictionaryRepresentation]
+ -[RISessionSchemaRISessionSourceEnded exists]
+ -[RISessionSchemaRISessionSourceEnded hasExists]
+ -[RISessionSchemaRISessionSourceEnded hash]
+ -[RISessionSchemaRISessionSourceEnded initWithDictionary:]
+ -[RISessionSchemaRISessionSourceEnded initWithJSON:]
+ -[RISessionSchemaRISessionSourceEnded isEqual:]
+ -[RISessionSchemaRISessionSourceEnded jsonData]
+ -[RISessionSchemaRISessionSourceEnded readFrom:]
+ -[RISessionSchemaRISessionSourceEnded setExists:]
+ -[RISessionSchemaRISessionSourceEnded setHasExists:]
+ -[RISessionSchemaRISessionSourceEnded writeTo:]
+ -[RISessionSchemaRISessionSourceFailed .cxx_destruct]
+ -[RISessionSchemaRISessionSourceFailed deleteError]
+ -[RISessionSchemaRISessionSourceFailed deleteExists]
+ -[RISessionSchemaRISessionSourceFailed deleteUnderUnderlyingError]
+ -[RISessionSchemaRISessionSourceFailed deleteUnderlyingError]
+ -[RISessionSchemaRISessionSourceFailed dictionaryRepresentation]
+ -[RISessionSchemaRISessionSourceFailed error]
+ -[RISessionSchemaRISessionSourceFailed exists]
+ -[RISessionSchemaRISessionSourceFailed hasError]
+ -[RISessionSchemaRISessionSourceFailed hasExists]
+ -[RISessionSchemaRISessionSourceFailed hasUnderUnderlyingError]
+ -[RISessionSchemaRISessionSourceFailed hasUnderlyingError]
+ -[RISessionSchemaRISessionSourceFailed hash]
+ -[RISessionSchemaRISessionSourceFailed initWithDictionary:]
+ -[RISessionSchemaRISessionSourceFailed initWithJSON:]
+ -[RISessionSchemaRISessionSourceFailed isEqual:]
+ -[RISessionSchemaRISessionSourceFailed jsonData]
+ -[RISessionSchemaRISessionSourceFailed readFrom:]
+ -[RISessionSchemaRISessionSourceFailed setError:]
+ -[RISessionSchemaRISessionSourceFailed setExists:]
+ -[RISessionSchemaRISessionSourceFailed setHasError:]
+ -[RISessionSchemaRISessionSourceFailed setHasExists:]
+ -[RISessionSchemaRISessionSourceFailed setHasUnderUnderlyingError:]
+ -[RISessionSchemaRISessionSourceFailed setHasUnderlyingError:]
+ -[RISessionSchemaRISessionSourceFailed setUnderUnderlyingError:]
+ -[RISessionSchemaRISessionSourceFailed setUnderlyingError:]
+ -[RISessionSchemaRISessionSourceFailed underUnderlyingError]
+ -[RISessionSchemaRISessionSourceFailed underlyingError]
+ -[RISessionSchemaRISessionSourceFailed writeTo:]
+ -[RISessionSchemaRISessionSourceStarted communicationType]
+ -[RISessionSchemaRISessionSourceStarted deleteCommunicationType]
+ -[RISessionSchemaRISessionSourceStarted deleteExists]
+ -[RISessionSchemaRISessionSourceStarted dictionaryRepresentation]
+ -[RISessionSchemaRISessionSourceStarted exists]
+ -[RISessionSchemaRISessionSourceStarted hasCommunicationType]
+ -[RISessionSchemaRISessionSourceStarted hasExists]
+ -[RISessionSchemaRISessionSourceStarted hash]
+ -[RISessionSchemaRISessionSourceStarted initWithDictionary:]
+ -[RISessionSchemaRISessionSourceStarted initWithJSON:]
+ -[RISessionSchemaRISessionSourceStarted isEqual:]
+ -[RISessionSchemaRISessionSourceStarted jsonData]
+ -[RISessionSchemaRISessionSourceStarted readFrom:]
+ -[RISessionSchemaRISessionSourceStarted setCommunicationType:]
+ -[RISessionSchemaRISessionSourceStarted setExists:]
+ -[RISessionSchemaRISessionSourceStarted setHasCommunicationType:]
+ -[RISessionSchemaRISessionSourceStarted setHasExists:]
+ -[RISessionSchemaRISessionSourceStarted writeTo:]
+ -[SAMSchemaSAMRequestEnded deleteIsPQA]
+ -[SAMSchemaSAMRequestEnded hasIsPQA]
+ -[SAMSchemaSAMRequestEnded isPQA]
+ -[SAMSchemaSAMRequestEnded setHasIsPQA:]
+ -[SAMSchemaSAMRequestEnded setIsPQA:]
+ -[SAMSchemaWKAExecutionInfo deleteStepCount]
+ -[SAMSchemaWKAExecutionInfo hasStepCount]
+ -[SAMSchemaWKAExecutionInfo setHasStepCount:]
+ -[SAMSchemaWKAExecutionInfo setStepCount:]
+ -[SAMSchemaWKAExecutionInfo stepCount]
+ -[SASchemaSAClientEvent deleteSaRemoteSearchContext]
+ -[SASchemaSAClientEvent hasSaRemoteSearchContext]
+ -[SASchemaSAClientEvent saRemoteSearchContext]
+ -[SASchemaSAClientEvent setHasSaRemoteSearchContext:]
+ -[SASchemaSAClientEvent setSaRemoteSearchContext:]
+ -[SASchemaSARemoteSearchCanceled deleteExists]
+ -[SASchemaSARemoteSearchCanceled dictionaryRepresentation]
+ -[SASchemaSARemoteSearchCanceled exists]
+ -[SASchemaSARemoteSearchCanceled hasExists]
+ -[SASchemaSARemoteSearchCanceled hash]
+ -[SASchemaSARemoteSearchCanceled initWithDictionary:]
+ -[SASchemaSARemoteSearchCanceled initWithJSON:]
+ -[SASchemaSARemoteSearchCanceled isEqual:]
+ -[SASchemaSARemoteSearchCanceled jsonData]
+ -[SASchemaSARemoteSearchCanceled readFrom:]
+ -[SASchemaSARemoteSearchCanceled setExists:]
+ -[SASchemaSARemoteSearchCanceled setHasExists:]
+ -[SASchemaSARemoteSearchCanceled writeTo:]
+ -[SASchemaSARemoteSearchContext .cxx_destruct]
+ -[SASchemaSARemoteSearchContext canceled]
+ -[SASchemaSARemoteSearchContext deleteCanceled]
+ -[SASchemaSARemoteSearchContext deleteEnded]
+ -[SASchemaSARemoteSearchContext deleteFailed]
+ -[SASchemaSARemoteSearchContext deleteStartedOrChanged]
+ -[SASchemaSARemoteSearchContext dictionaryRepresentation]
+ -[SASchemaSARemoteSearchContext ended]
+ -[SASchemaSARemoteSearchContext failed]
+ -[SASchemaSARemoteSearchContext hasCanceled]
+ -[SASchemaSARemoteSearchContext hasEnded]
+ -[SASchemaSARemoteSearchContext hasFailed]
+ -[SASchemaSARemoteSearchContext hasStartedOrChanged]
+ -[SASchemaSARemoteSearchContext hash]
+ -[SASchemaSARemoteSearchContext initWithDictionary:]
+ -[SASchemaSARemoteSearchContext initWithJSON:]
+ -[SASchemaSARemoteSearchContext isEqual:]
+ -[SASchemaSARemoteSearchContext jsonData]
+ -[SASchemaSARemoteSearchContext readFrom:]
+ -[SASchemaSARemoteSearchContext setCanceled:]
+ -[SASchemaSARemoteSearchContext setEnded:]
+ -[SASchemaSARemoteSearchContext setFailed:]
+ -[SASchemaSARemoteSearchContext setHasCanceled:]
+ -[SASchemaSARemoteSearchContext setHasEnded:]
+ -[SASchemaSARemoteSearchContext setHasFailed:]
+ -[SASchemaSARemoteSearchContext setHasStartedOrChanged:]
+ -[SASchemaSARemoteSearchContext setStartedOrChanged:]
+ -[SASchemaSARemoteSearchContext startedOrChanged]
+ -[SASchemaSARemoteSearchContext whichContextevent]
+ -[SASchemaSARemoteSearchContext writeTo:]
+ -[SASchemaSARemoteSearchEnded deleteExists]
+ -[SASchemaSARemoteSearchEnded dictionaryRepresentation]
+ -[SASchemaSARemoteSearchEnded exists]
+ -[SASchemaSARemoteSearchEnded hasExists]
+ -[SASchemaSARemoteSearchEnded hash]
+ -[SASchemaSARemoteSearchEnded initWithDictionary:]
+ -[SASchemaSARemoteSearchEnded initWithJSON:]
+ -[SASchemaSARemoteSearchEnded isEqual:]
+ -[SASchemaSARemoteSearchEnded jsonData]
+ -[SASchemaSARemoteSearchEnded readFrom:]
+ -[SASchemaSARemoteSearchEnded setExists:]
+ -[SASchemaSARemoteSearchEnded setHasExists:]
+ -[SASchemaSARemoteSearchEnded writeTo:]
+ -[SASchemaSARemoteSearchFailed .cxx_destruct]
+ -[SASchemaSARemoteSearchFailed deleteError]
+ -[SASchemaSARemoteSearchFailed dictionaryRepresentation]
+ -[SASchemaSARemoteSearchFailed error]
+ -[SASchemaSARemoteSearchFailed hasError]
+ -[SASchemaSARemoteSearchFailed hash]
+ -[SASchemaSARemoteSearchFailed initWithDictionary:]
+ -[SASchemaSARemoteSearchFailed initWithJSON:]
+ -[SASchemaSARemoteSearchFailed isEqual:]
+ -[SASchemaSARemoteSearchFailed jsonData]
+ -[SASchemaSARemoteSearchFailed readFrom:]
+ -[SASchemaSARemoteSearchFailed setError:]
+ -[SASchemaSARemoteSearchFailed setHasError:]
+ -[SASchemaSARemoteSearchFailed writeTo:]
+ -[SASchemaSARemoteSearchStarted deleteExists]
+ -[SASchemaSARemoteSearchStarted dictionaryRepresentation]
+ -[SASchemaSARemoteSearchStarted exists]
+ -[SASchemaSARemoteSearchStarted hasExists]
+ -[SASchemaSARemoteSearchStarted hash]
+ -[SASchemaSARemoteSearchStarted initWithDictionary:]
+ -[SASchemaSARemoteSearchStarted initWithJSON:]
+ -[SASchemaSARemoteSearchStarted isEqual:]
+ -[SASchemaSARemoteSearchStarted jsonData]
+ -[SASchemaSARemoteSearchStarted readFrom:]
+ -[SASchemaSARemoteSearchStarted setExists:]
+ -[SASchemaSARemoteSearchStarted setHasExists:]
+ -[SASchemaSARemoteSearchStarted writeTo:]
+ -[SASchemaSARequestEnded deleteMultiDeviceRoutingMode]
+ -[SASchemaSARequestEnded hasMultiDeviceRoutingMode]
+ -[SASchemaSARequestEnded multiDeviceRoutingMode]
+ -[SASchemaSARequestEnded setHasMultiDeviceRoutingMode:]
+ -[SASchemaSARequestEnded setMultiDeviceRoutingMode:]
+ -[SISchemaClientEvent deleteUeiCarPlayBannerPreprocessedTapped]
+ -[SISchemaClientEvent deleteUeiResponseAppLaunchContext]
+ -[SISchemaClientEvent deleteUeiResponseScrolled]
+ -[SISchemaClientEvent hasUeiCarPlayBannerPreprocessedTapped]
+ -[SISchemaClientEvent hasUeiResponseAppLaunchContext]
+ -[SISchemaClientEvent hasUeiResponseScrolled]
+ -[SISchemaClientEvent setHasUeiCarPlayBannerPreprocessedTapped:]
+ -[SISchemaClientEvent setHasUeiResponseAppLaunchContext:]
+ -[SISchemaClientEvent setHasUeiResponseScrolled:]
+ -[SISchemaClientEvent setUeiCarPlayBannerPreprocessedTapped:]
+ -[SISchemaClientEvent setUeiResponseAppLaunchContext:]
+ -[SISchemaClientEvent setUeiResponseScrolled:]
+ -[SISchemaClientEvent ueiCarPlayBannerPreprocessedTapped]
+ -[SISchemaClientEvent ueiResponseAppLaunchContext]
+ -[SISchemaClientEvent ueiResponseScrolled]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped deleteExists]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped dictionaryRepresentation]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped exists]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped hasExists]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped hash]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped initWithDictionary:]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped initWithJSON:]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped isEqual:]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped jsonData]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped readFrom:]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped setExists:]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped setHasExists:]
+ -[SISchemaUEICarPlayBannerPreprocessedTapped writeTo:]
+ -[SISchemaUEIResponseAppLaunchCanceled deleteExists]
+ -[SISchemaUEIResponseAppLaunchCanceled dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchCanceled exists]
+ -[SISchemaUEIResponseAppLaunchCanceled hasExists]
+ -[SISchemaUEIResponseAppLaunchCanceled hash]
+ -[SISchemaUEIResponseAppLaunchCanceled initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchCanceled initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchCanceled isEqual:]
+ -[SISchemaUEIResponseAppLaunchCanceled jsonData]
+ -[SISchemaUEIResponseAppLaunchCanceled readFrom:]
+ -[SISchemaUEIResponseAppLaunchCanceled setExists:]
+ -[SISchemaUEIResponseAppLaunchCanceled setHasExists:]
+ -[SISchemaUEIResponseAppLaunchCanceled writeTo:]
+ -[SISchemaUEIResponseAppLaunchContext .cxx_destruct]
+ -[SISchemaUEIResponseAppLaunchContext canceled]
+ -[SISchemaUEIResponseAppLaunchContext deleteCanceled]
+ -[SISchemaUEIResponseAppLaunchContext deleteEnded]
+ -[SISchemaUEIResponseAppLaunchContext deleteFailed]
+ -[SISchemaUEIResponseAppLaunchContext deleteStartedOrChanged]
+ -[SISchemaUEIResponseAppLaunchContext dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchContext ended]
+ -[SISchemaUEIResponseAppLaunchContext failed]
+ -[SISchemaUEIResponseAppLaunchContext hasCanceled]
+ -[SISchemaUEIResponseAppLaunchContext hasEnded]
+ -[SISchemaUEIResponseAppLaunchContext hasFailed]
+ -[SISchemaUEIResponseAppLaunchContext hasStartedOrChanged]
+ -[SISchemaUEIResponseAppLaunchContext hash]
+ -[SISchemaUEIResponseAppLaunchContext initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchContext initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchContext isEqual:]
+ -[SISchemaUEIResponseAppLaunchContext jsonData]
+ -[SISchemaUEIResponseAppLaunchContext readFrom:]
+ -[SISchemaUEIResponseAppLaunchContext setCanceled:]
+ -[SISchemaUEIResponseAppLaunchContext setEnded:]
+ -[SISchemaUEIResponseAppLaunchContext setFailed:]
+ -[SISchemaUEIResponseAppLaunchContext setHasCanceled:]
+ -[SISchemaUEIResponseAppLaunchContext setHasEnded:]
+ -[SISchemaUEIResponseAppLaunchContext setHasFailed:]
+ -[SISchemaUEIResponseAppLaunchContext setHasStartedOrChanged:]
+ -[SISchemaUEIResponseAppLaunchContext setStartedOrChanged:]
+ -[SISchemaUEIResponseAppLaunchContext startedOrChanged]
+ -[SISchemaUEIResponseAppLaunchContext whichContextevent]
+ -[SISchemaUEIResponseAppLaunchContext writeTo:]
+ -[SISchemaUEIResponseAppLaunchEnded .cxx_destruct]
+ -[SISchemaUEIResponseAppLaunchEnded deleteExecutorAppIntentMetrics]
+ -[SISchemaUEIResponseAppLaunchEnded dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchEnded executorAppIntentMetrics]
+ -[SISchemaUEIResponseAppLaunchEnded hasExecutorAppIntentMetrics]
+ -[SISchemaUEIResponseAppLaunchEnded hash]
+ -[SISchemaUEIResponseAppLaunchEnded initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchEnded initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchEnded isEqual:]
+ -[SISchemaUEIResponseAppLaunchEnded jsonData]
+ -[SISchemaUEIResponseAppLaunchEnded readFrom:]
+ -[SISchemaUEIResponseAppLaunchEnded setExecutorAppIntentMetrics:]
+ -[SISchemaUEIResponseAppLaunchEnded setHasExecutorAppIntentMetrics:]
+ -[SISchemaUEIResponseAppLaunchEnded writeTo:]
+ -[SISchemaUEIResponseAppLaunchFailed .cxx_destruct]
+ -[SISchemaUEIResponseAppLaunchFailed addErrors:]
+ -[SISchemaUEIResponseAppLaunchFailed clearErrors]
+ -[SISchemaUEIResponseAppLaunchFailed deleteErrors]
+ -[SISchemaUEIResponseAppLaunchFailed dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchFailed errorsAtIndex:]
+ -[SISchemaUEIResponseAppLaunchFailed errorsCount]
+ -[SISchemaUEIResponseAppLaunchFailed errors]
+ -[SISchemaUEIResponseAppLaunchFailed hash]
+ -[SISchemaUEIResponseAppLaunchFailed initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchFailed initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchFailed isEqual:]
+ -[SISchemaUEIResponseAppLaunchFailed jsonData]
+ -[SISchemaUEIResponseAppLaunchFailed readFrom:]
+ -[SISchemaUEIResponseAppLaunchFailed setErrors:]
+ -[SISchemaUEIResponseAppLaunchFailed writeTo:]
+ -[SISchemaUEIResponseAppLaunchStarted deleteExists]
+ -[SISchemaUEIResponseAppLaunchStarted dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchStarted exists]
+ -[SISchemaUEIResponseAppLaunchStarted hasExists]
+ -[SISchemaUEIResponseAppLaunchStarted hash]
+ -[SISchemaUEIResponseAppLaunchStarted initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchStarted initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchStarted isEqual:]
+ -[SISchemaUEIResponseAppLaunchStarted jsonData]
+ -[SISchemaUEIResponseAppLaunchStarted readFrom:]
+ -[SISchemaUEIResponseAppLaunchStarted setExists:]
+ -[SISchemaUEIResponseAppLaunchStarted setHasExists:]
+ -[SISchemaUEIResponseAppLaunchStarted writeTo:]
+ -[SISchemaUEIResponseScrolled deleteReachedLastLine]
+ -[SISchemaUEIResponseScrolled dictionaryRepresentation]
+ -[SISchemaUEIResponseScrolled hasReachedLastLine]
+ -[SISchemaUEIResponseScrolled hash]
+ -[SISchemaUEIResponseScrolled initWithDictionary:]
+ -[SISchemaUEIResponseScrolled initWithJSON:]
+ -[SISchemaUEIResponseScrolled isEqual:]
+ -[SISchemaUEIResponseScrolled jsonData]
+ -[SISchemaUEIResponseScrolled reachedLastLine]
+ -[SISchemaUEIResponseScrolled readFrom:]
+ -[SISchemaUEIResponseScrolled setHasReachedLastLine:]
+ -[SISchemaUEIResponseScrolled setReachedLastLine:]
+ -[SISchemaUEIResponseScrolled writeTo:]
+ -[STSchemaSTEvent deleteStHybridLocalSearchContext]
+ -[STSchemaSTEvent deleteStMediaSearchContext]
+ -[STSchemaSTEvent deleteStMediaSearchMergeContext]
+ -[STSchemaSTEvent hasStHybridLocalSearchContext]
+ -[STSchemaSTEvent hasStMediaSearchContext]
+ -[STSchemaSTEvent hasStMediaSearchMergeContext]
+ -[STSchemaSTEvent setHasStHybridLocalSearchContext:]
+ -[STSchemaSTEvent setHasStMediaSearchContext:]
+ -[STSchemaSTEvent setHasStMediaSearchMergeContext:]
+ -[STSchemaSTEvent setStHybridLocalSearchContext:]
+ -[STSchemaSTEvent setStMediaSearchContext:]
+ -[STSchemaSTEvent setStMediaSearchMergeContext:]
+ -[STSchemaSTEvent stHybridLocalSearchContext]
+ -[STSchemaSTEvent stMediaSearchContext]
+ -[STSchemaSTEvent stMediaSearchMergeContext]
+ -[STSchemaSTHybridLocalSearchCanceled deleteExists]
+ -[STSchemaSTHybridLocalSearchCanceled dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchCanceled exists]
+ -[STSchemaSTHybridLocalSearchCanceled hasExists]
+ -[STSchemaSTHybridLocalSearchCanceled hash]
+ -[STSchemaSTHybridLocalSearchCanceled initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchCanceled initWithJSON:]
+ -[STSchemaSTHybridLocalSearchCanceled isEqual:]
+ -[STSchemaSTHybridLocalSearchCanceled jsonData]
+ -[STSchemaSTHybridLocalSearchCanceled readFrom:]
+ -[STSchemaSTHybridLocalSearchCanceled setExists:]
+ -[STSchemaSTHybridLocalSearchCanceled setHasExists:]
+ -[STSchemaSTHybridLocalSearchCanceled writeTo:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics .cxx_destruct]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics cascadeItemType]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics cascadeSetCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics deleteCascadeItemType]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics deleteCascadeSetCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics deleteDomainId]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics deleteItemsEnumeratedCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics deleteResultCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics domainId]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics hasCascadeItemType]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics hasCascadeSetCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics hasDomainId]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics hasItemsEnumeratedCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics hasResultCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics hash]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics initWithJSON:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics isEqual:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics itemsEnumeratedCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics jsonData]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics readFrom:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics resultCount]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setCascadeItemType:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setCascadeSetCount:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setDomainId:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setHasCascadeItemType:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setHasCascadeSetCount:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setHasDomainId:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setHasItemsEnumeratedCount:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setHasResultCount:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setItemsEnumeratedCount:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics setResultCount:]
+ -[STSchemaSTHybridLocalSearchCascadeDomainMetrics writeTo:]
+ -[STSchemaSTHybridLocalSearchContext .cxx_destruct]
+ -[STSchemaSTHybridLocalSearchContext canceled]
+ -[STSchemaSTHybridLocalSearchContext deleteCanceled]
+ -[STSchemaSTHybridLocalSearchContext deleteEnded]
+ -[STSchemaSTHybridLocalSearchContext deleteFailed]
+ -[STSchemaSTHybridLocalSearchContext deleteStartedOrChanged]
+ -[STSchemaSTHybridLocalSearchContext dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchContext ended]
+ -[STSchemaSTHybridLocalSearchContext failed]
+ -[STSchemaSTHybridLocalSearchContext hasCanceled]
+ -[STSchemaSTHybridLocalSearchContext hasEnded]
+ -[STSchemaSTHybridLocalSearchContext hasFailed]
+ -[STSchemaSTHybridLocalSearchContext hasStartedOrChanged]
+ -[STSchemaSTHybridLocalSearchContext hash]
+ -[STSchemaSTHybridLocalSearchContext initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchContext initWithJSON:]
+ -[STSchemaSTHybridLocalSearchContext isEqual:]
+ -[STSchemaSTHybridLocalSearchContext jsonData]
+ -[STSchemaSTHybridLocalSearchContext readFrom:]
+ -[STSchemaSTHybridLocalSearchContext setCanceled:]
+ -[STSchemaSTHybridLocalSearchContext setEnded:]
+ -[STSchemaSTHybridLocalSearchContext setFailed:]
+ -[STSchemaSTHybridLocalSearchContext setHasCanceled:]
+ -[STSchemaSTHybridLocalSearchContext setHasEnded:]
+ -[STSchemaSTHybridLocalSearchContext setHasFailed:]
+ -[STSchemaSTHybridLocalSearchContext setHasStartedOrChanged:]
+ -[STSchemaSTHybridLocalSearchContext setStartedOrChanged:]
+ -[STSchemaSTHybridLocalSearchContext startedOrChanged]
+ -[STSchemaSTHybridLocalSearchContext whichContextevent]
+ -[STSchemaSTHybridLocalSearchContext writeTo:]
+ -[STSchemaSTHybridLocalSearchEnded .cxx_destruct]
+ -[STSchemaSTHybridLocalSearchEnded addCascadeDomainMetrics:]
+ -[STSchemaSTHybridLocalSearchEnded addResult:]
+ -[STSchemaSTHybridLocalSearchEnded cascadeDomainMetricsAtIndex:]
+ -[STSchemaSTHybridLocalSearchEnded cascadeDomainMetricsCount]
+ -[STSchemaSTHybridLocalSearchEnded cascadeDomainMetrics]
+ -[STSchemaSTHybridLocalSearchEnded clearCascadeDomainMetrics]
+ -[STSchemaSTHybridLocalSearchEnded clearResult]
+ -[STSchemaSTHybridLocalSearchEnded deleteCascadeDomainMetrics]
+ -[STSchemaSTHybridLocalSearchEnded deleteResult]
+ -[STSchemaSTHybridLocalSearchEnded dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchEnded hash]
+ -[STSchemaSTHybridLocalSearchEnded initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchEnded initWithJSON:]
+ -[STSchemaSTHybridLocalSearchEnded isEqual:]
+ -[STSchemaSTHybridLocalSearchEnded jsonData]
+ -[STSchemaSTHybridLocalSearchEnded readFrom:]
+ -[STSchemaSTHybridLocalSearchEnded resultAtIndex:]
+ -[STSchemaSTHybridLocalSearchEnded resultCount]
+ -[STSchemaSTHybridLocalSearchEnded results]
+ -[STSchemaSTHybridLocalSearchEnded setCascadeDomainMetrics:]
+ -[STSchemaSTHybridLocalSearchEnded setResults:]
+ -[STSchemaSTHybridLocalSearchEnded writeTo:]
+ -[STSchemaSTHybridLocalSearchFailed .cxx_destruct]
+ -[STSchemaSTHybridLocalSearchFailed addErrors:]
+ -[STSchemaSTHybridLocalSearchFailed clearErrors]
+ -[STSchemaSTHybridLocalSearchFailed deleteErrors]
+ -[STSchemaSTHybridLocalSearchFailed dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchFailed errorsAtIndex:]
+ -[STSchemaSTHybridLocalSearchFailed errorsCount]
+ -[STSchemaSTHybridLocalSearchFailed errors]
+ -[STSchemaSTHybridLocalSearchFailed hash]
+ -[STSchemaSTHybridLocalSearchFailed initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchFailed initWithJSON:]
+ -[STSchemaSTHybridLocalSearchFailed isEqual:]
+ -[STSchemaSTHybridLocalSearchFailed jsonData]
+ -[STSchemaSTHybridLocalSearchFailed readFrom:]
+ -[STSchemaSTHybridLocalSearchFailed setErrors:]
+ -[STSchemaSTHybridLocalSearchFailed writeTo:]
+ -[STSchemaSTHybridLocalSearchResult .cxx_destruct]
+ -[STSchemaSTHybridLocalSearchResult bundleId]
+ -[STSchemaSTHybridLocalSearchResult deleteBundleId]
+ -[STSchemaSTHybridLocalSearchResult deleteFuzzyMatchScore]
+ -[STSchemaSTHybridLocalSearchResult deleteMatchedField]
+ -[STSchemaSTHybridLocalSearchResult deleteSource]
+ -[STSchemaSTHybridLocalSearchResult deleteStringMatchStrategy]
+ -[STSchemaSTHybridLocalSearchResult dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchResult fuzzyMatchScore]
+ -[STSchemaSTHybridLocalSearchResult hasBundleId]
+ -[STSchemaSTHybridLocalSearchResult hasFuzzyMatchScore]
+ -[STSchemaSTHybridLocalSearchResult hasMatchedField]
+ -[STSchemaSTHybridLocalSearchResult hasSource]
+ -[STSchemaSTHybridLocalSearchResult hasStringMatchStrategy]
+ -[STSchemaSTHybridLocalSearchResult hash]
+ -[STSchemaSTHybridLocalSearchResult initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchResult initWithJSON:]
+ -[STSchemaSTHybridLocalSearchResult isEqual:]
+ -[STSchemaSTHybridLocalSearchResult jsonData]
+ -[STSchemaSTHybridLocalSearchResult matchedField]
+ -[STSchemaSTHybridLocalSearchResult readFrom:]
+ -[STSchemaSTHybridLocalSearchResult setBundleId:]
+ -[STSchemaSTHybridLocalSearchResult setFuzzyMatchScore:]
+ -[STSchemaSTHybridLocalSearchResult setHasBundleId:]
+ -[STSchemaSTHybridLocalSearchResult setHasFuzzyMatchScore:]
+ -[STSchemaSTHybridLocalSearchResult setHasMatchedField:]
+ -[STSchemaSTHybridLocalSearchResult setHasSource:]
+ -[STSchemaSTHybridLocalSearchResult setHasStringMatchStrategy:]
+ -[STSchemaSTHybridLocalSearchResult setMatchedField:]
+ -[STSchemaSTHybridLocalSearchResult setSource:]
+ -[STSchemaSTHybridLocalSearchResult setStringMatchStrategy:]
+ -[STSchemaSTHybridLocalSearchResult source]
+ -[STSchemaSTHybridLocalSearchResult stringMatchStrategy]
+ -[STSchemaSTHybridLocalSearchResult writeTo:]
+ -[STSchemaSTHybridLocalSearchStarted deleteExists]
+ -[STSchemaSTHybridLocalSearchStarted dictionaryRepresentation]
+ -[STSchemaSTHybridLocalSearchStarted exists]
+ -[STSchemaSTHybridLocalSearchStarted hasExists]
+ -[STSchemaSTHybridLocalSearchStarted hash]
+ -[STSchemaSTHybridLocalSearchStarted initWithDictionary:]
+ -[STSchemaSTHybridLocalSearchStarted initWithJSON:]
+ -[STSchemaSTHybridLocalSearchStarted isEqual:]
+ -[STSchemaSTHybridLocalSearchStarted jsonData]
+ -[STSchemaSTHybridLocalSearchStarted readFrom:]
+ -[STSchemaSTHybridLocalSearchStarted setExists:]
+ -[STSchemaSTHybridLocalSearchStarted setHasExists:]
+ -[STSchemaSTHybridLocalSearchStarted writeTo:]
+ -[STSchemaSTMediaSearchCanceled deleteExists]
+ -[STSchemaSTMediaSearchCanceled dictionaryRepresentation]
+ -[STSchemaSTMediaSearchCanceled exists]
+ -[STSchemaSTMediaSearchCanceled hasExists]
+ -[STSchemaSTMediaSearchCanceled hash]
+ -[STSchemaSTMediaSearchCanceled initWithDictionary:]
+ -[STSchemaSTMediaSearchCanceled initWithJSON:]
+ -[STSchemaSTMediaSearchCanceled isEqual:]
+ -[STSchemaSTMediaSearchCanceled jsonData]
+ -[STSchemaSTMediaSearchCanceled readFrom:]
+ -[STSchemaSTMediaSearchCanceled setExists:]
+ -[STSchemaSTMediaSearchCanceled setHasExists:]
+ -[STSchemaSTMediaSearchCanceled writeTo:]
+ -[STSchemaSTMediaSearchContext .cxx_destruct]
+ -[STSchemaSTMediaSearchContext canceled]
+ -[STSchemaSTMediaSearchContext deleteCanceled]
+ -[STSchemaSTMediaSearchContext deleteEnded]
+ -[STSchemaSTMediaSearchContext deleteFailed]
+ -[STSchemaSTMediaSearchContext deleteStartedOrChanged]
+ -[STSchemaSTMediaSearchContext dictionaryRepresentation]
+ -[STSchemaSTMediaSearchContext ended]
+ -[STSchemaSTMediaSearchContext failed]
+ -[STSchemaSTMediaSearchContext hasCanceled]
+ -[STSchemaSTMediaSearchContext hasEnded]
+ -[STSchemaSTMediaSearchContext hasFailed]
+ -[STSchemaSTMediaSearchContext hasStartedOrChanged]
+ -[STSchemaSTMediaSearchContext hash]
+ -[STSchemaSTMediaSearchContext initWithDictionary:]
+ -[STSchemaSTMediaSearchContext initWithJSON:]
+ -[STSchemaSTMediaSearchContext isEqual:]
+ -[STSchemaSTMediaSearchContext jsonData]
+ -[STSchemaSTMediaSearchContext readFrom:]
+ -[STSchemaSTMediaSearchContext setCanceled:]
+ -[STSchemaSTMediaSearchContext setEnded:]
+ -[STSchemaSTMediaSearchContext setFailed:]
+ -[STSchemaSTMediaSearchContext setHasCanceled:]
+ -[STSchemaSTMediaSearchContext setHasEnded:]
+ -[STSchemaSTMediaSearchContext setHasFailed:]
+ -[STSchemaSTMediaSearchContext setHasStartedOrChanged:]
+ -[STSchemaSTMediaSearchContext setStartedOrChanged:]
+ -[STSchemaSTMediaSearchContext startedOrChanged]
+ -[STSchemaSTMediaSearchContext whichContextevent]
+ -[STSchemaSTMediaSearchContext writeTo:]
+ -[STSchemaSTMediaSearchEnded .cxx_destruct]
+ -[STSchemaSTMediaSearchEnded addResult:]
+ -[STSchemaSTMediaSearchEnded clearResult]
+ -[STSchemaSTMediaSearchEnded deleteResult]
+ -[STSchemaSTMediaSearchEnded deleteServerLatency]
+ -[STSchemaSTMediaSearchEnded dictionaryRepresentation]
+ -[STSchemaSTMediaSearchEnded hasServerLatency]
+ -[STSchemaSTMediaSearchEnded hash]
+ -[STSchemaSTMediaSearchEnded initWithDictionary:]
+ -[STSchemaSTMediaSearchEnded initWithJSON:]
+ -[STSchemaSTMediaSearchEnded isEqual:]
+ -[STSchemaSTMediaSearchEnded jsonData]
+ -[STSchemaSTMediaSearchEnded readFrom:]
+ -[STSchemaSTMediaSearchEnded resultAtIndex:]
+ -[STSchemaSTMediaSearchEnded resultCount]
+ -[STSchemaSTMediaSearchEnded results]
+ -[STSchemaSTMediaSearchEnded serverLatency]
+ -[STSchemaSTMediaSearchEnded setHasServerLatency:]
+ -[STSchemaSTMediaSearchEnded setResults:]
+ -[STSchemaSTMediaSearchEnded setServerLatency:]
+ -[STSchemaSTMediaSearchEnded writeTo:]
+ -[STSchemaSTMediaSearchFailed .cxx_destruct]
+ -[STSchemaSTMediaSearchFailed addErrors:]
+ -[STSchemaSTMediaSearchFailed clearErrors]
+ -[STSchemaSTMediaSearchFailed deleteErrors]
+ -[STSchemaSTMediaSearchFailed dictionaryRepresentation]
+ -[STSchemaSTMediaSearchFailed errorsAtIndex:]
+ -[STSchemaSTMediaSearchFailed errorsCount]
+ -[STSchemaSTMediaSearchFailed errors]
+ -[STSchemaSTMediaSearchFailed hash]
+ -[STSchemaSTMediaSearchFailed initWithDictionary:]
+ -[STSchemaSTMediaSearchFailed initWithJSON:]
+ -[STSchemaSTMediaSearchFailed isEqual:]
+ -[STSchemaSTMediaSearchFailed jsonData]
+ -[STSchemaSTMediaSearchFailed readFrom:]
+ -[STSchemaSTMediaSearchFailed setErrors:]
+ -[STSchemaSTMediaSearchFailed writeTo:]
+ -[STSchemaSTMediaSearchLatency averageTimeBetweenContentInMs]
+ -[STSchemaSTMediaSearchLatency contentEventCount]
+ -[STSchemaSTMediaSearchLatency contentStreamingDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteAverageTimeBetweenContentInMs]
+ -[STSchemaSTMediaSearchLatency deleteContentEventCount]
+ -[STSchemaSTMediaSearchLatency deleteContentStreamingDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteExecutorDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteExecutorModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteLongestTimeBetweenContentInMs]
+ -[STSchemaSTMediaSearchLatency deletePlannerDurationInMs]
+ -[STSchemaSTMediaSearchLatency deletePlannerModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteResponseGenerationDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteResponseGenerationModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteSafetyDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteSafetyModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency deleteTimeToFirstContentInMs]
+ -[STSchemaSTMediaSearchLatency deleteTimeToResponseFinishInMs]
+ -[STSchemaSTMediaSearchLatency deleteTimeToResponseStartInMs]
+ -[STSchemaSTMediaSearchLatency deleteTotalRequestDurationInMs]
+ -[STSchemaSTMediaSearchLatency dictionaryRepresentation]
+ -[STSchemaSTMediaSearchLatency executorDurationInMs]
+ -[STSchemaSTMediaSearchLatency executorModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasAverageTimeBetweenContentInMs]
+ -[STSchemaSTMediaSearchLatency hasContentEventCount]
+ -[STSchemaSTMediaSearchLatency hasContentStreamingDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasExecutorDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasExecutorModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasLongestTimeBetweenContentInMs]
+ -[STSchemaSTMediaSearchLatency hasPlannerDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasPlannerModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasResponseGenerationDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasResponseGenerationModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasSafetyDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasSafetyModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency hasTimeToFirstContentInMs]
+ -[STSchemaSTMediaSearchLatency hasTimeToResponseFinishInMs]
+ -[STSchemaSTMediaSearchLatency hasTimeToResponseStartInMs]
+ -[STSchemaSTMediaSearchLatency hasTotalRequestDurationInMs]
+ -[STSchemaSTMediaSearchLatency hash]
+ -[STSchemaSTMediaSearchLatency initWithDictionary:]
+ -[STSchemaSTMediaSearchLatency initWithJSON:]
+ -[STSchemaSTMediaSearchLatency isEqual:]
+ -[STSchemaSTMediaSearchLatency jsonData]
+ -[STSchemaSTMediaSearchLatency longestTimeBetweenContentInMs]
+ -[STSchemaSTMediaSearchLatency plannerDurationInMs]
+ -[STSchemaSTMediaSearchLatency plannerModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency readFrom:]
+ -[STSchemaSTMediaSearchLatency responseGenerationDurationInMs]
+ -[STSchemaSTMediaSearchLatency responseGenerationModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency safetyDurationInMs]
+ -[STSchemaSTMediaSearchLatency safetyModelDurationInMs]
+ -[STSchemaSTMediaSearchLatency setAverageTimeBetweenContentInMs:]
+ -[STSchemaSTMediaSearchLatency setContentEventCount:]
+ -[STSchemaSTMediaSearchLatency setContentStreamingDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setExecutorDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setExecutorModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasAverageTimeBetweenContentInMs:]
+ -[STSchemaSTMediaSearchLatency setHasContentEventCount:]
+ -[STSchemaSTMediaSearchLatency setHasContentStreamingDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasExecutorDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasExecutorModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasLongestTimeBetweenContentInMs:]
+ -[STSchemaSTMediaSearchLatency setHasPlannerDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasPlannerModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasResponseGenerationDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasResponseGenerationModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasSafetyDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasSafetyModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setHasTimeToFirstContentInMs:]
+ -[STSchemaSTMediaSearchLatency setHasTimeToResponseFinishInMs:]
+ -[STSchemaSTMediaSearchLatency setHasTimeToResponseStartInMs:]
+ -[STSchemaSTMediaSearchLatency setHasTotalRequestDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setLongestTimeBetweenContentInMs:]
+ -[STSchemaSTMediaSearchLatency setPlannerDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setPlannerModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setResponseGenerationDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setResponseGenerationModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setSafetyDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setSafetyModelDurationInMs:]
+ -[STSchemaSTMediaSearchLatency setTimeToFirstContentInMs:]
+ -[STSchemaSTMediaSearchLatency setTimeToResponseFinishInMs:]
+ -[STSchemaSTMediaSearchLatency setTimeToResponseStartInMs:]
+ -[STSchemaSTMediaSearchLatency setTotalRequestDurationInMs:]
+ -[STSchemaSTMediaSearchLatency timeToFirstContentInMs]
+ -[STSchemaSTMediaSearchLatency timeToResponseFinishInMs]
+ -[STSchemaSTMediaSearchLatency timeToResponseStartInMs]
+ -[STSchemaSTMediaSearchLatency totalRequestDurationInMs]
+ -[STSchemaSTMediaSearchLatency writeTo:]
+ -[STSchemaSTMediaSearchMergeCanceled deleteExists]
+ -[STSchemaSTMediaSearchMergeCanceled dictionaryRepresentation]
+ -[STSchemaSTMediaSearchMergeCanceled exists]
+ -[STSchemaSTMediaSearchMergeCanceled hasExists]
+ -[STSchemaSTMediaSearchMergeCanceled hash]
+ -[STSchemaSTMediaSearchMergeCanceled initWithDictionary:]
+ -[STSchemaSTMediaSearchMergeCanceled initWithJSON:]
+ -[STSchemaSTMediaSearchMergeCanceled isEqual:]
+ -[STSchemaSTMediaSearchMergeCanceled jsonData]
+ -[STSchemaSTMediaSearchMergeCanceled readFrom:]
+ -[STSchemaSTMediaSearchMergeCanceled setExists:]
+ -[STSchemaSTMediaSearchMergeCanceled setHasExists:]
+ -[STSchemaSTMediaSearchMergeCanceled writeTo:]
+ -[STSchemaSTMediaSearchMergeContext .cxx_destruct]
+ -[STSchemaSTMediaSearchMergeContext canceled]
+ -[STSchemaSTMediaSearchMergeContext deleteCanceled]
+ -[STSchemaSTMediaSearchMergeContext deleteEnded]
+ -[STSchemaSTMediaSearchMergeContext deleteFailed]
+ -[STSchemaSTMediaSearchMergeContext deleteStartedOrChanged]
+ -[STSchemaSTMediaSearchMergeContext dictionaryRepresentation]
+ -[STSchemaSTMediaSearchMergeContext ended]
+ -[STSchemaSTMediaSearchMergeContext failed]
+ -[STSchemaSTMediaSearchMergeContext hasCanceled]
+ -[STSchemaSTMediaSearchMergeContext hasEnded]
+ -[STSchemaSTMediaSearchMergeContext hasFailed]
+ -[STSchemaSTMediaSearchMergeContext hasStartedOrChanged]
+ -[STSchemaSTMediaSearchMergeContext hash]
+ -[STSchemaSTMediaSearchMergeContext initWithDictionary:]
+ -[STSchemaSTMediaSearchMergeContext initWithJSON:]
+ -[STSchemaSTMediaSearchMergeContext isEqual:]
+ -[STSchemaSTMediaSearchMergeContext jsonData]
+ -[STSchemaSTMediaSearchMergeContext readFrom:]
+ -[STSchemaSTMediaSearchMergeContext setCanceled:]
+ -[STSchemaSTMediaSearchMergeContext setEnded:]
+ -[STSchemaSTMediaSearchMergeContext setFailed:]
+ -[STSchemaSTMediaSearchMergeContext setHasCanceled:]
+ -[STSchemaSTMediaSearchMergeContext setHasEnded:]
+ -[STSchemaSTMediaSearchMergeContext setHasFailed:]
+ -[STSchemaSTMediaSearchMergeContext setHasStartedOrChanged:]
+ -[STSchemaSTMediaSearchMergeContext setStartedOrChanged:]
+ -[STSchemaSTMediaSearchMergeContext startedOrChanged]
+ -[STSchemaSTMediaSearchMergeContext whichContextevent]
+ -[STSchemaSTMediaSearchMergeContext writeTo:]
+ -[STSchemaSTMediaSearchMergeEnded .cxx_destruct]
+ -[STSchemaSTMediaSearchMergeEnded addResult:]
+ -[STSchemaSTMediaSearchMergeEnded clearResult]
+ -[STSchemaSTMediaSearchMergeEnded deleteMergeOutcome]
+ -[STSchemaSTMediaSearchMergeEnded deleteMergedItemCount]
+ -[STSchemaSTMediaSearchMergeEnded deletePegasusItemCount]
+ -[STSchemaSTMediaSearchMergeEnded deleteResult]
+ -[STSchemaSTMediaSearchMergeEnded dictionaryRepresentation]
+ -[STSchemaSTMediaSearchMergeEnded hasMergeOutcome]
+ -[STSchemaSTMediaSearchMergeEnded hasMergedItemCount]
+ -[STSchemaSTMediaSearchMergeEnded hasPegasusItemCount]
+ -[STSchemaSTMediaSearchMergeEnded hash]
+ -[STSchemaSTMediaSearchMergeEnded initWithDictionary:]
+ -[STSchemaSTMediaSearchMergeEnded initWithJSON:]
+ -[STSchemaSTMediaSearchMergeEnded isEqual:]
+ -[STSchemaSTMediaSearchMergeEnded jsonData]
+ -[STSchemaSTMediaSearchMergeEnded mergeOutcome]
+ -[STSchemaSTMediaSearchMergeEnded mergedItemCount]
+ -[STSchemaSTMediaSearchMergeEnded pegasusItemCount]
+ -[STSchemaSTMediaSearchMergeEnded readFrom:]
+ -[STSchemaSTMediaSearchMergeEnded resultAtIndex:]
+ -[STSchemaSTMediaSearchMergeEnded resultCount]
+ -[STSchemaSTMediaSearchMergeEnded results]
+ -[STSchemaSTMediaSearchMergeEnded setHasMergeOutcome:]
+ -[STSchemaSTMediaSearchMergeEnded setHasMergedItemCount:]
+ -[STSchemaSTMediaSearchMergeEnded setHasPegasusItemCount:]
+ -[STSchemaSTMediaSearchMergeEnded setMergeOutcome:]
+ -[STSchemaSTMediaSearchMergeEnded setMergedItemCount:]
+ -[STSchemaSTMediaSearchMergeEnded setPegasusItemCount:]
+ -[STSchemaSTMediaSearchMergeEnded setResults:]
+ -[STSchemaSTMediaSearchMergeEnded writeTo:]
+ -[STSchemaSTMediaSearchMergeFailed .cxx_destruct]
+ -[STSchemaSTMediaSearchMergeFailed addErrors:]
+ -[STSchemaSTMediaSearchMergeFailed clearErrors]
+ -[STSchemaSTMediaSearchMergeFailed deleteErrors]
+ -[STSchemaSTMediaSearchMergeFailed dictionaryRepresentation]
+ -[STSchemaSTMediaSearchMergeFailed errorsAtIndex:]
+ -[STSchemaSTMediaSearchMergeFailed errorsCount]
+ -[STSchemaSTMediaSearchMergeFailed errors]
+ -[STSchemaSTMediaSearchMergeFailed hash]
+ -[STSchemaSTMediaSearchMergeFailed initWithDictionary:]
+ -[STSchemaSTMediaSearchMergeFailed initWithJSON:]
+ -[STSchemaSTMediaSearchMergeFailed isEqual:]
+ -[STSchemaSTMediaSearchMergeFailed jsonData]
+ -[STSchemaSTMediaSearchMergeFailed readFrom:]
+ -[STSchemaSTMediaSearchMergeFailed setErrors:]
+ -[STSchemaSTMediaSearchMergeFailed writeTo:]
+ -[STSchemaSTMediaSearchMergeResult deleteMediaRank]
+ -[STSchemaSTMediaSearchMergeResult deleteMergedRank]
+ -[STSchemaSTMediaSearchMergeResult deleteWasAlsoReturnedByPegasus]
+ -[STSchemaSTMediaSearchMergeResult dictionaryRepresentation]
+ -[STSchemaSTMediaSearchMergeResult hasMediaRank]
+ -[STSchemaSTMediaSearchMergeResult hasMergedRank]
+ -[STSchemaSTMediaSearchMergeResult hasWasAlsoReturnedByPegasus]
+ -[STSchemaSTMediaSearchMergeResult hash]
+ -[STSchemaSTMediaSearchMergeResult initWithDictionary:]
+ -[STSchemaSTMediaSearchMergeResult initWithJSON:]
+ -[STSchemaSTMediaSearchMergeResult isEqual:]
+ -[STSchemaSTMediaSearchMergeResult jsonData]
+ -[STSchemaSTMediaSearchMergeResult mediaRank]
+ -[STSchemaSTMediaSearchMergeResult mergedRank]
+ -[STSchemaSTMediaSearchMergeResult readFrom:]
+ -[STSchemaSTMediaSearchMergeResult setHasMediaRank:]
+ -[STSchemaSTMediaSearchMergeResult setHasMergedRank:]
+ -[STSchemaSTMediaSearchMergeResult setHasWasAlsoReturnedByPegasus:]
+ -[STSchemaSTMediaSearchMergeResult setMediaRank:]
+ -[STSchemaSTMediaSearchMergeResult setMergedRank:]
+ -[STSchemaSTMediaSearchMergeResult setWasAlsoReturnedByPegasus:]
+ -[STSchemaSTMediaSearchMergeResult wasAlsoReturnedByPegasus]
+ -[STSchemaSTMediaSearchMergeResult writeTo:]
+ -[STSchemaSTMediaSearchMergeStarted deleteExists]
+ -[STSchemaSTMediaSearchMergeStarted dictionaryRepresentation]
+ -[STSchemaSTMediaSearchMergeStarted exists]
+ -[STSchemaSTMediaSearchMergeStarted hasExists]
+ -[STSchemaSTMediaSearchMergeStarted hash]
+ -[STSchemaSTMediaSearchMergeStarted initWithDictionary:]
+ -[STSchemaSTMediaSearchMergeStarted initWithJSON:]
+ -[STSchemaSTMediaSearchMergeStarted isEqual:]
+ -[STSchemaSTMediaSearchMergeStarted jsonData]
+ -[STSchemaSTMediaSearchMergeStarted readFrom:]
+ -[STSchemaSTMediaSearchMergeStarted setExists:]
+ -[STSchemaSTMediaSearchMergeStarted setHasExists:]
+ -[STSchemaSTMediaSearchMergeStarted writeTo:]
+ -[STSchemaSTMediaSearchResult deleteDomain]
+ -[STSchemaSTMediaSearchResult deleteMediaRank]
+ -[STSchemaSTMediaSearchResult deleteResultType]
+ -[STSchemaSTMediaSearchResult dictionaryRepresentation]
+ -[STSchemaSTMediaSearchResult domain]
+ -[STSchemaSTMediaSearchResult hasDomain]
+ -[STSchemaSTMediaSearchResult hasMediaRank]
+ -[STSchemaSTMediaSearchResult hasResultType]
+ -[STSchemaSTMediaSearchResult hash]
+ -[STSchemaSTMediaSearchResult initWithDictionary:]
+ -[STSchemaSTMediaSearchResult initWithJSON:]
+ -[STSchemaSTMediaSearchResult isEqual:]
+ -[STSchemaSTMediaSearchResult jsonData]
+ -[STSchemaSTMediaSearchResult mediaRank]
+ -[STSchemaSTMediaSearchResult readFrom:]
+ -[STSchemaSTMediaSearchResult resultType]
+ -[STSchemaSTMediaSearchResult setDomain:]
+ -[STSchemaSTMediaSearchResult setHasDomain:]
+ -[STSchemaSTMediaSearchResult setHasMediaRank:]
+ -[STSchemaSTMediaSearchResult setHasResultType:]
+ -[STSchemaSTMediaSearchResult setMediaRank:]
+ -[STSchemaSTMediaSearchResult setResultType:]
+ -[STSchemaSTMediaSearchResult writeTo:]
+ -[STSchemaSTMediaSearchStarted .cxx_destruct]
+ -[STSchemaSTMediaSearchStarted addRequestedDomain:]
+ -[STSchemaSTMediaSearchStarted clearRequestedDomain]
+ -[STSchemaSTMediaSearchStarted deleteIsConversationContinuation]
+ -[STSchemaSTMediaSearchStarted deleteRequestedDomain]
+ -[STSchemaSTMediaSearchStarted dictionaryRepresentation]
+ -[STSchemaSTMediaSearchStarted hasIsConversationContinuation]
+ -[STSchemaSTMediaSearchStarted hash]
+ -[STSchemaSTMediaSearchStarted initWithDictionary:]
+ -[STSchemaSTMediaSearchStarted initWithJSON:]
+ -[STSchemaSTMediaSearchStarted isConversationContinuation]
+ -[STSchemaSTMediaSearchStarted isEqual:]
+ -[STSchemaSTMediaSearchStarted jsonData]
+ -[STSchemaSTMediaSearchStarted readFrom:]
+ -[STSchemaSTMediaSearchStarted requestedDomainAtIndex:]
+ -[STSchemaSTMediaSearchStarted requestedDomainCount]
+ -[STSchemaSTMediaSearchStarted requestedDomains]
+ -[STSchemaSTMediaSearchStarted setHasIsConversationContinuation:]
+ -[STSchemaSTMediaSearchStarted setIsConversationContinuation:]
+ -[STSchemaSTMediaSearchStarted setRequestedDomains:]
+ -[STSchemaSTMediaSearchStarted writeTo:]
+ -[TCSchemaTCClassifyCanceled deleteExists]
+ -[TCSchemaTCClassifyCanceled dictionaryRepresentation]
+ -[TCSchemaTCClassifyCanceled exists]
+ -[TCSchemaTCClassifyCanceled hasExists]
+ -[TCSchemaTCClassifyCanceled hash]
+ -[TCSchemaTCClassifyCanceled initWithDictionary:]
+ -[TCSchemaTCClassifyCanceled initWithJSON:]
+ -[TCSchemaTCClassifyCanceled isEqual:]
+ -[TCSchemaTCClassifyCanceled jsonData]
+ -[TCSchemaTCClassifyCanceled readFrom:]
+ -[TCSchemaTCClassifyCanceled setExists:]
+ -[TCSchemaTCClassifyCanceled setHasExists:]
+ -[TCSchemaTCClassifyCanceled writeTo:]
+ -[TCSchemaTCClassifyContext .cxx_destruct]
+ -[TCSchemaTCClassifyContext canceled]
+ -[TCSchemaTCClassifyContext deleteCanceled]
+ -[TCSchemaTCClassifyContext deleteEnded]
+ -[TCSchemaTCClassifyContext deleteFailed]
+ -[TCSchemaTCClassifyContext deleteStartedOrChanged]
+ -[TCSchemaTCClassifyContext dictionaryRepresentation]
+ -[TCSchemaTCClassifyContext ended]
+ -[TCSchemaTCClassifyContext failed]
+ -[TCSchemaTCClassifyContext hasCanceled]
+ -[TCSchemaTCClassifyContext hasEnded]
+ -[TCSchemaTCClassifyContext hasFailed]
+ -[TCSchemaTCClassifyContext hasStartedOrChanged]
+ -[TCSchemaTCClassifyContext hash]
+ -[TCSchemaTCClassifyContext initWithDictionary:]
+ -[TCSchemaTCClassifyContext initWithJSON:]
+ -[TCSchemaTCClassifyContext isEqual:]
+ -[TCSchemaTCClassifyContext jsonData]
+ -[TCSchemaTCClassifyContext readFrom:]
+ -[TCSchemaTCClassifyContext setCanceled:]
+ -[TCSchemaTCClassifyContext setEnded:]
+ -[TCSchemaTCClassifyContext setFailed:]
+ -[TCSchemaTCClassifyContext setHasCanceled:]
+ -[TCSchemaTCClassifyContext setHasEnded:]
+ -[TCSchemaTCClassifyContext setHasFailed:]
+ -[TCSchemaTCClassifyContext setHasStartedOrChanged:]
+ -[TCSchemaTCClassifyContext setStartedOrChanged:]
+ -[TCSchemaTCClassifyContext startedOrChanged]
+ -[TCSchemaTCClassifyContext whichContextevent]
+ -[TCSchemaTCClassifyContext writeTo:]
+ -[TCSchemaTCClassifyEnded decision]
+ -[TCSchemaTCClassifyEnded deleteDecision]
+ -[TCSchemaTCClassifyEnded deleteOdmThreshold]
+ -[TCSchemaTCClassifyEnded deletePegasusThreshold]
+ -[TCSchemaTCClassifyEnded deleteScoreOdm]
+ -[TCSchemaTCClassifyEnded deleteScorePcc]
+ -[TCSchemaTCClassifyEnded deleteScorePegasus]
+ -[TCSchemaTCClassifyEnded dictionaryRepresentation]
+ -[TCSchemaTCClassifyEnded hasDecision]
+ -[TCSchemaTCClassifyEnded hasOdmThreshold]
+ -[TCSchemaTCClassifyEnded hasPegasusThreshold]
+ -[TCSchemaTCClassifyEnded hasScoreOdm]
+ -[TCSchemaTCClassifyEnded hasScorePcc]
+ -[TCSchemaTCClassifyEnded hasScorePegasus]
+ -[TCSchemaTCClassifyEnded hash]
+ -[TCSchemaTCClassifyEnded initWithDictionary:]
+ -[TCSchemaTCClassifyEnded initWithJSON:]
+ -[TCSchemaTCClassifyEnded isEqual:]
+ -[TCSchemaTCClassifyEnded jsonData]
+ -[TCSchemaTCClassifyEnded odmThreshold]
+ -[TCSchemaTCClassifyEnded pegasusThreshold]
+ -[TCSchemaTCClassifyEnded readFrom:]
+ -[TCSchemaTCClassifyEnded scoreOdm]
+ -[TCSchemaTCClassifyEnded scorePcc]
+ -[TCSchemaTCClassifyEnded scorePegasus]
+ -[TCSchemaTCClassifyEnded setDecision:]
+ -[TCSchemaTCClassifyEnded setHasDecision:]
+ -[TCSchemaTCClassifyEnded setHasOdmThreshold:]
+ -[TCSchemaTCClassifyEnded setHasPegasusThreshold:]
+ -[TCSchemaTCClassifyEnded setHasScoreOdm:]
+ -[TCSchemaTCClassifyEnded setHasScorePcc:]
+ -[TCSchemaTCClassifyEnded setHasScorePegasus:]
+ -[TCSchemaTCClassifyEnded setOdmThreshold:]
+ -[TCSchemaTCClassifyEnded setPegasusThreshold:]
+ -[TCSchemaTCClassifyEnded setScoreOdm:]
+ -[TCSchemaTCClassifyEnded setScorePcc:]
+ -[TCSchemaTCClassifyEnded setScorePegasus:]
+ -[TCSchemaTCClassifyEnded writeTo:]
+ -[TCSchemaTCClassifyFailed .cxx_destruct]
+ -[TCSchemaTCClassifyFailed addErrors:]
+ -[TCSchemaTCClassifyFailed clearErrors]
+ -[TCSchemaTCClassifyFailed deleteErrors]
+ -[TCSchemaTCClassifyFailed dictionaryRepresentation]
+ -[TCSchemaTCClassifyFailed errorsAtIndex:]
+ -[TCSchemaTCClassifyFailed errorsCount]
+ -[TCSchemaTCClassifyFailed errors]
+ -[TCSchemaTCClassifyFailed hash]
+ -[TCSchemaTCClassifyFailed initWithDictionary:]
+ -[TCSchemaTCClassifyFailed initWithJSON:]
+ -[TCSchemaTCClassifyFailed isEqual:]
+ -[TCSchemaTCClassifyFailed jsonData]
+ -[TCSchemaTCClassifyFailed readFrom:]
+ -[TCSchemaTCClassifyFailed setErrors:]
+ -[TCSchemaTCClassifyFailed writeTo:]
+ -[TCSchemaTCClassifyStarted deleteIsShadowMode]
+ -[TCSchemaTCClassifyStarted dictionaryRepresentation]
+ -[TCSchemaTCClassifyStarted hasIsShadowMode]
+ -[TCSchemaTCClassifyStarted hash]
+ -[TCSchemaTCClassifyStarted initWithDictionary:]
+ -[TCSchemaTCClassifyStarted initWithJSON:]
+ -[TCSchemaTCClassifyStarted isEqual:]
+ -[TCSchemaTCClassifyStarted isShadowMode]
+ -[TCSchemaTCClassifyStarted jsonData]
+ -[TCSchemaTCClassifyStarted readFrom:]
+ -[TCSchemaTCClassifyStarted setHasIsShadowMode:]
+ -[TCSchemaTCClassifyStarted setIsShadowMode:]
+ -[TCSchemaTCClassifyStarted writeTo:]
+ -[TCSchemaTCClientEvent .cxx_destruct]
+ -[TCSchemaTCClientEvent classifyContext]
+ -[TCSchemaTCClientEvent deleteClassifyContext]
+ -[TCSchemaTCClientEvent deleteEventMetadata]
+ -[TCSchemaTCClientEvent deleteLoadContext]
+ -[TCSchemaTCClientEvent dictionaryRepresentation]
+ -[TCSchemaTCClientEvent eventMetadata]
+ -[TCSchemaTCClientEvent hasClassifyContext]
+ -[TCSchemaTCClientEvent hasEventMetadata]
+ -[TCSchemaTCClientEvent hasLoadContext]
+ -[TCSchemaTCClientEvent hash]
+ -[TCSchemaTCClientEvent initWithDictionary:]
+ -[TCSchemaTCClientEvent initWithJSON:]
+ -[TCSchemaTCClientEvent isEqual:]
+ -[TCSchemaTCClientEvent jsonData]
+ -[TCSchemaTCClientEvent loadContext]
+ -[TCSchemaTCClientEvent qualifiedMessageName]
+ -[TCSchemaTCClientEvent readFrom:]
+ -[TCSchemaTCClientEvent setClassifyContext:]
+ -[TCSchemaTCClientEvent setEventMetadata:]
+ -[TCSchemaTCClientEvent setHasClassifyContext:]
+ -[TCSchemaTCClientEvent setHasEventMetadata:]
+ -[TCSchemaTCClientEvent setHasLoadContext:]
+ -[TCSchemaTCClientEvent setLoadContext:]
+ -[TCSchemaTCClientEvent whichEvent_Type]
+ -[TCSchemaTCClientEvent writeTo:]
+ -[TCSchemaTCClientEvent(Component) componentName]
+ -[TCSchemaTCClientEvent(Component) getComponentId]
+ -[TCSchemaTCClientEvent(InnerEventContainer) innerEvent]
+ -[TCSchemaTCClientEvent(InnerEventContainer) whichInnerEventType]
+ -[TCSchemaTCClientEvent(InstrumentationAdditions) getAnyEventType]
+ -[TCSchemaTCClientEventMetadata .cxx_destruct]
+ -[TCSchemaTCClientEventMetadata deleteTcId]
+ -[TCSchemaTCClientEventMetadata dictionaryRepresentation]
+ -[TCSchemaTCClientEventMetadata hasTcId]
+ -[TCSchemaTCClientEventMetadata hash]
+ -[TCSchemaTCClientEventMetadata initWithDictionary:]
+ -[TCSchemaTCClientEventMetadata initWithJSON:]
+ -[TCSchemaTCClientEventMetadata isEqual:]
+ -[TCSchemaTCClientEventMetadata jsonData]
+ -[TCSchemaTCClientEventMetadata readFrom:]
+ -[TCSchemaTCClientEventMetadata setHasTcId:]
+ -[TCSchemaTCClientEventMetadata setTcId:]
+ -[TCSchemaTCClientEventMetadata tcId]
+ -[TCSchemaTCClientEventMetadata writeTo:]
+ -[TCSchemaTCLoadCanceled deleteExists]
+ -[TCSchemaTCLoadCanceled dictionaryRepresentation]
+ -[TCSchemaTCLoadCanceled exists]
+ -[TCSchemaTCLoadCanceled hasExists]
+ -[TCSchemaTCLoadCanceled hash]
+ -[TCSchemaTCLoadCanceled initWithDictionary:]
+ -[TCSchemaTCLoadCanceled initWithJSON:]
+ -[TCSchemaTCLoadCanceled isEqual:]
+ -[TCSchemaTCLoadCanceled jsonData]
+ -[TCSchemaTCLoadCanceled readFrom:]
+ -[TCSchemaTCLoadCanceled setExists:]
+ -[TCSchemaTCLoadCanceled setHasExists:]
+ -[TCSchemaTCLoadCanceled writeTo:]
+ -[TCSchemaTCLoadContext .cxx_destruct]
+ -[TCSchemaTCLoadContext canceled]
+ -[TCSchemaTCLoadContext deleteCanceled]
+ -[TCSchemaTCLoadContext deleteEnded]
+ -[TCSchemaTCLoadContext deleteFailed]
+ -[TCSchemaTCLoadContext deleteStartedOrChanged]
+ -[TCSchemaTCLoadContext dictionaryRepresentation]
+ -[TCSchemaTCLoadContext ended]
+ -[TCSchemaTCLoadContext failed]
+ -[TCSchemaTCLoadContext hasCanceled]
+ -[TCSchemaTCLoadContext hasEnded]
+ -[TCSchemaTCLoadContext hasFailed]
+ -[TCSchemaTCLoadContext hasStartedOrChanged]
+ -[TCSchemaTCLoadContext hash]
+ -[TCSchemaTCLoadContext initWithDictionary:]
+ -[TCSchemaTCLoadContext initWithJSON:]
+ -[TCSchemaTCLoadContext isEqual:]
+ -[TCSchemaTCLoadContext jsonData]
+ -[TCSchemaTCLoadContext readFrom:]
+ -[TCSchemaTCLoadContext setCanceled:]
+ -[TCSchemaTCLoadContext setEnded:]
+ -[TCSchemaTCLoadContext setFailed:]
+ -[TCSchemaTCLoadContext setHasCanceled:]
+ -[TCSchemaTCLoadContext setHasEnded:]
+ -[TCSchemaTCLoadContext setHasFailed:]
+ -[TCSchemaTCLoadContext setHasStartedOrChanged:]
+ -[TCSchemaTCLoadContext setStartedOrChanged:]
+ -[TCSchemaTCLoadContext startedOrChanged]
+ -[TCSchemaTCLoadContext whichContextevent]
+ -[TCSchemaTCLoadContext writeTo:]
+ -[TCSchemaTCLoadEnded deleteExists]
+ -[TCSchemaTCLoadEnded dictionaryRepresentation]
+ -[TCSchemaTCLoadEnded exists]
+ -[TCSchemaTCLoadEnded hasExists]
+ -[TCSchemaTCLoadEnded hash]
+ -[TCSchemaTCLoadEnded initWithDictionary:]
+ -[TCSchemaTCLoadEnded initWithJSON:]
+ -[TCSchemaTCLoadEnded isEqual:]
+ -[TCSchemaTCLoadEnded jsonData]
+ -[TCSchemaTCLoadEnded readFrom:]
+ -[TCSchemaTCLoadEnded setExists:]
+ -[TCSchemaTCLoadEnded setHasExists:]
+ -[TCSchemaTCLoadEnded writeTo:]
+ -[TCSchemaTCLoadFailed .cxx_destruct]
+ -[TCSchemaTCLoadFailed addErrors:]
+ -[TCSchemaTCLoadFailed clearErrors]
+ -[TCSchemaTCLoadFailed deleteErrors]
+ -[TCSchemaTCLoadFailed dictionaryRepresentation]
+ -[TCSchemaTCLoadFailed errorsAtIndex:]
+ -[TCSchemaTCLoadFailed errorsCount]
+ -[TCSchemaTCLoadFailed errors]
+ -[TCSchemaTCLoadFailed hash]
+ -[TCSchemaTCLoadFailed initWithDictionary:]
+ -[TCSchemaTCLoadFailed initWithJSON:]
+ -[TCSchemaTCLoadFailed isEqual:]
+ -[TCSchemaTCLoadFailed jsonData]
+ -[TCSchemaTCLoadFailed readFrom:]
+ -[TCSchemaTCLoadFailed setErrors:]
+ -[TCSchemaTCLoadFailed writeTo:]
+ -[TCSchemaTCLoadStarted deleteExists]
+ -[TCSchemaTCLoadStarted dictionaryRepresentation]
+ -[TCSchemaTCLoadStarted exists]
+ -[TCSchemaTCLoadStarted hasExists]
+ -[TCSchemaTCLoadStarted hash]
+ -[TCSchemaTCLoadStarted initWithDictionary:]
+ -[TCSchemaTCLoadStarted initWithJSON:]
+ -[TCSchemaTCLoadStarted isEqual:]
+ -[TCSchemaTCLoadStarted jsonData]
+ -[TCSchemaTCLoadStarted readFrom:]
+ -[TCSchemaTCLoadStarted setExists:]
+ -[TCSchemaTCLoadStarted setHasExists:]
+ -[TCSchemaTCLoadStarted writeTo:]
+ OBJC_IVAR_$_ASRSchemaASRRecognitionMetrics._numActivatedNCBVQEntitiesFromJIT
+ OBJC_IVAR_$_CHSchemaCHAgenticGradingInferenceGenerated._evaluatorMetadata
+ OBJC_IVAR_$_CHSchemaCHAgenticGradingInferenceGenerated._graderResult
+ OBJC_IVAR_$_CHSchemaCHAgenticGradingInferenceGenerated._graderType
+ OBJC_IVAR_$_CHSchemaCHAgenticGradingInferenceGenerated._has
+ OBJC_IVAR_$_CHSchemaCHClientEvent._agenticGradingInferenceGenerated
+ OBJC_IVAR_$_CHSchemaCHGraderResult._speechGradingInferenceMetadata
+ OBJC_IVAR_$_CHSchemaCHSpeechCriterionResult._categoryScore
+ OBJC_IVAR_$_CHSchemaCHSpeechCriterionResult._criterionId
+ OBJC_IVAR_$_CHSchemaCHSpeechCriterionResult._has
+ OBJC_IVAR_$_CHSchemaCHSpeechCriterionResult._verdict
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._applicableWeightMilliunits
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._asrRisk
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._confMarginBucket
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._criterionResults
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._errorClass
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._gated
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._has
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._judged
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._latencyBucket
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._mode
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._nBestPhrases
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._notJudgedReason
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._numInteractionsConsidered
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._numInteractionsGraded
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._parseOutcome
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._phrasesWithChoice
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._provider
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._queryRewritten
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._regrade
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._retries
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._rubricVersion
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._runId
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._runSampleProbability
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._sampleAgreement
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._samples
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._score
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._selectedHypothesisIndex
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._selectionOutcome
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._thin
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._topHypothesisConfBucket
+ OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._totalWeightMilliunits
+ OBJC_IVAR_$_CPRSchemaCPRActiveRuntimeSwitchAttempted._has
+ OBJC_IVAR_$_CPRSchemaCPRActiveRuntimeSwitchAttempted._outcome
+ OBJC_IVAR_$_CPRSchemaCPRActiveRuntimeSwitchAttempted._reason
+ OBJC_IVAR_$_CPRSchemaCPRArchitectureUsed._activeRuntimeAtRequestStart
+ OBJC_IVAR_$_CPRSchemaCPRArchitectureUsed._rootIfSessionId
+ OBJC_IVAR_$_CPRSchemaCPRClientEvent._activeRuntimeSwitchAttempted
+ OBJC_IVAR_$_CPRSchemaCPRClientEvent._architectureUsed
+ OBJC_IVAR_$_DIMSchemaDIMDeviceFixedContext._dataSharingPromptVersion
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorActionPoisoningClassifierCallEnded._inputCharCount
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorAppIntentMetrics._isRemoteExecution
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorClientEvent._executorInjectableContentClassifierCallContext
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled._exists
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled._has
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._appIntentSessionId
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._canceled
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._ended
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._failed
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._has
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._startedOrChanged
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded._classifierOutcome
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded._has
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded._inputCharCount
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed._errors
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted._exists
+ OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted._has
+ OBJC_IVAR_$_GMSSchemaGMSExtendedInferenceMetrics._routingDecision
+ OBJC_IVAR_$_IDENTITYSchemaIDENTITYClientEvent._speakerIdResultReceived
+ OBJC_IVAR_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived._has
+ OBJC_IVAR_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived._hasVoiceTrigger
+ OBJC_IVAR_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived._milestone
+ OBJC_IVAR_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived._perceptionClassification
+ OBJC_IVAR_$_LRSchemaLRRedactionExclusionSignal._excludedScope
+ OBJC_IVAR_$_LRSchemaLRRedactionExclusionSignal._has
+ OBJC_IVAR_$_LRSchemaLRRedactionExclusionSignal._reason
+ OBJC_IVAR_$_LRSchemaLRRedactionSignal._excludedSignals
+ OBJC_IVAR_$_NLXSchemaNLXClientEventMetadata._requesterFlow
+ OBJC_IVAR_$_ODDSiriSchemaODDAnnounceProperties._isAnnounceEligible
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._countOfFactoryAssetsInAssetSet
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._countOfOTAAssetsInAssetSet
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._countOfPSUSAssetsInAssetSet
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._currentBuildVersion
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._totalSizeOfFactoryAssetsInAssetSet
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._totalSizeOfOTAAssetsInAssetSet
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._totalSizeOfPSUSAssetsInAssetSet
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantLLMSiriCounts._tokenCounts
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantLLMSiriDimensions._appPartyTypes
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._eventStreamResultType
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._promptType
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._provider
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._has
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._inputTokenBucketOdm
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._inputTokenBucketPcc
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._outputTokenBucketOdm
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._outputTokenBucketPcc
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._tokenBucketScheme
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._totalTokenBucketOdm
+ OBJC_IVAR_$_ODDSiriSchemaODDLLMSiriTokenCounts._totalTokenBucketPcc
+ OBJC_IVAR_$_ODDSiriSchemaODDwatchOSAssistantProperties._announce
+ OBJC_IVAR_$_ORCHSchemaORCHClientEvent._speakerIdentificationResultReceived
+ OBJC_IVAR_$_ORCHSchemaORCHClientEvent._speakerIdentificationSettled
+ OBJC_IVAR_$_ORCHSchemaORCHIFProxyRequestFailed._errors
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._dropReason
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._elapsedSinceActivationInMs
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._elapsedToForwardCompletedInMs
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._failureReason
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._has
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._identityAggressors
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._isGuest
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._isRecentlySeen
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._phase
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._resultOrdinal
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._userIdentityClassification
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._wasForwarded
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._wasIdentityTransition
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationSettled._has
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationSettled._numEnrolledMembers
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationSettled._numIdentityTransitions
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationSettled._numResultsReceived
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationSettled._stateAtSettlement
+ OBJC_IVAR_$_PLANNERSchemaPLANNERClientEvent._userIdentityChecked
+ OBJC_IVAR_$_PLANNERSchemaPLANNERClientEvent._userIdentityConfirmationRequested
+ OBJC_IVAR_$_PLANNERSchemaPLANNERClientEvent._userIdentityConfirmationResolved
+ OBJC_IVAR_$_PLANNERSchemaPLANNERIPIClassifierEnded._inputCharCount
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityChecked._gate
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityChecked._has
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityChecked._isRecentlySeen
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityChecked._outcome
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityChecked._userClassification
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested._has
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested._promptOrdinal
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested._userClassification
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved._error
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved._has
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved._outcome
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved._promptOrdinal
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSEntityRef._has
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSEntityRef._provenance
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._errorResults
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._generalResults
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._successResults
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult._errorCode
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult._errorKind
+ OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult._has
+ OBJC_IVAR_$_RISchemaRIClientEvent._eventMetadata
+ OBJC_IVAR_$_RISchemaRIClientEvent._remoteContext
+ OBJC_IVAR_$_RISchemaRIClientEvent._sourceContext
+ OBJC_IVAR_$_RISchemaRIClientEventMetadata._riId
+ OBJC_IVAR_$_RISchemaRIError._errorCode
+ OBJC_IVAR_$_RISchemaRIError._errorDomain
+ OBJC_IVAR_$_RISchemaRIError._has
+ OBJC_IVAR_$_RISchemaRIRemoteContext._ended
+ OBJC_IVAR_$_RISchemaRIRemoteContext._failed
+ OBJC_IVAR_$_RISchemaRIRemoteContext._startedOrChanged
+ OBJC_IVAR_$_RISchemaRIRemoteEnded._exists
+ OBJC_IVAR_$_RISchemaRIRemoteEnded._has
+ OBJC_IVAR_$_RISchemaRIRemoteFailed._error
+ OBJC_IVAR_$_RISchemaRIRemoteFailed._exists
+ OBJC_IVAR_$_RISchemaRIRemoteFailed._has
+ OBJC_IVAR_$_RISchemaRIRemoteFailed._underUnderlyingError
+ OBJC_IVAR_$_RISchemaRIRemoteFailed._underlyingError
+ OBJC_IVAR_$_RISchemaRIRemoteStarted._has
+ OBJC_IVAR_$_RISchemaRIRemoteStarted._isColdLaunch
+ OBJC_IVAR_$_RISchemaRIRemoteStarted._riSessionId
+ OBJC_IVAR_$_RISchemaRISourceContext._ended
+ OBJC_IVAR_$_RISchemaRISourceContext._failed
+ OBJC_IVAR_$_RISchemaRISourceContext._startedOrChanged
+ OBJC_IVAR_$_RISchemaRISourceEnded._exists
+ OBJC_IVAR_$_RISchemaRISourceEnded._has
+ OBJC_IVAR_$_RISchemaRISourceEnded._remoteTimeInMs
+ OBJC_IVAR_$_RISchemaRISourceEnded._roundTripCount
+ OBJC_IVAR_$_RISchemaRISourceEnded._sizeInBytes
+ OBJC_IVAR_$_RISchemaRISourceFailed._error
+ OBJC_IVAR_$_RISchemaRISourceFailed._exists
+ OBJC_IVAR_$_RISchemaRISourceFailed._has
+ OBJC_IVAR_$_RISchemaRISourceFailed._underUnderlyingError
+ OBJC_IVAR_$_RISchemaRISourceFailed._underlyingError
+ OBJC_IVAR_$_RISchemaRISourceStarted._communicationType
+ OBJC_IVAR_$_RISchemaRISourceStarted._has
+ OBJC_IVAR_$_RISchemaRISourceStarted._riSessionId
+ OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._eventMetadata
+ OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._remoteSessionContext
+ OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._sourceSessionContext
+ OBJC_IVAR_$_RISessionSchemaRISessionClientEventMetadata._riSessionId
+ OBJC_IVAR_$_RISessionSchemaRISessionError._errorCode
+ OBJC_IVAR_$_RISessionSchemaRISessionError._errorDomain
+ OBJC_IVAR_$_RISessionSchemaRISessionError._has
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._ended
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._failed
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._startedOrChanged
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteEnded._exists
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteEnded._has
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._error
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._exists
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._has
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._underUnderlyingError
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._underlyingError
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteStarted._exists
+ OBJC_IVAR_$_RISessionSchemaRISessionRemoteStarted._has
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._ended
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._failed
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._startedOrChanged
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceEnded._exists
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceEnded._has
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._error
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._exists
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._has
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._underUnderlyingError
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._underlyingError
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceStarted._communicationType
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceStarted._exists
+ OBJC_IVAR_$_RISessionSchemaRISessionSourceStarted._has
+ OBJC_IVAR_$_SAMSchemaSAMRequestEnded._has
+ OBJC_IVAR_$_SAMSchemaSAMRequestEnded._isPQA
+ OBJC_IVAR_$_SAMSchemaWKAExecutionInfo._stepCount
+ OBJC_IVAR_$_SASchemaSAClientEvent._saRemoteSearchContext
+ OBJC_IVAR_$_SASchemaSARemoteSearchCanceled._exists
+ OBJC_IVAR_$_SASchemaSARemoteSearchCanceled._has
+ OBJC_IVAR_$_SASchemaSARemoteSearchContext._canceled
+ OBJC_IVAR_$_SASchemaSARemoteSearchContext._ended
+ OBJC_IVAR_$_SASchemaSARemoteSearchContext._failed
+ OBJC_IVAR_$_SASchemaSARemoteSearchContext._startedOrChanged
+ OBJC_IVAR_$_SASchemaSARemoteSearchEnded._exists
+ OBJC_IVAR_$_SASchemaSARemoteSearchEnded._has
+ OBJC_IVAR_$_SASchemaSARemoteSearchFailed._error
+ OBJC_IVAR_$_SASchemaSARemoteSearchStarted._exists
+ OBJC_IVAR_$_SASchemaSARemoteSearchStarted._has
+ OBJC_IVAR_$_SASchemaSARequestEnded._multiDeviceRoutingMode
+ OBJC_IVAR_$_SISchemaClientEvent._ueiCarPlayBannerPreprocessedTapped
+ OBJC_IVAR_$_SISchemaClientEvent._ueiResponseAppLaunchContext
+ OBJC_IVAR_$_SISchemaClientEvent._ueiResponseScrolled
+ OBJC_IVAR_$_SISchemaUEICarPlayBannerPreprocessedTapped._exists
+ OBJC_IVAR_$_SISchemaUEICarPlayBannerPreprocessedTapped._has
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchCanceled._exists
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchCanceled._has
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._canceled
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._ended
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._failed
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._startedOrChanged
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchEnded._executorAppIntentMetrics
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchFailed._errors
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchStarted._exists
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchStarted._has
+ OBJC_IVAR_$_SISchemaUEIResponseScrolled._has
+ OBJC_IVAR_$_SISchemaUEIResponseScrolled._reachedLastLine
+ OBJC_IVAR_$_STSchemaSTEvent._stHybridLocalSearchContext
+ OBJC_IVAR_$_STSchemaSTEvent._stMediaSearchContext
+ OBJC_IVAR_$_STSchemaSTEvent._stMediaSearchMergeContext
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCanceled._exists
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCanceled._has
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._cascadeItemType
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._cascadeSetCount
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._domainId
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._has
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._itemsEnumeratedCount
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._resultCount
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._canceled
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._ended
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._failed
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._startedOrChanged
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchEnded._cascadeDomainMetrics
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchEnded._results
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchFailed._errors
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._bundleId
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._fuzzyMatchScore
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._has
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._matchedField
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._source
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._stringMatchStrategy
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchStarted._exists
+ OBJC_IVAR_$_STSchemaSTHybridLocalSearchStarted._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchCanceled._exists
+ OBJC_IVAR_$_STSchemaSTMediaSearchCanceled._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchContext._canceled
+ OBJC_IVAR_$_STSchemaSTMediaSearchContext._ended
+ OBJC_IVAR_$_STSchemaSTMediaSearchContext._failed
+ OBJC_IVAR_$_STSchemaSTMediaSearchContext._startedOrChanged
+ OBJC_IVAR_$_STSchemaSTMediaSearchEnded._results
+ OBJC_IVAR_$_STSchemaSTMediaSearchEnded._serverLatency
+ OBJC_IVAR_$_STSchemaSTMediaSearchFailed._errors
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._averageTimeBetweenContentInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._contentEventCount
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._contentStreamingDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._executorDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._executorModelDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._longestTimeBetweenContentInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._plannerDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._plannerModelDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._responseGenerationDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._responseGenerationModelDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._safetyDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._safetyModelDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._timeToFirstContentInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._timeToResponseFinishInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._timeToResponseStartInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchLatency._totalRequestDurationInMs
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeCanceled._exists
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeCanceled._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._canceled
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._ended
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._failed
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._startedOrChanged
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeEnded._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeEnded._mergeOutcome
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeEnded._mergedItemCount
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeEnded._pegasusItemCount
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeEnded._results
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeFailed._errors
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeResult._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeResult._mediaRank
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeResult._mergedRank
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeResult._wasAlsoReturnedByPegasus
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeStarted._exists
+ OBJC_IVAR_$_STSchemaSTMediaSearchMergeStarted._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchResult._domain
+ OBJC_IVAR_$_STSchemaSTMediaSearchResult._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchResult._mediaRank
+ OBJC_IVAR_$_STSchemaSTMediaSearchResult._resultType
+ OBJC_IVAR_$_STSchemaSTMediaSearchStarted._has
+ OBJC_IVAR_$_STSchemaSTMediaSearchStarted._isConversationContinuation
+ OBJC_IVAR_$_STSchemaSTMediaSearchStarted._requestedDomains
+ OBJC_IVAR_$_TCSchemaTCClassifyCanceled._exists
+ OBJC_IVAR_$_TCSchemaTCClassifyCanceled._has
+ OBJC_IVAR_$_TCSchemaTCClassifyContext._canceled
+ OBJC_IVAR_$_TCSchemaTCClassifyContext._ended
+ OBJC_IVAR_$_TCSchemaTCClassifyContext._failed
+ OBJC_IVAR_$_TCSchemaTCClassifyContext._startedOrChanged
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._decision
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._has
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._odmThreshold
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._pegasusThreshold
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._scoreOdm
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._scorePcc
+ OBJC_IVAR_$_TCSchemaTCClassifyEnded._scorePegasus
+ OBJC_IVAR_$_TCSchemaTCClassifyFailed._errors
+ OBJC_IVAR_$_TCSchemaTCClassifyStarted._has
+ OBJC_IVAR_$_TCSchemaTCClassifyStarted._isShadowMode
+ OBJC_IVAR_$_TCSchemaTCClientEvent._classifyContext
+ OBJC_IVAR_$_TCSchemaTCClientEvent._eventMetadata
+ OBJC_IVAR_$_TCSchemaTCClientEvent._loadContext
+ OBJC_IVAR_$_TCSchemaTCClientEventMetadata._tcId
+ OBJC_IVAR_$_TCSchemaTCLoadCanceled._exists
+ OBJC_IVAR_$_TCSchemaTCLoadCanceled._has
+ OBJC_IVAR_$_TCSchemaTCLoadContext._canceled
+ OBJC_IVAR_$_TCSchemaTCLoadContext._ended
+ OBJC_IVAR_$_TCSchemaTCLoadContext._failed
+ OBJC_IVAR_$_TCSchemaTCLoadContext._startedOrChanged
+ OBJC_IVAR_$_TCSchemaTCLoadEnded._exists
+ OBJC_IVAR_$_TCSchemaTCLoadEnded._has
+ OBJC_IVAR_$_TCSchemaTCLoadFailed._errors
+ OBJC_IVAR_$_TCSchemaTCLoadStarted._exists
+ OBJC_IVAR_$_TCSchemaTCLoadStarted._has
+ _OBJC_CLASS_$_CHSchemaCHAgenticGradingInferenceGenerated
+ _OBJC_CLASS_$_CHSchemaCHGraderResult
+ _OBJC_CLASS_$_CHSchemaCHSpeechCriterionResult
+ _OBJC_CLASS_$_CHSchemaCHSpeechGradingInferenceMetadata
+ _OBJC_CLASS_$_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ _OBJC_CLASS_$_CPRSchemaCPRArchitectureUsed
+ _OBJC_CLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ _OBJC_CLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ _OBJC_CLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ _OBJC_CLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ _OBJC_CLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ _OBJC_CLASS_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ _OBJC_CLASS_$_LRSchemaLRRedactionExclusionSignal
+ _OBJC_CLASS_$_ODDSiriSchemaODDLLMSiriTokenCounts
+ _OBJC_CLASS_$_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ _OBJC_CLASS_$_ORCHSchemaORCHSpeakerIdentificationSettled
+ _OBJC_CLASS_$_PLANNERSchemaPLANNERUserIdentityChecked
+ _OBJC_CLASS_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ _OBJC_CLASS_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ _OBJC_CLASS_$_RISchemaRIClientEvent
+ _OBJC_CLASS_$_RISchemaRIClientEventMetadata
+ _OBJC_CLASS_$_RISchemaRIError
+ _OBJC_CLASS_$_RISchemaRIRemoteContext
+ _OBJC_CLASS_$_RISchemaRIRemoteEnded
+ _OBJC_CLASS_$_RISchemaRIRemoteFailed
+ _OBJC_CLASS_$_RISchemaRIRemoteStarted
+ _OBJC_CLASS_$_RISchemaRISourceContext
+ _OBJC_CLASS_$_RISchemaRISourceEnded
+ _OBJC_CLASS_$_RISchemaRISourceFailed
+ _OBJC_CLASS_$_RISchemaRISourceStarted
+ _OBJC_CLASS_$_RISessionSchemaRISessionClientEvent
+ _OBJC_CLASS_$_RISessionSchemaRISessionClientEventMetadata
+ _OBJC_CLASS_$_RISessionSchemaRISessionError
+ _OBJC_CLASS_$_RISessionSchemaRISessionRemoteContext
+ _OBJC_CLASS_$_RISessionSchemaRISessionRemoteEnded
+ _OBJC_CLASS_$_RISessionSchemaRISessionRemoteFailed
+ _OBJC_CLASS_$_RISessionSchemaRISessionRemoteStarted
+ _OBJC_CLASS_$_RISessionSchemaRISessionSourceContext
+ _OBJC_CLASS_$_RISessionSchemaRISessionSourceEnded
+ _OBJC_CLASS_$_RISessionSchemaRISessionSourceFailed
+ _OBJC_CLASS_$_RISessionSchemaRISessionSourceStarted
+ _OBJC_CLASS_$_SASchemaSARemoteSearchCanceled
+ _OBJC_CLASS_$_SASchemaSARemoteSearchContext
+ _OBJC_CLASS_$_SASchemaSARemoteSearchEnded
+ _OBJC_CLASS_$_SASchemaSARemoteSearchFailed
+ _OBJC_CLASS_$_SASchemaSARemoteSearchStarted
+ _OBJC_CLASS_$_SISchemaUEICarPlayBannerPreprocessedTapped
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchCanceled
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchContext
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchEnded
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchFailed
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchStarted
+ _OBJC_CLASS_$_SISchemaUEIResponseScrolled
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchCanceled
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchContext
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchEnded
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchFailed
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchResult
+ _OBJC_CLASS_$_STSchemaSTHybridLocalSearchStarted
+ _OBJC_CLASS_$_STSchemaSTMediaSearchCanceled
+ _OBJC_CLASS_$_STSchemaSTMediaSearchContext
+ _OBJC_CLASS_$_STSchemaSTMediaSearchEnded
+ _OBJC_CLASS_$_STSchemaSTMediaSearchFailed
+ _OBJC_CLASS_$_STSchemaSTMediaSearchLatency
+ _OBJC_CLASS_$_STSchemaSTMediaSearchMergeCanceled
+ _OBJC_CLASS_$_STSchemaSTMediaSearchMergeContext
+ _OBJC_CLASS_$_STSchemaSTMediaSearchMergeEnded
+ _OBJC_CLASS_$_STSchemaSTMediaSearchMergeFailed
+ _OBJC_CLASS_$_STSchemaSTMediaSearchMergeResult
+ _OBJC_CLASS_$_STSchemaSTMediaSearchMergeStarted
+ _OBJC_CLASS_$_STSchemaSTMediaSearchResult
+ _OBJC_CLASS_$_STSchemaSTMediaSearchStarted
+ _OBJC_CLASS_$_TCSchemaTCClassifyCanceled
+ _OBJC_CLASS_$_TCSchemaTCClassifyContext
+ _OBJC_CLASS_$_TCSchemaTCClassifyEnded
+ _OBJC_CLASS_$_TCSchemaTCClassifyFailed
+ _OBJC_CLASS_$_TCSchemaTCClassifyStarted
+ _OBJC_CLASS_$_TCSchemaTCClientEvent
+ _OBJC_CLASS_$_TCSchemaTCClientEventMetadata
+ _OBJC_CLASS_$_TCSchemaTCLoadCanceled
+ _OBJC_CLASS_$_TCSchemaTCLoadContext
+ _OBJC_CLASS_$_TCSchemaTCLoadEnded
+ _OBJC_CLASS_$_TCSchemaTCLoadFailed
+ _OBJC_CLASS_$_TCSchemaTCLoadStarted
+ _OBJC_IVAR_$_CHSchemaCHAgenticGradingInferenceGenerated._hasEvaluatorMetadata
+ _OBJC_IVAR_$_CHSchemaCHAgenticGradingInferenceGenerated._hasGraderResult
+ _OBJC_IVAR_$_CHSchemaCHClientEvent._hasAgenticGradingInferenceGenerated
+ _OBJC_IVAR_$_CHSchemaCHGraderResult._hasSpeechGradingInferenceMetadata
+ _OBJC_IVAR_$_CHSchemaCHGraderResult._whichGraderresult
+ _OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._hasProvider
+ _OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._hasRubricVersion
+ _OBJC_IVAR_$_CHSchemaCHSpeechGradingInferenceMetadata._hasRunId
+ _OBJC_IVAR_$_CPRSchemaCPRActiveRuntimeSwitchAttempted._hasReason
+ _OBJC_IVAR_$_CPRSchemaCPRArchitectureUsed._hasActiveRuntimeAtRequestStart
+ _OBJC_IVAR_$_CPRSchemaCPRArchitectureUsed._hasRootIfSessionId
+ _OBJC_IVAR_$_CPRSchemaCPRClientEvent._hasActiveRuntimeSwitchAttempted
+ _OBJC_IVAR_$_CPRSchemaCPRClientEvent._hasArchitectureUsed
+ _OBJC_IVAR_$_ExecutorSiriSchemaExecutorClientEvent._hasExecutorInjectableContentClassifierCallContext
+ _OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._hasCanceled
+ _OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._hasEnded
+ _OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._hasFailed
+ _OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._hasStartedOrChanged
+ _OBJC_IVAR_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext._whichContextevent
+ _OBJC_IVAR_$_GMSSchemaGMSExtendedInferenceMetrics._hasRoutingDecision
+ _OBJC_IVAR_$_IDENTITYSchemaIDENTITYClientEvent._hasSpeakerIdResultReceived
+ _OBJC_IVAR_$_LRSchemaLRRedactionExclusionSignal._hasExcludedScope
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssetBringUpStatus._hasCurrentBuildVersion
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantLLMSiriCounts._hasTokenCounts
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._hasProvider
+ _OBJC_IVAR_$_ODDSiriSchemaODDwatchOSAssistantProperties._hasAnnounce
+ _OBJC_IVAR_$_ORCHSchemaORCHClientEvent._hasSpeakerIdentificationResultReceived
+ _OBJC_IVAR_$_ORCHSchemaORCHClientEvent._hasSpeakerIdentificationSettled
+ _OBJC_IVAR_$_PLANNERSchemaPLANNERClientEvent._hasUserIdentityChecked
+ _OBJC_IVAR_$_PLANNERSchemaPLANNERClientEvent._hasUserIdentityConfirmationRequested
+ _OBJC_IVAR_$_PLANNERSchemaPLANNERClientEvent._hasUserIdentityConfirmationResolved
+ _OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved._hasError
+ _OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._hasErrorResults
+ _OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._hasGeneralResults
+ _OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._hasSuccessResults
+ _OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionEnded._whichPlannertoolsresult
+ _OBJC_IVAR_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult._hasErrorCode
+ _OBJC_IVAR_$_RISchemaRIClientEvent._hasEventMetadata
+ _OBJC_IVAR_$_RISchemaRIClientEvent._hasRemoteContext
+ _OBJC_IVAR_$_RISchemaRIClientEvent._hasSourceContext
+ _OBJC_IVAR_$_RISchemaRIClientEvent._whichEvent_Type
+ _OBJC_IVAR_$_RISchemaRIClientEventMetadata._hasRiId
+ _OBJC_IVAR_$_RISchemaRIError._hasErrorDomain
+ _OBJC_IVAR_$_RISchemaRIRemoteContext._hasEnded
+ _OBJC_IVAR_$_RISchemaRIRemoteContext._hasFailed
+ _OBJC_IVAR_$_RISchemaRIRemoteContext._hasStartedOrChanged
+ _OBJC_IVAR_$_RISchemaRIRemoteContext._whichContextevent
+ _OBJC_IVAR_$_RISchemaRIRemoteFailed._hasError
+ _OBJC_IVAR_$_RISchemaRIRemoteFailed._hasUnderUnderlyingError
+ _OBJC_IVAR_$_RISchemaRIRemoteFailed._hasUnderlyingError
+ _OBJC_IVAR_$_RISchemaRIRemoteStarted._hasRiSessionId
+ _OBJC_IVAR_$_RISchemaRISourceContext._hasEnded
+ _OBJC_IVAR_$_RISchemaRISourceContext._hasFailed
+ _OBJC_IVAR_$_RISchemaRISourceContext._hasStartedOrChanged
+ _OBJC_IVAR_$_RISchemaRISourceContext._whichContextevent
+ _OBJC_IVAR_$_RISchemaRISourceFailed._hasError
+ _OBJC_IVAR_$_RISchemaRISourceFailed._hasUnderUnderlyingError
+ _OBJC_IVAR_$_RISchemaRISourceFailed._hasUnderlyingError
+ _OBJC_IVAR_$_RISchemaRISourceStarted._hasRiSessionId
+ _OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._hasEventMetadata
+ _OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._hasRemoteSessionContext
+ _OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._hasSourceSessionContext
+ _OBJC_IVAR_$_RISessionSchemaRISessionClientEvent._whichEvent_Type
+ _OBJC_IVAR_$_RISessionSchemaRISessionClientEventMetadata._hasRiSessionId
+ _OBJC_IVAR_$_RISessionSchemaRISessionError._hasErrorDomain
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._hasEnded
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._hasFailed
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._hasStartedOrChanged
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteContext._whichContextevent
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._hasError
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._hasUnderUnderlyingError
+ _OBJC_IVAR_$_RISessionSchemaRISessionRemoteFailed._hasUnderlyingError
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._hasEnded
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._hasFailed
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._hasStartedOrChanged
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceContext._whichContextevent
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._hasError
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._hasUnderUnderlyingError
+ _OBJC_IVAR_$_RISessionSchemaRISessionSourceFailed._hasUnderlyingError
+ _OBJC_IVAR_$_SASchemaSAClientEvent._hasSaRemoteSearchContext
+ _OBJC_IVAR_$_SASchemaSARemoteSearchContext._hasCanceled
+ _OBJC_IVAR_$_SASchemaSARemoteSearchContext._hasEnded
+ _OBJC_IVAR_$_SASchemaSARemoteSearchContext._hasFailed
+ _OBJC_IVAR_$_SASchemaSARemoteSearchContext._hasStartedOrChanged
+ _OBJC_IVAR_$_SASchemaSARemoteSearchContext._whichContextevent
+ _OBJC_IVAR_$_SASchemaSARemoteSearchFailed._hasError
+ _OBJC_IVAR_$_SISchemaClientEvent._hasUeiCarPlayBannerPreprocessedTapped
+ _OBJC_IVAR_$_SISchemaClientEvent._hasUeiResponseAppLaunchContext
+ _OBJC_IVAR_$_SISchemaClientEvent._hasUeiResponseScrolled
+ _OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasCanceled
+ _OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasEnded
+ _OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasFailed
+ _OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasStartedOrChanged
+ _OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._whichContextevent
+ _OBJC_IVAR_$_SISchemaUEIResponseAppLaunchEnded._hasExecutorAppIntentMetrics
+ _OBJC_IVAR_$_STSchemaSTEvent._hasStHybridLocalSearchContext
+ _OBJC_IVAR_$_STSchemaSTEvent._hasStMediaSearchContext
+ _OBJC_IVAR_$_STSchemaSTEvent._hasStMediaSearchMergeContext
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics._hasDomainId
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._hasCanceled
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._hasEnded
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._hasFailed
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._hasStartedOrChanged
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchContext._whichContextevent
+ _OBJC_IVAR_$_STSchemaSTHybridLocalSearchResult._hasBundleId
+ _OBJC_IVAR_$_STSchemaSTMediaSearchContext._hasCanceled
+ _OBJC_IVAR_$_STSchemaSTMediaSearchContext._hasEnded
+ _OBJC_IVAR_$_STSchemaSTMediaSearchContext._hasFailed
+ _OBJC_IVAR_$_STSchemaSTMediaSearchContext._hasStartedOrChanged
+ _OBJC_IVAR_$_STSchemaSTMediaSearchContext._whichContextevent
+ _OBJC_IVAR_$_STSchemaSTMediaSearchEnded._hasServerLatency
+ _OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._hasCanceled
+ _OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._hasEnded
+ _OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._hasFailed
+ _OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._hasStartedOrChanged
+ _OBJC_IVAR_$_STSchemaSTMediaSearchMergeContext._whichContextevent
+ _OBJC_IVAR_$_TCSchemaTCClassifyContext._hasCanceled
+ _OBJC_IVAR_$_TCSchemaTCClassifyContext._hasEnded
+ _OBJC_IVAR_$_TCSchemaTCClassifyContext._hasFailed
+ _OBJC_IVAR_$_TCSchemaTCClassifyContext._hasStartedOrChanged
+ _OBJC_IVAR_$_TCSchemaTCClassifyContext._whichContextevent
+ _OBJC_IVAR_$_TCSchemaTCClientEvent._hasClassifyContext
+ _OBJC_IVAR_$_TCSchemaTCClientEvent._hasEventMetadata
+ _OBJC_IVAR_$_TCSchemaTCClientEvent._hasLoadContext
+ _OBJC_IVAR_$_TCSchemaTCClientEvent._whichEvent_Type
+ _OBJC_IVAR_$_TCSchemaTCClientEventMetadata._hasTcId
+ _OBJC_IVAR_$_TCSchemaTCLoadContext._hasCanceled
+ _OBJC_IVAR_$_TCSchemaTCLoadContext._hasEnded
+ _OBJC_IVAR_$_TCSchemaTCLoadContext._hasFailed
+ _OBJC_IVAR_$_TCSchemaTCLoadContext._hasStartedOrChanged
+ _OBJC_IVAR_$_TCSchemaTCLoadContext._whichContextevent
+ _OBJC_METACLASS_$_CHSchemaCHAgenticGradingInferenceGenerated
+ _OBJC_METACLASS_$_CHSchemaCHGraderResult
+ _OBJC_METACLASS_$_CHSchemaCHSpeechCriterionResult
+ _OBJC_METACLASS_$_CHSchemaCHSpeechGradingInferenceMetadata
+ _OBJC_METACLASS_$_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ _OBJC_METACLASS_$_CPRSchemaCPRArchitectureUsed
+ _OBJC_METACLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ _OBJC_METACLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ _OBJC_METACLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ _OBJC_METACLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ _OBJC_METACLASS_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ _OBJC_METACLASS_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ _OBJC_METACLASS_$_LRSchemaLRRedactionExclusionSignal
+ _OBJC_METACLASS_$_ODDSiriSchemaODDLLMSiriTokenCounts
+ _OBJC_METACLASS_$_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ _OBJC_METACLASS_$_ORCHSchemaORCHSpeakerIdentificationSettled
+ _OBJC_METACLASS_$_PLANNERSchemaPLANNERUserIdentityChecked
+ _OBJC_METACLASS_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ _OBJC_METACLASS_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ _OBJC_METACLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ _OBJC_METACLASS_$_RISchemaRIClientEvent
+ _OBJC_METACLASS_$_RISchemaRIClientEventMetadata
+ _OBJC_METACLASS_$_RISchemaRIError
+ _OBJC_METACLASS_$_RISchemaRIRemoteContext
+ _OBJC_METACLASS_$_RISchemaRIRemoteEnded
+ _OBJC_METACLASS_$_RISchemaRIRemoteFailed
+ _OBJC_METACLASS_$_RISchemaRIRemoteStarted
+ _OBJC_METACLASS_$_RISchemaRISourceContext
+ _OBJC_METACLASS_$_RISchemaRISourceEnded
+ _OBJC_METACLASS_$_RISchemaRISourceFailed
+ _OBJC_METACLASS_$_RISchemaRISourceStarted
+ _OBJC_METACLASS_$_RISessionSchemaRISessionClientEvent
+ _OBJC_METACLASS_$_RISessionSchemaRISessionClientEventMetadata
+ _OBJC_METACLASS_$_RISessionSchemaRISessionError
+ _OBJC_METACLASS_$_RISessionSchemaRISessionRemoteContext
+ _OBJC_METACLASS_$_RISessionSchemaRISessionRemoteEnded
+ _OBJC_METACLASS_$_RISessionSchemaRISessionRemoteFailed
+ _OBJC_METACLASS_$_RISessionSchemaRISessionRemoteStarted
+ _OBJC_METACLASS_$_RISessionSchemaRISessionSourceContext
+ _OBJC_METACLASS_$_RISessionSchemaRISessionSourceEnded
+ _OBJC_METACLASS_$_RISessionSchemaRISessionSourceFailed
+ _OBJC_METACLASS_$_RISessionSchemaRISessionSourceStarted
+ _OBJC_METACLASS_$_SASchemaSARemoteSearchCanceled
+ _OBJC_METACLASS_$_SASchemaSARemoteSearchContext
+ _OBJC_METACLASS_$_SASchemaSARemoteSearchEnded
+ _OBJC_METACLASS_$_SASchemaSARemoteSearchFailed
+ _OBJC_METACLASS_$_SASchemaSARemoteSearchStarted
+ _OBJC_METACLASS_$_SISchemaUEICarPlayBannerPreprocessedTapped
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchCanceled
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchContext
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchEnded
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchFailed
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchStarted
+ _OBJC_METACLASS_$_SISchemaUEIResponseScrolled
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchCanceled
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchContext
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchEnded
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchFailed
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchResult
+ _OBJC_METACLASS_$_STSchemaSTHybridLocalSearchStarted
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchCanceled
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchContext
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchEnded
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchFailed
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchLatency
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchMergeCanceled
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchMergeContext
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchMergeEnded
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchMergeFailed
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchMergeResult
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchMergeStarted
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchResult
+ _OBJC_METACLASS_$_STSchemaSTMediaSearchStarted
+ _OBJC_METACLASS_$_TCSchemaTCClassifyCanceled
+ _OBJC_METACLASS_$_TCSchemaTCClassifyContext
+ _OBJC_METACLASS_$_TCSchemaTCClassifyEnded
+ _OBJC_METACLASS_$_TCSchemaTCClassifyFailed
+ _OBJC_METACLASS_$_TCSchemaTCClassifyStarted
+ _OBJC_METACLASS_$_TCSchemaTCClientEvent
+ _OBJC_METACLASS_$_TCSchemaTCClientEventMetadata
+ _OBJC_METACLASS_$_TCSchemaTCLoadCanceled
+ _OBJC_METACLASS_$_TCSchemaTCLoadContext
+ _OBJC_METACLASS_$_TCSchemaTCLoadEnded
+ _OBJC_METACLASS_$_TCSchemaTCLoadFailed
+ _OBJC_METACLASS_$_TCSchemaTCLoadStarted
+ __OBJC_$_CLASS_METHODS_RISchemaRIClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_$_CLASS_METHODS_RISessionSchemaRISessionClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_$_CLASS_METHODS_TCSchemaTCClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_$_INSTANCE_METHODS_CHSchemaCHAgenticGradingInferenceGenerated
+ __OBJC_$_INSTANCE_METHODS_CHSchemaCHGraderResult
+ __OBJC_$_INSTANCE_METHODS_CHSchemaCHSpeechCriterionResult
+ __OBJC_$_INSTANCE_METHODS_CHSchemaCHSpeechGradingInferenceMetadata
+ __OBJC_$_INSTANCE_METHODS_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ __OBJC_$_INSTANCE_METHODS_CPRSchemaCPRArchitectureUsed
+ __OBJC_$_INSTANCE_METHODS_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ __OBJC_$_INSTANCE_METHODS_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ __OBJC_$_INSTANCE_METHODS_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ __OBJC_$_INSTANCE_METHODS_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ __OBJC_$_INSTANCE_METHODS_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ __OBJC_$_INSTANCE_METHODS_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ __OBJC_$_INSTANCE_METHODS_LRSchemaLRRedactionExclusionSignal
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDLLMSiriTokenCounts
+ __OBJC_$_INSTANCE_METHODS_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ __OBJC_$_INSTANCE_METHODS_ORCHSchemaORCHSpeakerIdentificationSettled
+ __OBJC_$_INSTANCE_METHODS_PLANNERSchemaPLANNERUserIdentityChecked
+ __OBJC_$_INSTANCE_METHODS_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ __OBJC_$_INSTANCE_METHODS_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ __OBJC_$_INSTANCE_METHODS_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIClientEventMetadata
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIError
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIRemoteContext
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIRemoteEnded
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIRemoteFailed
+ __OBJC_$_INSTANCE_METHODS_RISchemaRIRemoteStarted
+ __OBJC_$_INSTANCE_METHODS_RISchemaRISourceContext
+ __OBJC_$_INSTANCE_METHODS_RISchemaRISourceEnded
+ __OBJC_$_INSTANCE_METHODS_RISchemaRISourceFailed
+ __OBJC_$_INSTANCE_METHODS_RISchemaRISourceStarted
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionClientEventMetadata
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionError
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionRemoteContext
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionRemoteEnded
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionRemoteFailed
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionRemoteStarted
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionSourceContext
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionSourceEnded
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionSourceFailed
+ __OBJC_$_INSTANCE_METHODS_RISessionSchemaRISessionSourceStarted
+ __OBJC_$_INSTANCE_METHODS_SASchemaSARemoteSearchCanceled
+ __OBJC_$_INSTANCE_METHODS_SASchemaSARemoteSearchContext
+ __OBJC_$_INSTANCE_METHODS_SASchemaSARemoteSearchEnded
+ __OBJC_$_INSTANCE_METHODS_SASchemaSARemoteSearchFailed
+ __OBJC_$_INSTANCE_METHODS_SASchemaSARemoteSearchStarted
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEICarPlayBannerPreprocessedTapped
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchContext
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseScrolled
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchCanceled
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchContext
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchEnded
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchFailed
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchResult
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTHybridLocalSearchStarted
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchCanceled
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchContext
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchEnded
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchFailed
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchLatency
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchMergeCanceled
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchMergeContext
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchMergeEnded
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchMergeFailed
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchMergeResult
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchMergeStarted
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchResult
+ __OBJC_$_INSTANCE_METHODS_STSchemaSTMediaSearchStarted
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClassifyCanceled
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClassifyContext
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClassifyEnded
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClassifyFailed
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClassifyStarted
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCClientEventMetadata
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCLoadCanceled
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCLoadContext
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCLoadEnded
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCLoadFailed
+ __OBJC_$_INSTANCE_METHODS_TCSchemaTCLoadStarted
+ __OBJC_$_INSTANCE_VARIABLES_CHSchemaCHAgenticGradingInferenceGenerated
+ __OBJC_$_INSTANCE_VARIABLES_CHSchemaCHGraderResult
+ __OBJC_$_INSTANCE_VARIABLES_CHSchemaCHSpeechCriterionResult
+ __OBJC_$_INSTANCE_VARIABLES_CHSchemaCHSpeechGradingInferenceMetadata
+ __OBJC_$_INSTANCE_VARIABLES_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ __OBJC_$_INSTANCE_VARIABLES_CPRSchemaCPRArchitectureUsed
+ __OBJC_$_INSTANCE_VARIABLES_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ __OBJC_$_INSTANCE_VARIABLES_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ __OBJC_$_INSTANCE_VARIABLES_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ __OBJC_$_INSTANCE_VARIABLES_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ __OBJC_$_INSTANCE_VARIABLES_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ __OBJC_$_INSTANCE_VARIABLES_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ __OBJC_$_INSTANCE_VARIABLES_LRSchemaLRRedactionExclusionSignal
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDLLMSiriTokenCounts
+ __OBJC_$_INSTANCE_VARIABLES_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ __OBJC_$_INSTANCE_VARIABLES_ORCHSchemaORCHSpeakerIdentificationSettled
+ __OBJC_$_INSTANCE_VARIABLES_PLANNERSchemaPLANNERUserIdentityChecked
+ __OBJC_$_INSTANCE_VARIABLES_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ __OBJC_$_INSTANCE_VARIABLES_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ __OBJC_$_INSTANCE_VARIABLES_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIClientEvent
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIClientEventMetadata
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIError
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIRemoteContext
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIRemoteEnded
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIRemoteFailed
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRIRemoteStarted
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRISourceContext
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRISourceEnded
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRISourceFailed
+ __OBJC_$_INSTANCE_VARIABLES_RISchemaRISourceStarted
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionClientEvent
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionClientEventMetadata
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionError
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionRemoteContext
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionRemoteEnded
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionRemoteFailed
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionRemoteStarted
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionSourceContext
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionSourceEnded
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionSourceFailed
+ __OBJC_$_INSTANCE_VARIABLES_RISessionSchemaRISessionSourceStarted
+ __OBJC_$_INSTANCE_VARIABLES_SASchemaSARemoteSearchCanceled
+ __OBJC_$_INSTANCE_VARIABLES_SASchemaSARemoteSearchContext
+ __OBJC_$_INSTANCE_VARIABLES_SASchemaSARemoteSearchEnded
+ __OBJC_$_INSTANCE_VARIABLES_SASchemaSARemoteSearchFailed
+ __OBJC_$_INSTANCE_VARIABLES_SASchemaSARemoteSearchStarted
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEICarPlayBannerPreprocessedTapped
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchContext
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseScrolled
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchCanceled
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchContext
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchEnded
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchFailed
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchResult
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTHybridLocalSearchStarted
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchCanceled
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchContext
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchEnded
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchFailed
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchLatency
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchMergeCanceled
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchMergeContext
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchMergeEnded
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchMergeFailed
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchMergeResult
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchMergeStarted
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchResult
+ __OBJC_$_INSTANCE_VARIABLES_STSchemaSTMediaSearchStarted
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClassifyCanceled
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClassifyContext
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClassifyEnded
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClassifyFailed
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClassifyStarted
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClientEvent
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCClientEventMetadata
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCLoadCanceled
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCLoadContext
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCLoadEnded
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCLoadFailed
+ __OBJC_$_INSTANCE_VARIABLES_TCSchemaTCLoadStarted
+ __OBJC_$_PROP_LIST_CHSchemaCHAgenticGradingInferenceGenerated
+ __OBJC_$_PROP_LIST_CHSchemaCHGraderResult
+ __OBJC_$_PROP_LIST_CHSchemaCHSpeechCriterionResult
+ __OBJC_$_PROP_LIST_CHSchemaCHSpeechGradingInferenceMetadata
+ __OBJC_$_PROP_LIST_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ __OBJC_$_PROP_LIST_CPRSchemaCPRArchitectureUsed
+ __OBJC_$_PROP_LIST_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ __OBJC_$_PROP_LIST_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ __OBJC_$_PROP_LIST_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ __OBJC_$_PROP_LIST_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ __OBJC_$_PROP_LIST_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ __OBJC_$_PROP_LIST_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ __OBJC_$_PROP_LIST_LRSchemaLRRedactionExclusionSignal
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDLLMSiriTokenCounts
+ __OBJC_$_PROP_LIST_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ __OBJC_$_PROP_LIST_ORCHSchemaORCHSpeakerIdentificationSettled
+ __OBJC_$_PROP_LIST_PLANNERSchemaPLANNERUserIdentityChecked
+ __OBJC_$_PROP_LIST_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ __OBJC_$_PROP_LIST_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ __OBJC_$_PROP_LIST_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ __OBJC_$_PROP_LIST_RISchemaRIClientEventMetadata
+ __OBJC_$_PROP_LIST_RISchemaRIError
+ __OBJC_$_PROP_LIST_RISchemaRIRemoteContext
+ __OBJC_$_PROP_LIST_RISchemaRIRemoteEnded
+ __OBJC_$_PROP_LIST_RISchemaRIRemoteFailed
+ __OBJC_$_PROP_LIST_RISchemaRIRemoteStarted
+ __OBJC_$_PROP_LIST_RISchemaRISourceContext
+ __OBJC_$_PROP_LIST_RISchemaRISourceEnded
+ __OBJC_$_PROP_LIST_RISchemaRISourceFailed
+ __OBJC_$_PROP_LIST_RISchemaRISourceStarted
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionClientEventMetadata
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionError
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionRemoteContext
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionRemoteEnded
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionRemoteFailed
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionRemoteStarted
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionSourceContext
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionSourceEnded
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionSourceFailed
+ __OBJC_$_PROP_LIST_RISessionSchemaRISessionSourceStarted
+ __OBJC_$_PROP_LIST_SASchemaSARemoteSearchCanceled
+ __OBJC_$_PROP_LIST_SASchemaSARemoteSearchContext
+ __OBJC_$_PROP_LIST_SASchemaSARemoteSearchEnded
+ __OBJC_$_PROP_LIST_SASchemaSARemoteSearchFailed
+ __OBJC_$_PROP_LIST_SASchemaSARemoteSearchStarted
+ __OBJC_$_PROP_LIST_SISchemaUEICarPlayBannerPreprocessedTapped
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchContext
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseScrolled
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchCanceled
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchContext
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchEnded
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchFailed
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchResult
+ __OBJC_$_PROP_LIST_STSchemaSTHybridLocalSearchStarted
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchCanceled
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchContext
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchEnded
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchFailed
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchLatency
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchMergeCanceled
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchMergeContext
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchMergeEnded
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchMergeFailed
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchMergeResult
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchMergeStarted
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchResult
+ __OBJC_$_PROP_LIST_STSchemaSTMediaSearchStarted
+ __OBJC_$_PROP_LIST_TCSchemaTCClassifyCanceled
+ __OBJC_$_PROP_LIST_TCSchemaTCClassifyContext
+ __OBJC_$_PROP_LIST_TCSchemaTCClassifyEnded
+ __OBJC_$_PROP_LIST_TCSchemaTCClassifyFailed
+ __OBJC_$_PROP_LIST_TCSchemaTCClassifyStarted
+ __OBJC_$_PROP_LIST_TCSchemaTCClientEventMetadata
+ __OBJC_$_PROP_LIST_TCSchemaTCLoadCanceled
+ __OBJC_$_PROP_LIST_TCSchemaTCLoadContext
+ __OBJC_$_PROP_LIST_TCSchemaTCLoadEnded
+ __OBJC_$_PROP_LIST_TCSchemaTCLoadFailed
+ __OBJC_$_PROP_LIST_TCSchemaTCLoadStarted
+ __OBJC_CLASS_PROTOCOLS_$_RISchemaRIClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_CLASS_PROTOCOLS_$_RISessionSchemaRISessionClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_CLASS_PROTOCOLS_$_TCSchemaTCClientEvent(InstrumentationAdditions|Component|InnerEventContainer)
+ __OBJC_CLASS_RO_$_CHSchemaCHAgenticGradingInferenceGenerated
+ __OBJC_CLASS_RO_$_CHSchemaCHGraderResult
+ __OBJC_CLASS_RO_$_CHSchemaCHSpeechCriterionResult
+ __OBJC_CLASS_RO_$_CHSchemaCHSpeechGradingInferenceMetadata
+ __OBJC_CLASS_RO_$_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ __OBJC_CLASS_RO_$_CPRSchemaCPRArchitectureUsed
+ __OBJC_CLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ __OBJC_CLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ __OBJC_CLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ __OBJC_CLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ __OBJC_CLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ __OBJC_CLASS_RO_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ __OBJC_CLASS_RO_$_LRSchemaLRRedactionExclusionSignal
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDLLMSiriTokenCounts
+ __OBJC_CLASS_RO_$_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ __OBJC_CLASS_RO_$_ORCHSchemaORCHSpeakerIdentificationSettled
+ __OBJC_CLASS_RO_$_PLANNERSchemaPLANNERUserIdentityChecked
+ __OBJC_CLASS_RO_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ __OBJC_CLASS_RO_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ __OBJC_CLASS_RO_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ __OBJC_CLASS_RO_$_RISchemaRIClientEvent
+ __OBJC_CLASS_RO_$_RISchemaRIClientEventMetadata
+ __OBJC_CLASS_RO_$_RISchemaRIError
+ __OBJC_CLASS_RO_$_RISchemaRIRemoteContext
+ __OBJC_CLASS_RO_$_RISchemaRIRemoteEnded
+ __OBJC_CLASS_RO_$_RISchemaRIRemoteFailed
+ __OBJC_CLASS_RO_$_RISchemaRIRemoteStarted
+ __OBJC_CLASS_RO_$_RISchemaRISourceContext
+ __OBJC_CLASS_RO_$_RISchemaRISourceEnded
+ __OBJC_CLASS_RO_$_RISchemaRISourceFailed
+ __OBJC_CLASS_RO_$_RISchemaRISourceStarted
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionClientEvent
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionClientEventMetadata
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionError
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionRemoteContext
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionRemoteEnded
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionRemoteFailed
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionRemoteStarted
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionSourceContext
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionSourceEnded
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionSourceFailed
+ __OBJC_CLASS_RO_$_RISessionSchemaRISessionSourceStarted
+ __OBJC_CLASS_RO_$_SASchemaSARemoteSearchCanceled
+ __OBJC_CLASS_RO_$_SASchemaSARemoteSearchContext
+ __OBJC_CLASS_RO_$_SASchemaSARemoteSearchEnded
+ __OBJC_CLASS_RO_$_SASchemaSARemoteSearchFailed
+ __OBJC_CLASS_RO_$_SASchemaSARemoteSearchStarted
+ __OBJC_CLASS_RO_$_SISchemaUEICarPlayBannerPreprocessedTapped
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchContext
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseScrolled
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchCanceled
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchContext
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchEnded
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchFailed
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchResult
+ __OBJC_CLASS_RO_$_STSchemaSTHybridLocalSearchStarted
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchCanceled
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchContext
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchEnded
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchFailed
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchLatency
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchMergeCanceled
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchMergeContext
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchMergeEnded
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchMergeFailed
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchMergeResult
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchMergeStarted
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchResult
+ __OBJC_CLASS_RO_$_STSchemaSTMediaSearchStarted
+ __OBJC_CLASS_RO_$_TCSchemaTCClassifyCanceled
+ __OBJC_CLASS_RO_$_TCSchemaTCClassifyContext
+ __OBJC_CLASS_RO_$_TCSchemaTCClassifyEnded
+ __OBJC_CLASS_RO_$_TCSchemaTCClassifyFailed
+ __OBJC_CLASS_RO_$_TCSchemaTCClassifyStarted
+ __OBJC_CLASS_RO_$_TCSchemaTCClientEvent
+ __OBJC_CLASS_RO_$_TCSchemaTCClientEventMetadata
+ __OBJC_CLASS_RO_$_TCSchemaTCLoadCanceled
+ __OBJC_CLASS_RO_$_TCSchemaTCLoadContext
+ __OBJC_CLASS_RO_$_TCSchemaTCLoadEnded
+ __OBJC_CLASS_RO_$_TCSchemaTCLoadFailed
+ __OBJC_CLASS_RO_$_TCSchemaTCLoadStarted
+ __OBJC_METACLASS_RO_$_CHSchemaCHAgenticGradingInferenceGenerated
+ __OBJC_METACLASS_RO_$_CHSchemaCHGraderResult
+ __OBJC_METACLASS_RO_$_CHSchemaCHSpeechCriterionResult
+ __OBJC_METACLASS_RO_$_CHSchemaCHSpeechGradingInferenceMetadata
+ __OBJC_METACLASS_RO_$_CPRSchemaCPRActiveRuntimeSwitchAttempted
+ __OBJC_METACLASS_RO_$_CPRSchemaCPRArchitectureUsed
+ __OBJC_METACLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallCanceled
+ __OBJC_METACLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallContext
+ __OBJC_METACLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallEnded
+ __OBJC_METACLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallFailed
+ __OBJC_METACLASS_RO_$_ExecutorSiriSchemaExecutorInjectableContentClassifierCallStarted
+ __OBJC_METACLASS_RO_$_IDENTITYSchemaIDENTITYSpeakerIdResultReceived
+ __OBJC_METACLASS_RO_$_LRSchemaLRRedactionExclusionSignal
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDLLMSiriTokenCounts
+ __OBJC_METACLASS_RO_$_ORCHSchemaORCHSpeakerIdentificationResultReceived
+ __OBJC_METACLASS_RO_$_ORCHSchemaORCHSpeakerIdentificationSettled
+ __OBJC_METACLASS_RO_$_PLANNERSchemaPLANNERUserIdentityChecked
+ __OBJC_METACLASS_RO_$_PLANNERSchemaPLANNERUserIdentityConfirmationRequested
+ __OBJC_METACLASS_RO_$_PLANNERSchemaPLANNERUserIdentityConfirmationResolved
+ __OBJC_METACLASS_RO_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ __OBJC_METACLASS_RO_$_RISchemaRIClientEvent
+ __OBJC_METACLASS_RO_$_RISchemaRIClientEventMetadata
+ __OBJC_METACLASS_RO_$_RISchemaRIError
+ __OBJC_METACLASS_RO_$_RISchemaRIRemoteContext
+ __OBJC_METACLASS_RO_$_RISchemaRIRemoteEnded
+ __OBJC_METACLASS_RO_$_RISchemaRIRemoteFailed
+ __OBJC_METACLASS_RO_$_RISchemaRIRemoteStarted
+ __OBJC_METACLASS_RO_$_RISchemaRISourceContext
+ __OBJC_METACLASS_RO_$_RISchemaRISourceEnded
+ __OBJC_METACLASS_RO_$_RISchemaRISourceFailed
+ __OBJC_METACLASS_RO_$_RISchemaRISourceStarted
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionClientEvent
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionClientEventMetadata
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionError
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionRemoteContext
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionRemoteEnded
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionRemoteFailed
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionRemoteStarted
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionSourceContext
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionSourceEnded
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionSourceFailed
+ __OBJC_METACLASS_RO_$_RISessionSchemaRISessionSourceStarted
+ __OBJC_METACLASS_RO_$_SASchemaSARemoteSearchCanceled
+ __OBJC_METACLASS_RO_$_SASchemaSARemoteSearchContext
+ __OBJC_METACLASS_RO_$_SASchemaSARemoteSearchEnded
+ __OBJC_METACLASS_RO_$_SASchemaSARemoteSearchFailed
+ __OBJC_METACLASS_RO_$_SASchemaSARemoteSearchStarted
+ __OBJC_METACLASS_RO_$_SISchemaUEICarPlayBannerPreprocessedTapped
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchContext
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseScrolled
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchCanceled
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchCascadeDomainMetrics
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchContext
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchEnded
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchFailed
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchResult
+ __OBJC_METACLASS_RO_$_STSchemaSTHybridLocalSearchStarted
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchCanceled
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchContext
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchEnded
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchFailed
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchLatency
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchMergeCanceled
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchMergeContext
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchMergeEnded
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchMergeFailed
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchMergeResult
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchMergeStarted
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchResult
+ __OBJC_METACLASS_RO_$_STSchemaSTMediaSearchStarted
+ __OBJC_METACLASS_RO_$_TCSchemaTCClassifyCanceled
+ __OBJC_METACLASS_RO_$_TCSchemaTCClassifyContext
+ __OBJC_METACLASS_RO_$_TCSchemaTCClassifyEnded
+ __OBJC_METACLASS_RO_$_TCSchemaTCClassifyFailed
+ __OBJC_METACLASS_RO_$_TCSchemaTCClassifyStarted
+ __OBJC_METACLASS_RO_$_TCSchemaTCClientEvent
+ __OBJC_METACLASS_RO_$_TCSchemaTCClientEventMetadata
+ __OBJC_METACLASS_RO_$_TCSchemaTCLoadCanceled
+ __OBJC_METACLASS_RO_$_TCSchemaTCLoadContext
+ __OBJC_METACLASS_RO_$_TCSchemaTCLoadEnded
+ __OBJC_METACLASS_RO_$_TCSchemaTCLoadFailed
+ __OBJC_METACLASS_RO_$_TCSchemaTCLoadStarted
+ ___swift_closure_destructor
+ ___swift_memcpy16_8
+ ___unnamed_12
+ ___unnamed_8
+ _swift_deallocObject
+ _swift_getFunctionTypeMetadata2
+ _swift_retain_x20
+ _symbolic $s19SiriInstrumentation21InjectableIdentifiersP
+ _symbolic B0
+ _symbolic SaySbx_xtc_SStGSg
+ _symbolic _____ 19SiriInstrumentation5GraphV13PreconditionsO
+ _symbolic _____ So013ODDSiriSchemaA19ExtensionPromptTypeV
+ _symbolic _____ So013ODDSiriSchemaA30ExtensionEventStreamResultTypeV
+ _symbolic _____ So015RISessionSchemaA17CommunicationTypeV
+ _symbolic _____ So018ExecutorSiriSchemaA34InjectableContentClassifierOutcomeV
+ _symbolic _____ So25NLXSchemaCDMRequesterFlowV
+ _symbolic _____ So25TCSchemaTCRoutingDecisionV
+ _symbolic _____ So26SISchemaUEIReachedLastLineV
+ _symbolic _____ So27CHSchemaCHAgenticGraderTypeV
+ _symbolic _____ So27CHSchemaCHSpeechCriterionIdV
+ _symbolic _____ So27CHSchemaCHSpeechGradingModeV
+ _symbolic _____ So27RISchemaRICommunicationTypeV
+ _symbolic _____ So27STSchemaSTMediaSearchDomainV
+ _symbolic _____ So30CHSchemaCHSpeechGradingVerdictV
+ _symbolic _____ So31CHSchemaCHSpeechNotJudgedReasonV
+ _symbolic _____ So31CHSchemaCHSpeechSampleAgreementV
+ _symbolic _____ So31ORCHSchemaORCHIdentityAggressorV
+ _symbolic _____ So31STSchemaSTMediaSearchResultTypeV
+ _symbolic _____ So32CHSchemaCHSpeechConfidenceBucketV
+ _symbolic _____ So32CHSchemaCHSpeechSelectionOutcomeV
+ _symbolic _____ So32CPRSchemaCPRRuntimeSwitchOutcomeV
+ _symbolic _____ So32ORCHSchemaORCHUserSelectionPhaseV
+ _symbolic _____ So32SASchemaSAMultiDeviceRoutingModeV
+ _symbolic _____ So33CHSchemaCHSpeechGradingErrorClassV
+ _symbolic _____ So33ODDSiriSchemaODDTokenBucketSchemeV
+ _symbolic _____ So33STSchemaSTHybridLocalSearchSourceV
+ _symbolic _____ So33STSchemaSTMediaSearchMergeOutcomeV
+ _symbolic _____ So34LRSchemaLRRedactionExclusionReasonV
+ _symbolic _____ So35CHSchemaCHSpeechGradingParseOutcomeV
+ _symbolic _____ So36PLANNERSchemaPLANNERUserIdentityGateV
+ _symbolic _____ So37ORCHSchemaORCHUserSelectionDropReasonV
+ _symbolic _____ So39STSchemaSTHybridLocalSearchMatchedFieldV
+ _symbolic _____ So40IDENTITYSchemaIDENTITYSpeakerIdMilestoneV
+ _symbolic _____ So40ORCHSchemaORCHUserSelectionFailureReasonV
+ _symbolic _____ So42ORCHSchemaORCHUserSelectionSettlementStateV
+ _symbolic _____ So42STSchemaSTHybridLocalSearchCascadeItemTypeV
+ _symbolic _____ So44PLANNERSchemaPLANNERUserIdentityCheckOutcomeV
+ _symbolic _____ So46PLANNERTOOLSSchemaPLANNERTOOLSEntityProvenanceV
+ _symbolic _____ So46STSchemaSTHybridLocalSearchStringMatchStrategyV
+ _symbolic _____ So51PLANNERSchemaPLANNERUserIdentityConfirmationOutcomeV
- ___unnamed_11
- ___unnamed_7
```
