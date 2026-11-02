## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

```diff

-980.77.1.2.0
-  __TEXT.__text: 0xb67ec
-  __TEXT.__objc_methlist: 0x1cec
-  __TEXT.__const: 0x664
-  __TEXT.__gcc_except_tab: 0xa1c
-  __TEXT.__cstring: 0x30a15
+1005.13.1.1.0
+  __TEXT.__text: 0xb72cc
+  __TEXT.__objc_methlist: 0x1d64
+  __TEXT.__const: 0x674
+  __TEXT.__gcc_except_tab: 0xa10
+  __TEXT.__cstring: 0x30ec3
   __TEXT.__dlopen_cstrs: 0x1f3
   __TEXT.__oslogstring: 0x31c
-  __TEXT.__unwind_info: 0x2d60
+  __TEXT.__unwind_info: 0x2d50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3e08
+  __DATA_CONST.__const: 0x3e28
   __DATA_CONST.__objc_classlist: 0x68
-  __DATA_CONST.__objc_catlist: 0x8
+  __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b98
+  __DATA_CONST.__objc_selrefs: 0x1bf8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x400
-  __AUTH_CONST.__const: 0x2dd8
-  __AUTH_CONST.__cfstring: 0x6600
-  __AUTH_CONST.__objc_const: 0x2498
+  __AUTH_CONST.__const: 0x2d78
+  __AUTH_CONST.__cfstring: 0x6680
+  __AUTH_CONST.__objc_const: 0x2518
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x140
   __AUTH.__data: 0x2c0
   __DATA.__objc_ivar: 0x18c
-  __DATA.__data: 0x14a0
-  __DATA.__bss: 0x130
+  __DATA.__data: 0x1430
+  __DATA.__bss: 0x120
   __DATA_DIRTY.__objc_data: 0x2d0
   __DATA_DIRTY.__data: 0xcb0
   __DATA_DIRTY.__bss: 0x2c8

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5367
-  Symbols:   4406
+  Functions: 5366
+  Symbols:   4425
   CStrings:  0
 
Symbols:
+ -[WiFiAwareDatapathInfo(APTNANDataSession) peerSignalStrength]
+ GCC_except_table29
+ GCC_except_table45
+ GCC_except_table63
+ GCC_except_table69
+ GCC_except_table70
+ GCC_except_table8
+ _APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix
+ _APBrowserSetAirPlayInfo
+ _APSIsHomeAccessory
+ _APSIsHomeTheaterSurroundEnabled
+ _APSSignalStrengthDBmFromScaled
+ _APSSurroundToOdeonFallbackEnabled
+ _APTDiagnosticSendStreamInfo
+ _APTNANDataSessionGetDatapathRSSI
+ _APTransportConnectionCopyProperty
+ _APTransportConnectionGetDSCPForSocketQoS
+ _APTransportConnectionQoSFromSocketQoS
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _APTransportSocketQoSFromConnectionQoS
+ _APTransportTrafficCapturePrepareForCollection
+ _APTransportTrafficCaptureWriteUDPMessage
+ _CFURLCreateFromFileSystemRepresentation
+ _FigCFSetContainsValue
+ _FigCFSetGetCount
+ _FigFileMarkPurgeable
+ _OUTLINED_FUNCTION_61
+ _OUTLINED_FUNCTION_62
+ _OUTLINED_FUNCTION_63
+ _OUTLINED_FUNCTION_64
+ _OUTLINED_FUNCTION_65
+ _OUTLINED_FUNCTION_66
+ __APTNANDataSessionCopyDatapathIDAndPeerMAC
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_WiFiAwareDatapathInfo_$_APTNANDataSession
+ __OBJC_$_CATEGORY_WiFiAwareDatapathInfo_$_APTNANDataSession
+ ___62-[WiFiAwareDatapathInfo(APTNANDataSession) peerSignalStrength]_block_invoke
+ ___APBrowserSetAirPlayInfo_block_invoke
+ ___APTransportTrafficCapturePrepareForCollection_block_invoke
+ ___APTransportTrafficCaptureWriteUDPMessage_block_invoke
+ ___block_descriptor_48_e8_32o40o_e44_v16?0"WiFiAwareDatapathPerformanceReport"8ls32l8s40l8
+ ___strlcpy_chk
+ _nw_content_context_set_metadata_for_protocol
+ _nw_ip_create_metadata
+ _nw_ip_metadata_set_dscp_value
+ _unbufnwGuts_setQualityOfServiceInternal
- GCC_except_table26
- GCC_except_table31
- GCC_except_table34
- GCC_except_table61
- GCC_except_table62
- GCC_except_table67
- GCC_except_table68
- _APTDiagnosticMulticastDataToAllHosts
- _APTPacingControllerReset
- _APTransportTrafficCaptureFlushForSysdiagnose
- _APTransportTrafficCaptureWriteMulticastMessage
- _APTransportWifiManagerClientCreate
- _APTransportWifiManagerClientRegister
- _APTransportWifiManagerClientUnregister
- _CMBaseObjectCopyProperty
- __APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix
- ___APTransportTrafficCaptureFlushForSysdiagnose_block_invoke
- ___APTransportTrafficCaptureWriteMulticastMessage_block_invoke
- ___APTransportWifiManagerClientRegister_block_invoke
- ___APTransportWifiManagerClientUnregister_block_invoke
- _gLogCategory_APTransportWifiManagerClient
- _kAPTransportProperty_WifiManagerClient
- _kAPTransportWifiManagerClientClass
- _session_performWifiManagerRegistration
- _wifiManagerClient_Finalize
- _wifiManagerClient_getTypeID
```
