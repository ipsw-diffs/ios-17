## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

```diff

-541.18.0.1.0
-  __TEXT.__text: 0x431a14
+541.18.2.0.0
+  __TEXT.__text: 0x431b64
   __TEXT.__stubs: 0x24fc
-  __TEXT.__objc_methlist: 0x39100
+  __TEXT.__objc_methlist: 0x39108
   __TEXT.__const: 0x4bb4
   __TEXT.__cstring: 0x57782
-  __TEXT.__oslogstring: 0x39057
+  __TEXT.__oslogstring: 0x390c3
   __TEXT.__gcc_except_tab: 0xcddc
   __TEXT.__dlopen_cstrs: 0x1d2
   __TEXT.__ustring: 0x4

   __TEXT.__swift5_protos: 0x1c
   __TEXT.__swift5_builtin: 0x64
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0xe51c
+  __TEXT.__unwind_info: 0xe520
   __TEXT.__eh_frame: 0x19c0
   __TEXT.__objc_classname: 0x8eb6
-  __TEXT.__objc_methname: 0xaf24d
+  __TEXT.__objc_methname: 0xaf273
   __TEXT.__objc_methtype: 0x19aa4
-  __TEXT.__objc_stubs: 0x4e280
-  __DATA_CONST.__got: 0x2488
+  __TEXT.__objc_stubs: 0x4e2a0
+  __DATA_CONST.__got: 0x2490
   __DATA_CONST.__const: 0x13088
   __DATA_CONST.__cfstring: 0x3b140
   __DATA_CONST.__objc_classlist: 0x1fb0

   __DATA_CONST.__objc_protolist: 0x4d8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_const: 0x89a60
-  __DATA_CONST.__objc_selrefs: 0x1c6e8
+  __DATA_CONST.__objc_selrefs: 0x1c6f0
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_classrefs: 0x2cb8
   __DATA_CONST.__objc_superrefs: 0x15e0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 26540
-  Symbols:   47566
-  CStrings:  33860
+  Functions: 26541
+  Symbols:   47570
+  CStrings:  33862
 
Symbols:
+ -[ATXNotificationAndSuggestionDatabase _purgeNotificationBiomeStreamsIfNeeded]
+ GCC_except_table161
+ GCC_except_table166
+ GCC_except_table76
+ __kATXBiomeNotificationPurgeCompleteKey
+ _objc_msgSend$_purgeNotificationBiomeStreamsIfNeeded
- GCC_except_table160
- GCC_except_table165
Functions:
~ -[ATXNotificationAndSuggestionDatabase init] : 116 -> 124
+ -[ATXNotificationAndSuggestionDatabase _purgeNotificationBiomeStreamsIfNeeded]
~ -[ATXNotificationsLoggingServer logNotificationEvent:notification:reason:] : 1156 -> 1228
CStrings:
+ "ATXNotificationAndSuggestionDatabase: Purging private notification streams to remove persisted text content"
+ "_purgeNotificationBiomeStreamsIfNeeded"
```
