[15:53:33] [main/INFO]: Loading Minecraft 1.18.1 with Fabric Loader 0.12.12
[15:53:34] [main/WARN]: Warnings were found!
 - Mod 'Fabric Rendering Fluids (v1)' (fabric-rendering-fluids-v1) 0.1.13+a02b446313 recommends any version of fabric-textures-v0, which is missing!
	 - You should install any version of fabric-textures-v0 for the optimal experience.
[15:53:34] [main/INFO]: Loading 9 mods:
	- fabric-api-base 0.3.0+a02b446313 via sodium
	- fabric-rendering-data-attachment-v1 0.1.5+a02b446313 via sodium
	- fabric-rendering-fluids-v1 0.1.13+a02b446313 via sodium
	- fabric-resource-loader-v0 0.4.7+b7ab612113 via sodium
	- fabricloader 0.12.12
	- java 17
	- minecraft 1.18.1
	- org_joml_joml 1.10.2 via sodium
	- sodium 0.3.4+build.13
[15:53:34] [main/INFO]: SpongePowered MIXIN Subsystem Version=0.8.4 Source=file:/C:/Users/DELL/AppData/Roaming/.minecraft/libraries/net/fabricmc/sponge-mixin/0.10.7+mixin.0.8.4/sponge-mixin-0.10.7+mixin.0.8.4.jar Service=Knot/Fabric Env=CLIENT
[15:53:34] [main/INFO]: Compatibility level set to JAVA_16
[15:53:34] [main/INFO]: Loaded configuration file for Sodium: 29 options available, 0 override(s) found
[15:53:34] [main/WARN]: Error loading class: net/minecraft/util/CubicSampler$class_4859 (java.lang.ClassNotFoundException: net/minecraft/util/CubicSampler$class_4859)
[15:53:34] [main/WARN]: Error loading class: net/minecraft/util/CubicSampler$class_4859 (java.lang.ClassNotFoundException: net/minecraft/util/CubicSampler$class_4859)
[15:53:34] [main/INFO]: Trying to switch memory allocators to work around memory leaks present with Jemalloc 5.0.0 through 5.2.0 on Windows
[15:53:46] [Render thread/WARN]: Error loading class: net/minecraft/util/CubicSampler$class_4859 (java.lang.ClassNotFoundException: net/minecraft/util/CubicSampler$class_4859)
[15:53:46] [Render thread/ERROR]: Mixin apply for mod sodium failed sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> net.minecraft.class_638: org.spongepowered.asm.mixin.transformer.throwables.InvalidMixinException Unexpecteded ClassMetadataNotFoundException whilst transforming the mixin class: [MAIN Applicator Phase -> sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> Apply Methods -> (Lnet/minecraft/class_243;Lnet/minecraft/util/CubicSampler$class_4859;)Lnet/minecraft/class_243;:redirect$zbj000$redirectSampleColor -> Transform LVT -> var=rgbFetcher -> desc=Lnet/minecraft/util/CubicSampler$class_4859;]
org.spongepowered.asm.mixin.transformer.throwables.InvalidMixinException: Unexpecteded ClassMetadataNotFoundException whilst transforming the mixin class: [MAIN Applicator Phase -> sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> Apply Methods -> (Lnet/minecraft/class_243;Lnet/minecraft/util/CubicSampler$class_4859;)Lnet/minecraft/class_243;:redirect$zbj000$redirectSampleColor -> Transform LVT -> var=rgbFetcher -> desc=Lnet/minecraft/util/CubicSampler$class_4859;]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformMethod(MixinTargetContext.java:510) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyNormalMethod(MixinApplicatorStandard.java:533) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMethods(MixinApplicatorStandard.java:519) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMixin(MixinApplicatorStandard.java:386) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.apply(MixinApplicatorStandard.java:325) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.apply(TargetClassContext.java:421) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.applyMixins(TargetClassContext.java:403) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:363) [sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234) [sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202) [sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:247) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) [fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) [?:?]
	at net.minecraft.client.main.Main.main(Main.java:199) [client-intermediary.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:77) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23) [fabric-loader-0.12.12.jar:?]
Caused by: org.spongepowered.asm.mixin.throwables.ClassMetadataNotFoundException: net.minecraft.util.CubicSampler$class_4859
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformSingleDescriptor(MixinTargetContext.java:1002) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformSingleDescriptor(MixinTargetContext.java:962) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformLVT(MixinTargetContext.java:563) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformMethod(MixinTargetContext.java:469) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	... 21 more
[15:53:47] [Render thread/INFO]: Failed to find module info for C:\Users\DELL\AppData\Roaming\.minecraft\bin\ec22-ea68-adb0-72cf\lwjgl.dll
com.sun.jna.platform.win32.Win32Exception: The specified resource type cannot be found in the image file.
	at net.minecraft.class_6498.method_37964(class_6498.java:62) ~[client-intermediary.jar:?]
	at net.minecraft.class_6498.method_37961(class_6498.java:48) ~[client-intermediary.jar:?]
	at net.minecraft.class_6498.method_37968(class_6498.java:132) ~[client-intermediary.jar:?]
	at net.minecraft.class_129.method_577(class_129.java:84) [client-intermediary.jar:?]
	at net.minecraft.class_6498.method_37966(class_6498.java:131) [client-intermediary.jar:?]
	at net.minecraft.client.main.Main.main(Main.java:207) [client-intermediary.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:77) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23) [fabric-loader-0.12.12.jar:?]
[15:53:47] [Render thread/WARN]: Error loading class: net/minecraft/util/CubicSampler$class_4859 (java.lang.ClassNotFoundException: net/minecraft/util/CubicSampler$class_4859)
[15:53:47] [Render thread/ERROR]: Mixin apply for mod sodium failed sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> net.minecraft.class_638: org.spongepowered.asm.mixin.transformer.throwables.InvalidMixinException Unexpecteded ClassMetadataNotFoundException whilst transforming the mixin class: [MAIN Applicator Phase -> sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> Apply Methods -> (Lnet/minecraft/class_243;Lnet/minecraft/util/CubicSampler$class_4859;)Lnet/minecraft/class_243;:redirect$zbj000$redirectSampleColor -> Transform LVT -> var=rgbFetcher -> desc=Lnet/minecraft/util/CubicSampler$class_4859;]
org.spongepowered.asm.mixin.transformer.throwables.InvalidMixinException: Unexpecteded ClassMetadataNotFoundException whilst transforming the mixin class: [MAIN Applicator Phase -> sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> Apply Methods -> (Lnet/minecraft/class_243;Lnet/minecraft/util/CubicSampler$class_4859;)Lnet/minecraft/class_243;:redirect$zbj000$redirectSampleColor -> Transform LVT -> var=rgbFetcher -> desc=Lnet/minecraft/util/CubicSampler$class_4859;]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformMethod(MixinTargetContext.java:510) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyNormalMethod(MixinApplicatorStandard.java:533) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMethods(MixinApplicatorStandard.java:519) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMixin(MixinApplicatorStandard.java:386) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.apply(MixinApplicatorStandard.java:325) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.apply(TargetClassContext.java:421) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.applyMixins(TargetClassContext.java:403) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:363) [sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234) [sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202) [sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:247) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) [fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) [?:?]
	at net.minecraft.client.main.Main.main(Main.java:208) [client-intermediary.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:77) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23) [fabric-loader-0.12.12.jar:?]
Caused by: org.spongepowered.asm.mixin.throwables.ClassMetadataNotFoundException: net.minecraft.util.CubicSampler$class_4859
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformSingleDescriptor(MixinTargetContext.java:1002) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformSingleDescriptor(MixinTargetContext.java:962) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformLVT(MixinTargetContext.java:563) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformMethod(MixinTargetContext.java:469) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	... 21 more
[15:53:47] [Render thread/ERROR]: Minecraft has crashed!
net.fabricmc.loader.impl.FormattedException: java.lang.RuntimeException: Mixin transformation of net.minecraft.class_638 failed
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:610) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:77) [fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23) [fabric-loader-0.12.12.jar:?]
Caused by: java.lang.RuntimeException: Mixin transformation of net.minecraft.class_638 failed
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:252) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) ~[fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) ~[?:?]
	at net.minecraft.client.main.Main.main(Main.java:208) ~[fabric-loader-0.12.12-1.18.1.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) ~[fabric-loader-0.12.12.jar:?]
	... 2 more
Caused by: org.spongepowered.asm.mixin.transformer.throwables.MixinTransformerError: An unexpected critical error was encountered
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:392) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:247) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) ~[fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) ~[?:?]
	at net.minecraft.client.main.Main.main(Main.java:208) ~[fabric-loader-0.12.12-1.18.1.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) ~[fabric-loader-0.12.12.jar:?]
	... 2 more
Caused by: org.spongepowered.asm.mixin.throwables.MixinApplyError: Mixin [sodium.mixins.json:features.fast_biome_colors.MixinClientWorld] from phase [DEFAULT] in config [sodium.mixins.json] from mod [sodium] FAILED during APPLY
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.handleMixinError(MixinProcessor.java:638) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.handleMixinApplyError(MixinProcessor.java:589) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:379) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:247) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) ~[fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) ~[?:?]
	at net.minecraft.client.main.Main.main(Main.java:208) ~[fabric-loader-0.12.12-1.18.1.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) ~[fabric-loader-0.12.12.jar:?]
	... 2 more
Caused by: org.spongepowered.asm.mixin.transformer.throwables.InvalidMixinException: Unexpecteded ClassMetadataNotFoundException whilst transforming the mixin class: [MAIN Applicator Phase -> sodium.mixins.json:features.fast_biome_colors.MixinClientWorld -> Apply Methods -> (Lnet/minecraft/class_243;Lnet/minecraft/util/CubicSampler$class_4859;)Lnet/minecraft/class_243;:redirect$zbj000$redirectSampleColor -> Transform LVT -> var=rgbFetcher -> desc=Lnet/minecraft/util/CubicSampler$class_4859;]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformMethod(MixinTargetContext.java:510) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyNormalMethod(MixinApplicatorStandard.java:533) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMethods(MixinApplicatorStandard.java:519) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMixin(MixinApplicatorStandard.java:386) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.apply(MixinApplicatorStandard.java:325) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.apply(TargetClassContext.java:421) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.applyMixins(TargetClassContext.java:403) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:363) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:247) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) ~[fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) ~[?:?]
	at net.minecraft.client.main.Main.main(Main.java:208) ~[fabric-loader-0.12.12-1.18.1.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) ~[fabric-loader-0.12.12.jar:?]
	... 2 more
Caused by: org.spongepowered.asm.mixin.throwables.ClassMetadataNotFoundException: net.minecraft.util.CubicSampler$class_4859
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformSingleDescriptor(MixinTargetContext.java:1002) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformSingleDescriptor(MixinTargetContext.java:962) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformLVT(MixinTargetContext.java:563) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.transformMethod(MixinTargetContext.java:469) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyNormalMethod(MixinApplicatorStandard.java:533) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMethods(MixinApplicatorStandard.java:519) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMixin(MixinApplicatorStandard.java:386) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.apply(MixinApplicatorStandard.java:325) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.apply(TargetClassContext.java:421) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.applyMixins(TargetClassContext.java:403) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:363) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:234) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClassBytes(MixinTransformer.java:202) ~[sponge-mixin-0.10.7+mixin.0.8.4.jar:0.10.7+mixin.0.8.4]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.getPostMixinClassByteArray(KnotClassDelegate.java:247) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassDelegate.tryLoadClass(KnotClassDelegate.java:150) ~[fabric-loader-0.12.12.jar:?]
	at net.fabricmc.loader.impl.launch.knot.KnotClassLoader.loadClass(KnotClassLoader.java:155) ~[fabric-loader-0.12.12.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:520) ~[?:?]
	at net.minecraft.client.main.Main.main(Main.java:208) ~[fabric-loader-0.12.12-1.18.1.jar:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:608) ~[fabric-loader-0.12.12.jar:?]
	... 2 more
