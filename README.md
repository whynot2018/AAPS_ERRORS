# AAPS_ERRORS


/*************-**************************************/
AndroidAPS$ ./gradlew app:assembleRelease
Starting a Gradle Daemon (subsequent builds will be faster)

> Configure project :app
--------------
isMaster: true
allCommited: true
--------------
Download https://github.com/MilosKozak/danars-support-lib/archive/master.zip

> Task :app:compileFullReleaseAidl
aidl E 01-05 21:11:05 15208 15208 aidl.cpp:581] refusing to generate code from aidl file defining parcelable


> Task :app:processFullReleaseGoogleServices
Parsing json file: /home/whynot/StudioProjects/AndroidAPS/app/google-services.json

> Task :wear:compileFullReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :app:processFullReleaseManifest
/home/whynot/StudioProjects/AndroidAPS/app/src/main/AndroidManifest.xml:24:9-31:50 Warning:
        activity#com.google.firebase.auth.internal.FederatedSignInActivity@android:launchMode was tagged at AndroidManifest.xml:24 to replace other declarations but no other declaration present
/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeFullReleaseResources/merged.dir/values-cs-rCZ/values-cs-rCZ.xml:1237: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeFullReleaseResources/merged.dir/values-ko-rKR/values-ko-rKR.xml:775: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeFullReleaseResources/merged.dir/values-sk-rSK/values-sk-rSK.xml:1238: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.


> Task :app:compileFullReleaseKotlin
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (7, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (99, 60): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (3, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (114, 60): 'PreferenceFragment' is deprecated. Deprecated in Java

> Task :app:compileFullReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.

> Task :app:compileNsclient2ReleaseAidl
aidl E 01-05 21:14:30 15485 15485 aidl.cpp:581] refusing to generate code from aidl file defining parcelable


> Task :app:processNsclient2ReleaseGoogleServices
Parsing json file: /home/whynot/StudioProjects/AndroidAPS/app/google-services.json

> Task :app:compileNsclientReleaseAidl
aidl E 01-05 21:14:37 15522 15522 aidl.cpp:581] refusing to generate code from aidl file defining parcelable


> Task :app:stripFullReleaseDebugSymbols
WARNING: Compatible side by side NDK version was not found. Default is 20.0.5594570.
Compatible side by side NDK version was not found. Default is 20.0.5594570.
Unable to strip the following libraries, packaging them as they are: libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libtool-checker.so, libtool-checker.so, libtool-checker.so, libtool-checker.so.

> Task :app:processNsclientReleaseGoogleServices
Parsing json file: /home/whynot/StudioProjects/AndroidAPS/app/google-services.json

> Task :app:stripNsclient2ReleaseDebugSymbols
Unable to strip the following libraries, packaging them as they are: libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libtool-checker.so, libtool-checker.so, libtool-checker.so, libtool-checker.so.

> Task :wear:compileNsclient2ReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :wear:compileNsclientReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :app:processNsclient2ReleaseManifest
/home/whynot/StudioProjects/AndroidAPS/app/src/main/AndroidManifest.xml:24:9-31:50 Warning:
        activity#com.google.firebase.auth.internal.FederatedSignInActivity@android:launchMode was tagged at AndroidManifest.xml:24 to replace other declarations but no other declaration present
/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeNsclient2ReleaseResources/merged.dir/values-sk-rSK/values-sk-rSK.xml:1238: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.


> Task :app:stripNsclientReleaseDebugSymbols
Unable to strip the following libraries, packaging them as they are: libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libtool-checker.so, libtool-checker.so, libtool-checker.so, libtool-checker.so.
/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeNsclient2ReleaseResources/merged.dir/values-cs-rCZ/values-cs-rCZ.xml:1237: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeNsclient2ReleaseResources/merged.dir/values-ko-rKR/values-ko-rKR.xml:775: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.


> Task :app:compilePumpcontrolReleaseAidl
aidl E 01-05 21:15:03 15581 15581 aidl.cpp:581] refusing to generate code from aidl file defining parcelable


> Task :app:processPumpcontrolReleaseGoogleServices
Parsing json file: /home/whynot/StudioProjects/AndroidAPS/app/google-services.json

> Task :app:compileNsclient2ReleaseKotlin
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (7, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (99, 60): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (3, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (114, 60): 'PreferenceFragment' is deprecated. Deprecated in Java

> Task :app:compileNsclient2ReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.

> Task :app:processNsclientReleaseManifest
/home/whynot/StudioProjects/AndroidAPS/app/src/main/AndroidManifest.xml:24:9-31:50 Warning:
        activity#com.google.firebase.auth.internal.FederatedSignInActivity@android:launchMode was tagged at AndroidManifest.xml:24 to replace other declarations but no other declaration present
/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeNsclientReleaseResources/merged.dir/values-cs-rCZ/values-cs-rCZ.xml:1237: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeNsclientReleaseResources/merged.dir/values-ko-rKR/values-ko-rKR.xml:775: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergeNsclientReleaseResources/merged.dir/values-sk-rSK/values-sk-rSK.xml:1238: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.


> Task :app:compileNsclientReleaseKotlin
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (7, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (99, 60): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (3, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (114, 60): 'PreferenceFragment' is deprecated. Deprecated in Java

> Task :wear:compilePumpcontrolReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

> Task :app:stripPumpcontrolReleaseDebugSymbols
Unable to strip the following libraries, packaging them as they are: libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libBleCommandUtil.so, libtool-checker.so, libtool-checker.so, libtool-checker.so, libtool-checker.so.

> Task :app:processPumpcontrolReleaseManifest
/home/whynot/StudioProjects/AndroidAPS/app/src/main/AndroidManifest.xml:24:9-31:50 Warning:
        activity#com.google.firebase.auth.internal.FederatedSignInActivity@android:launchMode was tagged at AndroidManifest.xml:24 to replace other declarations but no other declaration present
/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergePumpcontrolReleaseResources/merged.dir/values-sk-rSK/values-sk-rSK.xml:1238: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergePumpcontrolReleaseResources/merged.dir/values-cs-rCZ/values-cs-rCZ.xml:1237: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.

/home/whynot/StudioProjects/AndroidAPS/app/build/intermediates/incremental/mergePumpcontrolReleaseResources/merged.dir/values-ko-rKR/values-ko-rKR.xml:775: warn: multiple substitutions specified in non-positional format; did you mean to add the formatted="false" attribute?.


> Task :app:compileNsclientReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.

> Task :app:compilePumpcontrolReleaseKotlin
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (7, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/smsCommunicator/SmsCommunicatorPlugin.kt: (99, 60): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (3, 27): 'PreferenceFragment' is deprecated. Deprecated in Java
w: /home/whynot/StudioProjects/AndroidAPS/app/src/main/java/info/nightscout/androidaps/plugins/general/tidepool/TidepoolPlugin.kt: (114, 60): 'PreferenceFragment' is deprecated. Deprecated in Java

> Task :app:compilePumpcontrolReleaseJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.

Deprecated Gradle features were used in this build, making it incompatible with Gradle 6.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/5.6.4/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 7m 57s
207 actionable tasks: 205 executed, 2 up-to-date

/*************-**************************************/
