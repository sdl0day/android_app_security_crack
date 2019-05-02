# 安卓应用的安全和破解

* [前言](README.md)
* [概述](intro/README.md)
* [安卓背景知识](android_background/README.md)
  * [安卓基本框架](android_background/android_framework.md)
  * [apk编译打包流程](android_background/apk_compile_process.md)
  * [破解apk的流程](android_background/crack_apk_process.md)
  * [相关知识](android_background/related_info/README.md)
    * [apk文件](android_background/related_info/apk_file.md)
    * [dex文件](android_background/related_info/dex_file.md)
    * [smali文件](android_background/related_info/smali_file.md)
* [安卓加密技术](android_safety_tech/README.md)
  * [为何要加密加固](android_safety_tech/why_encrypt_harden.md)
  * [加密技术历史](android_safety_tech/encrypt_history.md)
  * [加密方案概述](android_safety_tech/encrypt_overview/README.md)
    * [代码混淆](android_safety_tech/encrypt_overview/code_obfuscation.md)
    * [加固方案](android_safety_tech/encrypt_overview/harden_method/README.md)
      * [常见加固技术对比](android_safety_tech/encrypt_overview/harden_method/common_harden_compare.md)
      * [常见加固方案](android_safety_tech/encrypt_overview/harden_method/common_harden_method.md)
* [安卓破解技术](android_crack_tech/README.md)
  * [如何反混淆](android_crack_tech/how_deobfuscation.md)
  * [如何去壳脱壳](android_crack_tech/how_remove_shell_unpacking.md)
  * [如何从apk破解出java源码](android_crack_tech/how_apk_to_java_src/README.md)
    * [破解apk概述](android_crack_tech/how_apk_to_java_src/crack_apk_intro.md)
    * [一步: apk->java](android_crack_tech/how_apk_to_java_src/1_step_apk_to_java.md)
    * [三步: app->dex->jar->java](android_crack_tech/how_apk_to_java_src/3_steps/README.md)
      * [1. app导出dex](android_crack_tech/how_apk_to_java_src/3_steps/1_app_dump_dex.md)
      * [2. dex转换出jar](android_crack_tech/how_apk_to_java_src/3_steps/2_dex_to_jar.md)
      * [3. jar转换出java](android_crack_tech/how_apk_to_java_src/3_steps/3_jar_to_java.md)
* [常见安卓破解工具](android_crack_tool/README.md)
  * [从app导出dex](android_crack_tool/app_to_dex/README.md)
    * [FDex2](android_crack_tool/app_to_dex/fdex2.md)
    * [DumpDex](android_crack_tool/app_to_dex/dumpdex.md)
    * [drizzleDumper](android_crack_tool/app_to_dex/drizzledumper.md)
    * [DexExtractor](android_crack_tool/app_to_dex/dexextractor.md)
    * [InDroid](android_crack_tool/app_to_dex/indroid.md)
  * [dex转jar](android_crack_tool/dex_to_jar/README.md)
    * [dex2jar](android_crack_tool/dex_to_jar/dex2jar.md)
    * [Enjarify](android_crack_tool/dex_to_jar/enjarify.md)
    * [Dedexer](android_crack_tool/dex_to_jar/dedexer.md)
  * [反编译器](android_crack_tool/decompiler/README.md)
    * [常见反编译器对比](android_crack_tool/decompiler/common_decompiler_compare.md)
    * [常见反编译器](android_crack_tool/decompiler/common_decompilers/README.md)
      * [jadx](android_crack_tool/decompiler/common_decompilers/jadx.md)
      * [CFR](android_crack_tool/decompiler/common_decompilers/cfr.md)
      * [JD-GUI](android_crack_tool/decompiler/common_decompilers/jd_gui.md)
      * [Procyon](android_crack_tool/decompiler/common_decompilers/procyon/README.md)
        * [Luyten](android_crack_tool/decompiler/common_decompilers/procyon/luyten.md)
      * [Krakatau](android_crack_tool/decompiler/common_decompilers/krakatau.md)
      * [Fernflower](android_crack_tool/decompiler/common_decompilers/fernflower.md)
      * [GDA](android_crack_tool/decompiler/common_decompilers/gda.md)
      * [Dare](android_crack_tool/decompiler/common_decompilers/dare.md)
      * [JAD](android_crack_tool/decompiler/common_decompilers/jad.md)
  * [其他破解类工具](android_crack_tool/other_crack_tool/README.md)
    * [apktool](android_crack_tool/other_crack_tool/apktool.md)
    * [smali/baksmali](android_crack_tool/other_crack_tool/smali_baksmali.md)
    * [IDA](android_crack_tool/other_crack_tool/ida.md)
    * [radare2](android_crack_tool/other_crack_tool/radare2.md)
    * [安卓XML破解](android_crack_tool/other_crack_tool/xml_crack/README.md)
      * [AXMLPrinter2](android_crack_tool/other_crack_tool/xml_crack/axmlprinter2.md)
  * [其他辅助类工具](android_crack_tool/other_assistant_tool/README.md)
    * [安卓调试器](android_crack_tool/other_assistant_tool/android_debugger/README.md)
      * [AndBug](android_crack_tool/other_assistant_tool/android_debugger/andbug.md)
      * [Android-OpenDebug](android_crack_tool/other_assistant_tool/android_debugger/android_opendebug.md)
    * [二进制编辑器](android_crack_tool/other_assistant_tool/binary_editor/README.md)
      * [010editor](android_crack_tool/other_assistant_tool/binary_editor/010editor.md)
      * [EverEdit](android_crack_tool/other_assistant_tool/binary_editor/everedit.md)
    * [ClassyShark](android_crack_tool/other_assistant_tool/classshark.md)
    * [APK Analyzer](android_crack_tool/other_assistant_tool/apk_analyzer.md)
    * [Fino](android_crack_tool/other_assistant_tool/fino.md)
    * [Introspy-Android](android_crack_tool/other_assistant_tool/introspy_android.md)
    * [redexer](android_crack_tool/other_assistant_tool/redexer.md)
    * [SmaliViewer](android_crack_tool/other_assistant_tool/smaliviewer.md)
  * [其他综合类工具](android_crack_tool/other_integrated_tool/README.md)
    * [ByteCode Viewer](android_crack_tool/other_integrated_tool/bytecode_viewer.md)
    * [Android Decompiler](android_crack_tool/other_integrated_tool/android_decompiler.md)
    * [decompile-apk](android_crack_tool/other_integrated_tool/decompile_apk.md)
    * [Android-Crack-Tool For Mac](android_crack_tool/other_integrated_tool/crack_tool_mac.md)
    * [Android逆向助手](android_crack_tool/other_integrated_tool/dayanzai_android_hack.md)
    * [AndroidKiller](android_crack_tool/other_integrated_tool/dayanzai_android_killer.md)
    * [Androguard](android_crack_tool/other_integrated_tool/androguard.md)
    * [AFE](android_crack_tool/other_integrated_tool/appknox_afe.md)
  * [其他相关工具](android_crack_tool/other_related_tool/README.md)
    * [安卓Hook框架](android_crack_tool/other_related_tool/android_hook_framework/README.md)
      * [XPosed框架](android_crack_tool/other_related_tool/android_hook_framework/xposed_framework.md)
      * [Cydia Substrate](android_crack_tool/other_related_tool/android_hook_framework/cydia_substrate.md)
      * [frida](android_crack_tool/other_related_tool/android_hook_framework/frida.md)
    * [安卓模拟器](android_crack_tool/other_related_tool/android_emulator/README.md)
      * [夜神安卓模拟器](android_crack_tool/other_related_tool/android_emulator/nox.md)
    * [文件浏览器](android_crack_tool/other_related_tool/file_browser.md)
* [附录](appendix/README.md)
  * [参考资料](appendix/reference.md)