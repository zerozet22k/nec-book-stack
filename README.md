
```
nec-book-stack
├─ nec-book
│  ├─ .env
│  ├─ nodemon.json
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ README.md
│  ├─ src
│  │  ├─ app.ts
│  │  ├─ config
│  │  │  ├─ config.ts
│  │  │  └─ db.ts
│  │  ├─ controllers
│  │  │  ├─ authController.ts
│  │  │  ├─ bookController.ts
│  │  │  ├─ bookOrderController.ts
│  │  │  ├─ bookSubscriptionController.ts
│  │  │  ├─ categoryController.ts
│  │  │  ├─ transactionController.ts
│  │  │  ├─ userController.ts
│  │  │  └─ webhookController.ts
│  │  ├─ middlewares
│  │  │  └─ authMiddleware.ts
│  │  ├─ models
│  │  │  ├─ Book.ts
│  │  │  ├─ BookOrder.ts
│  │  │  ├─ BookSubscription.ts
│  │  │  ├─ Category.ts
│  │  │  ├─ Transaction.ts
│  │  │  └─ User.ts
│  │  ├─ routes
│  │  │  ├─ authRoutes.ts
│  │  │  ├─ bookOrderRoutes.ts
│  │  │  ├─ bookRoutes.ts
│  │  │  ├─ bookSubscriptionRoutes.ts
│  │  │  ├─ categoryRoutes.ts
│  │  │  ├─ transactionRoutes.ts
│  │  │  └─ userRoutes.ts
│  │  ├─ services
│  │  │  └─ tokenService.ts
│  │  └─ utils
│  │     └─ handlers.ts
│  └─ tsconfig.json
├─ nec-book-app
│  ├─ .bundle
│  │  └─ config
│  ├─ .eslintrc.js
│  ├─ .prettierrc.js
│  ├─ .watchmanconfig
│  ├─ android
│  │  ├─ .gradle
│  │  │  ├─ 8.13
│  │  │  │  ├─ checksums
│  │  │  │  │  ├─ checksums.lock
│  │  │  │  │  ├─ md5-checksums.bin
│  │  │  │  │  └─ sha1-checksums.bin
│  │  │  │  ├─ executionHistory
│  │  │  │  │  ├─ executionHistory.bin
│  │  │  │  │  └─ executionHistory.lock
│  │  │  │  ├─ expanded
│  │  │  │  ├─ fileChanges
│  │  │  │  │  └─ last-build.bin
│  │  │  │  ├─ fileHashes
│  │  │  │  │  ├─ fileHashes.bin
│  │  │  │  │  ├─ fileHashes.lock
│  │  │  │  │  └─ resourceHashesCache.bin
│  │  │  │  ├─ gc.properties
│  │  │  │  └─ vcsMetadata
│  │  │  ├─ buildOutputCleanup
│  │  │  │  ├─ buildOutputCleanup.lock
│  │  │  │  ├─ cache.properties
│  │  │  │  └─ outputFiles.bin
│  │  │  ├─ file-system.probe
│  │  │  ├─ noVersion
│  │  │  │  └─ buildLogic.lock
│  │  │  └─ vcs-1
│  │  │     └─ gc.properties
│  │  ├─ .kotlin
│  │  │  └─ sessions
│  │  ├─ app
│  │  │  ├─ .cxx
│  │  │  │  ├─ Debug
│  │  │  │  │  └─ 266f2j4f
│  │  │  │  │     ├─ arm64-v8a
│  │  │  │  │     │  ├─ .cmake
│  │  │  │  │     │  │  └─ api
│  │  │  │  │     │  │     └─ v1
│  │  │  │  │     │  │        ├─ query
│  │  │  │  │     │  │        │  └─ client-agp
│  │  │  │  │     │  │        │     ├─ cache-v2
│  │  │  │  │     │  │        │     ├─ cmakeFiles-v1
│  │  │  │  │     │  │        │     └─ codemodel-v2
│  │  │  │  │     │  │        └─ reply
│  │  │  │  │     │  │           ├─ cache-v2-e07341bcfd6ce478c3ce.json
│  │  │  │  │     │  │           ├─ cmakeFiles-v1-6a3ad43e42c620af2822.json
│  │  │  │  │     │  │           ├─ codemodel-v2-b5da85264aa9707c5120.json
│  │  │  │  │     │  │           ├─ directory-.-Debug-d0094a50bb2071803777.json
│  │  │  │  │     │  │           ├─ directory-ReactNativeBlobUtilSpec_autolinked_build-Debug-4dff1583f330db125ee9.json
│  │  │  │  │     │  │           ├─ directory-rnasyncstorage_autolinked_build-Debug-1e080f56bfae790e50ec.json
│  │  │  │  │     │  │           ├─ directory-rngesturehandler_codegen_autolinked_build-Debug-52cb5462322c76d52fed.json
│  │  │  │  │     │  │           ├─ directory-rnpdf_autolinked_build-Debug-e96e0d61f0b4e5193a6d.json
│  │  │  │  │     │  │           ├─ directory-rnreanimated_autolinked_build-Debug-5728b3c51bf401bcbdfb.json
│  │  │  │  │     │  │           ├─ directory-rnscreens_autolinked_build-Debug-1a6aa31328e8e535fd84.json
│  │  │  │  │     │  │           ├─ directory-RNVectorIconsSpec_autolinked_build-Debug-17e087bd8d3124c615a3.json
│  │  │  │  │     │  │           ├─ directory-safeareacontext_autolinked_build-Debug-42cb9c95c87161281639.json
│  │  │  │  │     │  │           ├─ index-2025-05-19T07-52-39-0302.json
│  │  │  │  │     │  │           ├─ target-appmodules-Debug-46a7184f4d4549e08984.json
│  │  │  │  │     │  │           ├─ target-react_codegen_ReactNativeBlobUtilSpec-Debug-ed317252006eded7c780.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnasyncstorage-Debug-620fcbfb21cb455675b6.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rngesturehandler_codegen-Debug-c6e1c3d49bfe04ad1485.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnpdf-Debug-6e431262800157b876b7.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnreanimated-Debug-2d41e6563119f2386c2e.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnscreens-Debug-57ea99cd785b492c55d4.json
│  │  │  │  │     │  │           ├─ target-react_codegen_RNVectorIconsSpec-Debug-7d168b3792834298d259.json
│  │  │  │  │     │  │           └─ target-react_codegen_safeareacontext-Debug-7765ac57f2c1d5f15cd7.json
│  │  │  │  │     │  ├─ .ninja_deps
│  │  │  │  │     │  ├─ .ninja_log
│  │  │  │  │     │  ├─ additional_project_files.txt
│  │  │  │  │     │  ├─ android_gradle_build.json
│  │  │  │  │     │  ├─ android_gradle_build_mini.json
│  │  │  │  │     │  ├─ build.ninja
│  │  │  │  │     │  ├─ build_file_index.txt
│  │  │  │  │     │  ├─ CMakeCache.txt
│  │  │  │  │     │  ├─ CMakeFiles
│  │  │  │  │     │  │  ├─ 3.22.1-g37088a8-dirty
│  │  │  │  │     │  │  │  ├─ CMakeCCompiler.cmake
│  │  │  │  │     │  │  │  ├─ CMakeCXXCompiler.cmake
│  │  │  │  │     │  │  │  ├─ CMakeDetermineCompilerABI_C.bin
│  │  │  │  │     │  │  │  ├─ CMakeDetermineCompilerABI_CXX.bin
│  │  │  │  │     │  │  │  ├─ CMakeSystem.cmake
│  │  │  │  │     │  │  │  ├─ CompilerIdC
│  │  │  │  │     │  │  │  │  ├─ CMakeCCompilerId.c
│  │  │  │  │     │  │  │  │  ├─ CMakeCCompilerId.o
│  │  │  │  │     │  │  │  │  └─ tmp
│  │  │  │  │     │  │  │  └─ CompilerIdCXX
│  │  │  │  │     │  │  │     ├─ CMakeCXXCompilerId.cpp
│  │  │  │  │     │  │  │     ├─ CMakeCXXCompilerId.o
│  │  │  │  │     │  │  │     └─ tmp
│  │  │  │  │     │  │  ├─ appmodules.dir
│  │  │  │  │     │  │  │  ├─ C_
│  │  │  │  │     │  │  │  │  └─ Code
│  │  │  │  │     │  │  │  │     └─ nec-book-app
│  │  │  │  │     │  │  │  │        └─ android
│  │  │  │  │     │  │  │  │           └─ app
│  │  │  │  │     │  │  │  │              └─ build
│  │  │  │  │     │  │  │  │                 └─ generated
│  │  │  │  │     │  │  │  │                    └─ autolinking
│  │  │  │  │     │  │  │  │                       └─ src
│  │  │  │  │     │  │  │  │                          └─ main
│  │  │  │  │     │  │  │  │                             └─ jni
│  │  │  │  │     │  │  │  │                                └─ autolinking.cpp.o
│  │  │  │  │     │  │  │  └─ OnLoad.cpp.o
│  │  │  │  │     │  │  ├─ cmake.check_cache
│  │  │  │  │     │  │  ├─ cmake.verify_globs
│  │  │  │  │     │  │  ├─ CMakeOutput.log
│  │  │  │  │     │  │  ├─ CMakeTmp
│  │  │  │  │     │  │  ├─ rules.ninja
│  │  │  │  │     │  │  ├─ TargetDirectories.txt
│  │  │  │  │     │  │  └─ VerifyGlobs.cmake
│  │  │  │  │     │  ├─ cmake_install.cmake
│  │  │  │  │     │  ├─ compile_commands.json
│  │  │  │  │     │  ├─ compile_commands.json.bin
│  │  │  │  │     │  ├─ configure_fingerprint.bin
│  │  │  │  │     │  ├─ metadata_generation_command.txt
│  │  │  │  │     │  ├─ prefab_config.json
│  │  │  │  │     │  ├─ ReactNativeBlobUtilSpec_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_ReactNativeBlobUtilSpec.dir
│  │  │  │  │     │  │  │     ├─ 2361107e616b8ab90a9b526b4425e420
│  │  │  │  │     │  │  │     │  └─ ReactNativeBlobUtilSpecJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ ReactNativeBlobUtilSpec
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ ReactNativeBlobUtilSpec-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnasyncstorage_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnasyncstorage.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnasyncstorage
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnasyncstorageJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnasyncstorage-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rngesturehandler_codegen_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rngesturehandler_codegen.dir
│  │  │  │  │     │  │  │     ├─ bac033cd950586cef66695376748dd33
│  │  │  │  │     │  │  │     │  └─ rngesturehandler_codegenJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rngesturehandler_codegen
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rngesturehandler_codegen-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnpdf_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnpdf.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnpdf
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnpdfJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnpdf-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnreanimated_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnreanimated.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnreanimated
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnreanimatedJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnreanimated-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnscreens_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnscreens.dir
│  │  │  │  │     │  │  │     ├─ 391f4a68aed65e0f0d78d3ea11250c82
│  │  │  │  │     │  │  │     │  └─ common
│  │  │  │  │     │  │  │     │     └─ cpp
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ rnscreens
│  │  │  │  │     │  │  │     │                    ├─ RNSFullWindowOverlayShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSModalScreenShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenStackHeaderConfigState.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenStackHeaderSubviewState.cpp.o
│  │  │  │  │     │  │  │     │                    └─ RNSScreenState.cpp.o
│  │  │  │  │     │  │  │     ├─ 8a31dbcdf5039f0f2fa66c1dddf2dc23
│  │  │  │  │     │  │  │     │  └─ cpp
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ rnscreens
│  │  │  │  │     │  │  │     │                 ├─ RNSScreenStackHeaderConfigShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                 └─ RNSScreenStackHeaderSubviewShadowNode.cpp.o
│  │  │  │  │     │  │  │     ├─ b3b0db3b5b0256c2f5b806fee963c037
│  │  │  │  │     │  │  │     │  └─ source
│  │  │  │  │     │  │  │     │     └─ codegen
│  │  │  │  │     │  │  │     │        └─ jni
│  │  │  │  │     │  │  │     │           └─ react
│  │  │  │  │     │  │  │     │              └─ renderer
│  │  │  │  │     │  │  │     │                 └─ components
│  │  │  │  │     │  │  │     │                    └─ rnscreens
│  │  │  │  │     │  │  │     │                       ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │                       └─ rnscreensJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ d2526614ffd397f3aa77f5487a3a56fc
│  │  │  │  │     │  │  │     │  └─ generated
│  │  │  │  │     │  │  │     │     └─ source
│  │  │  │  │     │  │  │     │        └─ codegen
│  │  │  │  │     │  │  │     │           └─ jni
│  │  │  │  │     │  │  │     │              └─ react
│  │  │  │  │     │  │  │     │                 └─ renderer
│  │  │  │  │     │  │  │     │                    └─ components
│  │  │  │  │     │  │  │     │                       └─ rnscreens
│  │  │  │  │     │  │  │     │                          ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │                          └─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     ├─ f3a08f4af0f7d908d38d8a678dc00767
│  │  │  │  │     │  │  │     │  └─ build
│  │  │  │  │     │  │  │     │     └─ generated
│  │  │  │  │     │  │  │     │        └─ source
│  │  │  │  │     │  │  │     │           └─ codegen
│  │  │  │  │     │  │  │     │              └─ jni
│  │  │  │  │     │  │  │     │                 └─ react
│  │  │  │  │     │  │  │     │                    └─ renderer
│  │  │  │  │     │  │  │     │                       └─ components
│  │  │  │  │     │  │  │     │                          └─ rnscreens
│  │  │  │  │     │  │  │     │                             ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │                             └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnscreens.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ RNVectorIconsSpec_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_RNVectorIconsSpec.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ RNVectorIconsSpec
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ RNVectorIconsSpecJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ RNVectorIconsSpec-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ safeareacontext_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_safeareacontext.dir
│  │  │  │  │     │  │  │     ├─ 2c184c4d30a7848c6aa8ddb7f8307c6e
│  │  │  │  │     │  │  │     │  └─ react
│  │  │  │  │     │  │  │     │     └─ renderer
│  │  │  │  │     │  │  │     │        └─ components
│  │  │  │  │     │  │  │     │           └─ safeareacontext
│  │  │  │  │     │  │  │     │              └─ RNCSafeAreaViewShadowNode.cpp.o
│  │  │  │  │     │  │  │     ├─ 9f6f6be174adebe3cd0c34ca495df0c7
│  │  │  │  │     │  │  │     │  └─ jni
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ safeareacontext
│  │  │  │  │     │  │  │     │                 └─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     ├─ a1d3d0d7006545f905a8ea8373937a4d
│  │  │  │  │     │  │  │     │  └─ android
│  │  │  │  │     │  │  │     │     └─ build
│  │  │  │  │     │  │  │     │        └─ generated
│  │  │  │  │     │  │  │     │           └─ source
│  │  │  │  │     │  │  │     │              └─ codegen
│  │  │  │  │     │  │  │     │                 └─ jni
│  │  │  │  │     │  │  │     │                    └─ safeareacontext-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ a773985f0f2e09e145f56a0b75e38e9b
│  │  │  │  │     │  │  │     │  └─ codegen
│  │  │  │  │     │  │  │     │     └─ jni
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ safeareacontext
│  │  │  │  │     │  │  │     │                    ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │                    └─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     ├─ b744071d122ced8e068cecf0f5ca0d89
│  │  │  │  │     │  │  │     │  └─ cpp
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ safeareacontext
│  │  │  │  │     │  │  │     │                 └─ RNCSafeAreaViewState.cpp.o
│  │  │  │  │     │  │  │     ├─ c1b726b4478e52471b2f14dae633ebb7
│  │  │  │  │     │  │  │     │  └─ source
│  │  │  │  │     │  │  │     │     └─ codegen
│  │  │  │  │     │  │  │     │        └─ jni
│  │  │  │  │     │  │  │     │           └─ react
│  │  │  │  │     │  │  │     │              └─ renderer
│  │  │  │  │     │  │  │     │                 └─ components
│  │  │  │  │     │  │  │     │                    └─ safeareacontext
│  │  │  │  │     │  │  │     │                       ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │                       └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ f2e421a0d798a3e9ceed2d3ffb55f2fb
│  │  │  │  │     │  │  │        └─ renderer
│  │  │  │  │     │  │  │           └─ components
│  │  │  │  │     │  │  │              └─ safeareacontext
│  │  │  │  │     │  │  │                 └─ safeareacontextJSI-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  └─ symbol_folder_index.txt
│  │  │  │  │     ├─ armeabi-v7a
│  │  │  │  │     │  ├─ .cmake
│  │  │  │  │     │  │  └─ api
│  │  │  │  │     │  │     └─ v1
│  │  │  │  │     │  │        ├─ query
│  │  │  │  │     │  │        │  └─ client-agp
│  │  │  │  │     │  │        │     ├─ cache-v2
│  │  │  │  │     │  │        │     ├─ cmakeFiles-v1
│  │  │  │  │     │  │        │     └─ codemodel-v2
│  │  │  │  │     │  │        └─ reply
│  │  │  │  │     │  │           ├─ cache-v2-c98f63b111ca0e457c21.json
│  │  │  │  │     │  │           ├─ cmakeFiles-v1-6c768a450234d181c376.json
│  │  │  │  │     │  │           ├─ codemodel-v2-27544c2b9dbf154cbd4d.json
│  │  │  │  │     │  │           ├─ directory-.-Debug-d0094a50bb2071803777.json
│  │  │  │  │     │  │           ├─ directory-ReactNativeBlobUtilSpec_autolinked_build-Debug-4dff1583f330db125ee9.json
│  │  │  │  │     │  │           ├─ directory-rnasyncstorage_autolinked_build-Debug-1e080f56bfae790e50ec.json
│  │  │  │  │     │  │           ├─ directory-rngesturehandler_codegen_autolinked_build-Debug-52cb5462322c76d52fed.json
│  │  │  │  │     │  │           ├─ directory-rnpdf_autolinked_build-Debug-e96e0d61f0b4e5193a6d.json
│  │  │  │  │     │  │           ├─ directory-rnreanimated_autolinked_build-Debug-5728b3c51bf401bcbdfb.json
│  │  │  │  │     │  │           ├─ directory-rnscreens_autolinked_build-Debug-1a6aa31328e8e535fd84.json
│  │  │  │  │     │  │           ├─ directory-RNVectorIconsSpec_autolinked_build-Debug-17e087bd8d3124c615a3.json
│  │  │  │  │     │  │           ├─ directory-safeareacontext_autolinked_build-Debug-42cb9c95c87161281639.json
│  │  │  │  │     │  │           ├─ index-2025-05-19T07-52-41-0672.json
│  │  │  │  │     │  │           ├─ target-appmodules-Debug-ae4fd8ffc8ce1e365a36.json
│  │  │  │  │     │  │           ├─ target-react_codegen_ReactNativeBlobUtilSpec-Debug-b70e767d6d041fa42bbc.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnasyncstorage-Debug-415636de1bb29b4b5be6.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rngesturehandler_codegen-Debug-1d4f2d08bd20e629dcf4.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnpdf-Debug-389457abf63e3d2ee30f.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnreanimated-Debug-f3f2e6c469a04e08ef25.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnscreens-Debug-009dcf623cc30da89310.json
│  │  │  │  │     │  │           ├─ target-react_codegen_RNVectorIconsSpec-Debug-6a61087d8f5a8d4b9752.json
│  │  │  │  │     │  │           └─ target-react_codegen_safeareacontext-Debug-b02e98d28dcd5aa880fe.json
│  │  │  │  │     │  ├─ .ninja_deps
│  │  │  │  │     │  ├─ .ninja_log
│  │  │  │  │     │  ├─ additional_project_files.txt
│  │  │  │  │     │  ├─ android_gradle_build.json
│  │  │  │  │     │  ├─ android_gradle_build_mini.json
│  │  │  │  │     │  ├─ build.ninja
│  │  │  │  │     │  ├─ build_file_index.txt
│  │  │  │  │     │  ├─ CMakeCache.txt
│  │  │  │  │     │  ├─ CMakeFiles
│  │  │  │  │     │  │  ├─ 3.22.1-g37088a8-dirty
│  │  │  │  │     │  │  │  ├─ CMakeCCompiler.cmake
│  │  │  │  │     │  │  │  ├─ CMakeCXXCompiler.cmake
│  │  │  │  │     │  │  │  ├─ CMakeDetermineCompilerABI_C.bin
│  │  │  │  │     │  │  │  ├─ CMakeDetermineCompilerABI_CXX.bin
│  │  │  │  │     │  │  │  ├─ CMakeSystem.cmake
│  │  │  │  │     │  │  │  ├─ CompilerIdC
│  │  │  │  │     │  │  │  │  ├─ CMakeCCompilerId.c
│  │  │  │  │     │  │  │  │  ├─ CMakeCCompilerId.o
│  │  │  │  │     │  │  │  │  └─ tmp
│  │  │  │  │     │  │  │  └─ CompilerIdCXX
│  │  │  │  │     │  │  │     ├─ CMakeCXXCompilerId.cpp
│  │  │  │  │     │  │  │     ├─ CMakeCXXCompilerId.o
│  │  │  │  │     │  │  │     └─ tmp
│  │  │  │  │     │  │  ├─ appmodules.dir
│  │  │  │  │     │  │  │  ├─ C_
│  │  │  │  │     │  │  │  │  └─ Code
│  │  │  │  │     │  │  │  │     └─ nec-book-app
│  │  │  │  │     │  │  │  │        └─ android
│  │  │  │  │     │  │  │  │           └─ app
│  │  │  │  │     │  │  │  │              └─ build
│  │  │  │  │     │  │  │  │                 └─ generated
│  │  │  │  │     │  │  │  │                    └─ autolinking
│  │  │  │  │     │  │  │  │                       └─ src
│  │  │  │  │     │  │  │  │                          └─ main
│  │  │  │  │     │  │  │  │                             └─ jni
│  │  │  │  │     │  │  │  │                                └─ autolinking.cpp.o
│  │  │  │  │     │  │  │  └─ OnLoad.cpp.o
│  │  │  │  │     │  │  ├─ cmake.check_cache
│  │  │  │  │     │  │  ├─ cmake.verify_globs
│  │  │  │  │     │  │  ├─ CMakeOutput.log
│  │  │  │  │     │  │  ├─ CMakeTmp
│  │  │  │  │     │  │  ├─ rules.ninja
│  │  │  │  │     │  │  ├─ TargetDirectories.txt
│  │  │  │  │     │  │  └─ VerifyGlobs.cmake
│  │  │  │  │     │  ├─ cmake_install.cmake
│  │  │  │  │     │  ├─ compile_commands.json
│  │  │  │  │     │  ├─ compile_commands.json.bin
│  │  │  │  │     │  ├─ configure_fingerprint.bin
│  │  │  │  │     │  ├─ metadata_generation_command.txt
│  │  │  │  │     │  ├─ prefab_config.json
│  │  │  │  │     │  ├─ ReactNativeBlobUtilSpec_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_ReactNativeBlobUtilSpec.dir
│  │  │  │  │     │  │  │     ├─ 2361107e616b8ab90a9b526b4425e420
│  │  │  │  │     │  │  │     │  └─ ReactNativeBlobUtilSpecJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ ReactNativeBlobUtilSpec
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ ReactNativeBlobUtilSpec-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnasyncstorage_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnasyncstorage.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnasyncstorage
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnasyncstorageJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnasyncstorage-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rngesturehandler_codegen_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rngesturehandler_codegen.dir
│  │  │  │  │     │  │  │     ├─ bac033cd950586cef66695376748dd33
│  │  │  │  │     │  │  │     │  └─ rngesturehandler_codegenJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rngesturehandler_codegen
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rngesturehandler_codegen-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnpdf_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnpdf.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnpdf
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnpdfJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnpdf-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnreanimated_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnreanimated.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnreanimated
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnreanimatedJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnreanimated-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnscreens_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnscreens.dir
│  │  │  │  │     │  │  │     ├─ 391f4a68aed65e0f0d78d3ea11250c82
│  │  │  │  │     │  │  │     │  └─ common
│  │  │  │  │     │  │  │     │     └─ cpp
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ rnscreens
│  │  │  │  │     │  │  │     │                    ├─ RNSFullWindowOverlayShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSModalScreenShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenStackHeaderConfigState.cpp.o
│  │  │  │  │     │  │  │     │                    └─ RNSScreenState.cpp.o
│  │  │  │  │     │  │  │     ├─ 8a31dbcdf5039f0f2fa66c1dddf2dc23
│  │  │  │  │     │  │  │     │  └─ cpp
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ rnscreens
│  │  │  │  │     │  │  │     │                 ├─ RNSScreenStackHeaderConfigShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                 ├─ RNSScreenStackHeaderSubviewShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                 └─ RNSScreenStackHeaderSubviewState.cpp.o
│  │  │  │  │     │  │  │     ├─ b3b0db3b5b0256c2f5b806fee963c037
│  │  │  │  │     │  │  │     │  └─ source
│  │  │  │  │     │  │  │     │     └─ codegen
│  │  │  │  │     │  │  │     │        └─ jni
│  │  │  │  │     │  │  │     │           └─ react
│  │  │  │  │     │  │  │     │              └─ renderer
│  │  │  │  │     │  │  │     │                 └─ components
│  │  │  │  │     │  │  │     │                    └─ rnscreens
│  │  │  │  │     │  │  │     │                       ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │                       └─ rnscreensJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ d2526614ffd397f3aa77f5487a3a56fc
│  │  │  │  │     │  │  │     │  └─ generated
│  │  │  │  │     │  │  │     │     └─ source
│  │  │  │  │     │  │  │     │        └─ codegen
│  │  │  │  │     │  │  │     │           └─ jni
│  │  │  │  │     │  │  │     │              └─ react
│  │  │  │  │     │  │  │     │                 └─ renderer
│  │  │  │  │     │  │  │     │                    └─ components
│  │  │  │  │     │  │  │     │                       └─ rnscreens
│  │  │  │  │     │  │  │     │                          ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │                          └─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     ├─ f3a08f4af0f7d908d38d8a678dc00767
│  │  │  │  │     │  │  │     │  └─ build
│  │  │  │  │     │  │  │     │     └─ generated
│  │  │  │  │     │  │  │     │        └─ source
│  │  │  │  │     │  │  │     │           └─ codegen
│  │  │  │  │     │  │  │     │              └─ jni
│  │  │  │  │     │  │  │     │                 └─ react
│  │  │  │  │     │  │  │     │                    └─ renderer
│  │  │  │  │     │  │  │     │                       └─ components
│  │  │  │  │     │  │  │     │                          └─ rnscreens
│  │  │  │  │     │  │  │     │                             ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │                             └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnscreens.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ RNVectorIconsSpec_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_RNVectorIconsSpec.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ RNVectorIconsSpec
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ RNVectorIconsSpecJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ RNVectorIconsSpec-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ safeareacontext_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_safeareacontext.dir
│  │  │  │  │     │  │  │     ├─ 9f6f6be174adebe3cd0c34ca495df0c7
│  │  │  │  │     │  │  │     │  └─ jni
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ safeareacontext
│  │  │  │  │     │  │  │     │                 ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │                 └─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     ├─ a773985f0f2e09e145f56a0b75e38e9b
│  │  │  │  │     │  │  │     │  └─ codegen
│  │  │  │  │     │  │  │     │     └─ jni
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ safeareacontext
│  │  │  │  │     │  │  │     │                    ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │                    └─ States.cpp.o
│  │  │  │  │     │  │  │     ├─ b1805f4acbaf3a3dfcb857cb6d4c0834
│  │  │  │  │     │  │  │     │  └─ build
│  │  │  │  │     │  │  │     │     └─ generated
│  │  │  │  │     │  │  │     │        └─ source
│  │  │  │  │     │  │  │     │           └─ codegen
│  │  │  │  │     │  │  │     │              └─ jni
│  │  │  │  │     │  │  │     │                 └─ safeareacontext-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ b744071d122ced8e068cecf0f5ca0d89
│  │  │  │  │     │  │  │     │  └─ cpp
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ safeareacontext
│  │  │  │  │     │  │  │     │                 └─ RNCSafeAreaViewState.cpp.o
│  │  │  │  │     │  │  │     ├─ c1b726b4478e52471b2f14dae633ebb7
│  │  │  │  │     │  │  │     │  └─ source
│  │  │  │  │     │  │  │     │     └─ codegen
│  │  │  │  │     │  │  │     │        └─ jni
│  │  │  │  │     │  │  │     │           └─ react
│  │  │  │  │     │  │  │     │              └─ renderer
│  │  │  │  │     │  │  │     │                 └─ components
│  │  │  │  │     │  │  │     │                    └─ safeareacontext
│  │  │  │  │     │  │  │     │                       └─ Props.cpp.o
│  │  │  │  │     │  │  │     ├─ e98985743bbdc74ec02f89e4deb9cf36
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ safeareacontext
│  │  │  │  │     │  │  │     │           └─ RNCSafeAreaViewShadowNode.cpp.o
│  │  │  │  │     │  │  │     └─ f2e421a0d798a3e9ceed2d3ffb55f2fb
│  │  │  │  │     │  │  │        └─ renderer
│  │  │  │  │     │  │  │           └─ components
│  │  │  │  │     │  │  │              └─ safeareacontext
│  │  │  │  │     │  │  │                 └─ safeareacontextJSI-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  └─ symbol_folder_index.txt
│  │  │  │  │     ├─ hash_key.txt
│  │  │  │  │     ├─ prefab
│  │  │  │  │     │  ├─ arm64-v8a
│  │  │  │  │     │  │  └─ prefab
│  │  │  │  │     │  │     └─ lib
│  │  │  │  │     │  │        └─ aarch64-linux-android
│  │  │  │  │     │  │           └─ cmake
│  │  │  │  │     │  │              ├─ fbjni
│  │  │  │  │     │  │              │  ├─ fbjniConfig.cmake
│  │  │  │  │     │  │              │  └─ fbjniConfigVersion.cmake
│  │  │  │  │     │  │              ├─ hermes-engine
│  │  │  │  │     │  │              │  ├─ hermes-engineConfig.cmake
│  │  │  │  │     │  │              │  └─ hermes-engineConfigVersion.cmake
│  │  │  │  │     │  │              ├─ react-native-reanimated
│  │  │  │  │     │  │              │  ├─ react-native-reanimatedConfig.cmake
│  │  │  │  │     │  │              │  └─ react-native-reanimatedConfigVersion.cmake
│  │  │  │  │     │  │              └─ ReactAndroid
│  │  │  │  │     │  │                 ├─ ReactAndroidConfig.cmake
│  │  │  │  │     │  │                 └─ ReactAndroidConfigVersion.cmake
│  │  │  │  │     │  ├─ armeabi-v7a
│  │  │  │  │     │  │  └─ prefab
│  │  │  │  │     │  │     └─ lib
│  │  │  │  │     │  │        └─ arm-linux-androideabi
│  │  │  │  │     │  │           └─ cmake
│  │  │  │  │     │  │              ├─ fbjni
│  │  │  │  │     │  │              │  ├─ fbjniConfig.cmake
│  │  │  │  │     │  │              │  └─ fbjniConfigVersion.cmake
│  │  │  │  │     │  │              ├─ hermes-engine
│  │  │  │  │     │  │              │  ├─ hermes-engineConfig.cmake
│  │  │  │  │     │  │              │  └─ hermes-engineConfigVersion.cmake
│  │  │  │  │     │  │              ├─ react-native-reanimated
│  │  │  │  │     │  │              │  ├─ react-native-reanimatedConfig.cmake
│  │  │  │  │     │  │              │  └─ react-native-reanimatedConfigVersion.cmake
│  │  │  │  │     │  │              └─ ReactAndroid
│  │  │  │  │     │  │                 ├─ ReactAndroidConfig.cmake
│  │  │  │  │     │  │                 └─ ReactAndroidConfigVersion.cmake
│  │  │  │  │     │  ├─ x86
│  │  │  │  │     │  │  └─ prefab
│  │  │  │  │     │  │     └─ lib
│  │  │  │  │     │  │        └─ i686-linux-android
│  │  │  │  │     │  │           └─ cmake
│  │  │  │  │     │  │              ├─ fbjni
│  │  │  │  │     │  │              │  ├─ fbjniConfig.cmake
│  │  │  │  │     │  │              │  └─ fbjniConfigVersion.cmake
│  │  │  │  │     │  │              ├─ hermes-engine
│  │  │  │  │     │  │              │  ├─ hermes-engineConfig.cmake
│  │  │  │  │     │  │              │  └─ hermes-engineConfigVersion.cmake
│  │  │  │  │     │  │              ├─ react-native-reanimated
│  │  │  │  │     │  │              │  ├─ react-native-reanimatedConfig.cmake
│  │  │  │  │     │  │              │  └─ react-native-reanimatedConfigVersion.cmake
│  │  │  │  │     │  │              └─ ReactAndroid
│  │  │  │  │     │  │                 ├─ ReactAndroidConfig.cmake
│  │  │  │  │     │  │                 └─ ReactAndroidConfigVersion.cmake
│  │  │  │  │     │  └─ x86_64
│  │  │  │  │     │     └─ prefab
│  │  │  │  │     │        └─ lib
│  │  │  │  │     │           └─ x86_64-linux-android
│  │  │  │  │     │              └─ cmake
│  │  │  │  │     │                 ├─ fbjni
│  │  │  │  │     │                 │  ├─ fbjniConfig.cmake
│  │  │  │  │     │                 │  └─ fbjniConfigVersion.cmake
│  │  │  │  │     │                 ├─ hermes-engine
│  │  │  │  │     │                 │  ├─ hermes-engineConfig.cmake
│  │  │  │  │     │                 │  └─ hermes-engineConfigVersion.cmake
│  │  │  │  │     │                 ├─ react-native-reanimated
│  │  │  │  │     │                 │  ├─ react-native-reanimatedConfig.cmake
│  │  │  │  │     │                 │  └─ react-native-reanimatedConfigVersion.cmake
│  │  │  │  │     │                 └─ ReactAndroid
│  │  │  │  │     │                    ├─ ReactAndroidConfig.cmake
│  │  │  │  │     │                    └─ ReactAndroidConfigVersion.cmake
│  │  │  │  │     ├─ x86
│  │  │  │  │     │  ├─ .cmake
│  │  │  │  │     │  │  └─ api
│  │  │  │  │     │  │     └─ v1
│  │  │  │  │     │  │        ├─ query
│  │  │  │  │     │  │        │  └─ client-agp
│  │  │  │  │     │  │        │     ├─ cache-v2
│  │  │  │  │     │  │        │     ├─ cmakeFiles-v1
│  │  │  │  │     │  │        │     └─ codemodel-v2
│  │  │  │  │     │  │        └─ reply
│  │  │  │  │     │  │           ├─ cache-v2-434151212806b6365b62.json
│  │  │  │  │     │  │           ├─ cmakeFiles-v1-333ac5c3879d851bfc15.json
│  │  │  │  │     │  │           ├─ codemodel-v2-aa91fc4773b4063234c6.json
│  │  │  │  │     │  │           ├─ directory-.-Debug-d0094a50bb2071803777.json
│  │  │  │  │     │  │           ├─ directory-ReactNativeBlobUtilSpec_autolinked_build-Debug-4dff1583f330db125ee9.json
│  │  │  │  │     │  │           ├─ directory-rnasyncstorage_autolinked_build-Debug-1e080f56bfae790e50ec.json
│  │  │  │  │     │  │           ├─ directory-rngesturehandler_codegen_autolinked_build-Debug-52cb5462322c76d52fed.json
│  │  │  │  │     │  │           ├─ directory-rnpdf_autolinked_build-Debug-e96e0d61f0b4e5193a6d.json
│  │  │  │  │     │  │           ├─ directory-rnreanimated_autolinked_build-Debug-5728b3c51bf401bcbdfb.json
│  │  │  │  │     │  │           ├─ directory-rnscreens_autolinked_build-Debug-1a6aa31328e8e535fd84.json
│  │  │  │  │     │  │           ├─ directory-RNVectorIconsSpec_autolinked_build-Debug-17e087bd8d3124c615a3.json
│  │  │  │  │     │  │           ├─ directory-safeareacontext_autolinked_build-Debug-42cb9c95c87161281639.json
│  │  │  │  │     │  │           ├─ index-2025-05-19T07-52-43-0155.json
│  │  │  │  │     │  │           ├─ target-appmodules-Debug-cc426d886ab1b14cd94e.json
│  │  │  │  │     │  │           ├─ target-react_codegen_ReactNativeBlobUtilSpec-Debug-14ededdbc784cd4c1810.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnasyncstorage-Debug-620fcbfb21cb455675b6.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rngesturehandler_codegen-Debug-bc5277edcc85a0619182.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnpdf-Debug-6e431262800157b876b7.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnreanimated-Debug-2d41e6563119f2386c2e.json
│  │  │  │  │     │  │           ├─ target-react_codegen_rnscreens-Debug-5c748f35b5fc05c302bc.json
│  │  │  │  │     │  │           ├─ target-react_codegen_RNVectorIconsSpec-Debug-7d168b3792834298d259.json
│  │  │  │  │     │  │           └─ target-react_codegen_safeareacontext-Debug-37a3ebf112e02cb0386b.json
│  │  │  │  │     │  ├─ .ninja_deps
│  │  │  │  │     │  ├─ .ninja_log
│  │  │  │  │     │  ├─ additional_project_files.txt
│  │  │  │  │     │  ├─ android_gradle_build.json
│  │  │  │  │     │  ├─ android_gradle_build_mini.json
│  │  │  │  │     │  ├─ build.ninja
│  │  │  │  │     │  ├─ build_file_index.txt
│  │  │  │  │     │  ├─ CMakeCache.txt
│  │  │  │  │     │  ├─ CMakeFiles
│  │  │  │  │     │  │  ├─ 3.22.1-g37088a8-dirty
│  │  │  │  │     │  │  │  ├─ CMakeCCompiler.cmake
│  │  │  │  │     │  │  │  ├─ CMakeCXXCompiler.cmake
│  │  │  │  │     │  │  │  ├─ CMakeDetermineCompilerABI_C.bin
│  │  │  │  │     │  │  │  ├─ CMakeDetermineCompilerABI_CXX.bin
│  │  │  │  │     │  │  │  ├─ CMakeSystem.cmake
│  │  │  │  │     │  │  │  ├─ CompilerIdC
│  │  │  │  │     │  │  │  │  ├─ CMakeCCompilerId.c
│  │  │  │  │     │  │  │  │  ├─ CMakeCCompilerId.o
│  │  │  │  │     │  │  │  │  └─ tmp
│  │  │  │  │     │  │  │  └─ CompilerIdCXX
│  │  │  │  │     │  │  │     ├─ CMakeCXXCompilerId.cpp
│  │  │  │  │     │  │  │     ├─ CMakeCXXCompilerId.o
│  │  │  │  │     │  │  │     └─ tmp
│  │  │  │  │     │  │  ├─ appmodules.dir
│  │  │  │  │     │  │  │  ├─ C_
│  │  │  │  │     │  │  │  │  └─ Code
│  │  │  │  │     │  │  │  │     └─ nec-book-app
│  │  │  │  │     │  │  │  │        └─ android
│  │  │  │  │     │  │  │  │           └─ app
│  │  │  │  │     │  │  │  │              └─ build
│  │  │  │  │     │  │  │  │                 └─ generated
│  │  │  │  │     │  │  │  │                    └─ autolinking
│  │  │  │  │     │  │  │  │                       └─ src
│  │  │  │  │     │  │  │  │                          └─ main
│  │  │  │  │     │  │  │  │                             └─ jni
│  │  │  │  │     │  │  │  │                                └─ autolinking.cpp.o
│  │  │  │  │     │  │  │  └─ OnLoad.cpp.o
│  │  │  │  │     │  │  ├─ cmake.check_cache
│  │  │  │  │     │  │  ├─ cmake.verify_globs
│  │  │  │  │     │  │  ├─ CMakeOutput.log
│  │  │  │  │     │  │  ├─ CMakeTmp
│  │  │  │  │     │  │  ├─ rules.ninja
│  │  │  │  │     │  │  ├─ TargetDirectories.txt
│  │  │  │  │     │  │  └─ VerifyGlobs.cmake
│  │  │  │  │     │  ├─ cmake_install.cmake
│  │  │  │  │     │  ├─ compile_commands.json
│  │  │  │  │     │  ├─ compile_commands.json.bin
│  │  │  │  │     │  ├─ configure_fingerprint.bin
│  │  │  │  │     │  ├─ metadata_generation_command.txt
│  │  │  │  │     │  ├─ prefab_config.json
│  │  │  │  │     │  ├─ ReactNativeBlobUtilSpec_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_ReactNativeBlobUtilSpec.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ ReactNativeBlobUtilSpec
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ReactNativeBlobUtilSpecJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ ReactNativeBlobUtilSpec-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnasyncstorage_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnasyncstorage.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnasyncstorage
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnasyncstorageJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnasyncstorage-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rngesturehandler_codegen_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rngesturehandler_codegen.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rngesturehandler_codegen
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rngesturehandler_codegenJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rngesturehandler_codegen-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnpdf_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnpdf.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnpdf
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnpdfJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnpdf-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnreanimated_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnreanimated.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ rnreanimated
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ rnreanimatedJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ rnreanimated-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ rnscreens_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_rnscreens.dir
│  │  │  │  │     │  │  │     ├─ 391f4a68aed65e0f0d78d3ea11250c82
│  │  │  │  │     │  │  │     │  ├─ android
│  │  │  │  │     │  │  │     │  │  └─ build
│  │  │  │  │     │  │  │     │  │     └─ generated
│  │  │  │  │     │  │  │     │  │        └─ source
│  │  │  │  │     │  │  │     │  │           └─ codegen
│  │  │  │  │     │  │  │     │  │              └─ jni
│  │  │  │  │     │  │  │     │  │                 └─ react
│  │  │  │  │     │  │  │     │  │                    └─ renderer
│  │  │  │  │     │  │  │     │  │                       └─ components
│  │  │  │  │     │  │  │     │  │                          └─ rnscreens
│  │  │  │  │     │  │  │     │  │                             ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │  │                             └─ States.cpp.o
│  │  │  │  │     │  │  │     │  └─ common
│  │  │  │  │     │  │  │     │     └─ cpp
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ rnscreens
│  │  │  │  │     │  │  │     │                    ├─ RNSFullWindowOverlayShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSModalScreenShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenStackHeaderConfigShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenStackHeaderConfigState.cpp.o
│  │  │  │  │     │  │  │     │                    ├─ RNSScreenStackHeaderSubviewShadowNode.cpp.o
│  │  │  │  │     │  │  │     │                    └─ RNSScreenStackHeaderSubviewState.cpp.o
│  │  │  │  │     │  │  │     ├─ b3b0db3b5b0256c2f5b806fee963c037
│  │  │  │  │     │  │  │     │  └─ source
│  │  │  │  │     │  │  │     │     └─ codegen
│  │  │  │  │     │  │  │     │        └─ jni
│  │  │  │  │     │  │  │     │           └─ react
│  │  │  │  │     │  │  │     │              └─ renderer
│  │  │  │  │     │  │  │     │                 └─ components
│  │  │  │  │     │  │  │     │                    └─ rnscreens
│  │  │  │  │     │  │  │     │                       └─ rnscreensJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ C_
│  │  │  │  │     │  │  │     │  └─ Code
│  │  │  │  │     │  │  │     │     └─ nec-book-app
│  │  │  │  │     │  │  │     ├─ d2526614ffd397f3aa77f5487a3a56fc
│  │  │  │  │     │  │  │     │  └─ generated
│  │  │  │  │     │  │  │     │     └─ source
│  │  │  │  │     │  │  │     │        └─ codegen
│  │  │  │  │     │  │  │     │           └─ jni
│  │  │  │  │     │  │  │     │              └─ react
│  │  │  │  │     │  │  │     │                 └─ renderer
│  │  │  │  │     │  │  │     │                    └─ components
│  │  │  │  │     │  │  │     │                       └─ rnscreens
│  │  │  │  │     │  │  │     │                          └─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     ├─ f3a08f4af0f7d908d38d8a678dc00767
│  │  │  │  │     │  │  │     │  └─ build
│  │  │  │  │     │  │  │     │     └─ generated
│  │  │  │  │     │  │  │     │        └─ source
│  │  │  │  │     │  │  │     │           └─ codegen
│  │  │  │  │     │  │  │     │              └─ jni
│  │  │  │  │     │  │  │     │                 └─ react
│  │  │  │  │     │  │  │     │                    └─ renderer
│  │  │  │  │     │  │  │     │                       └─ components
│  │  │  │  │     │  │  │     │                          └─ rnscreens
│  │  │  │  │     │  │  │     │                             ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │                             └─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     └─ rnscreens.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ RNVectorIconsSpec_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_RNVectorIconsSpec.dir
│  │  │  │  │     │  │  │     ├─ react
│  │  │  │  │     │  │  │     │  └─ renderer
│  │  │  │  │     │  │  │     │     └─ components
│  │  │  │  │     │  │  │     │        └─ RNVectorIconsSpec
│  │  │  │  │     │  │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │     │           ├─ Props.cpp.o
│  │  │  │  │     │  │  │     │           ├─ RNVectorIconsSpecJSI-generated.cpp.o
│  │  │  │  │     │  │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │     │           └─ States.cpp.o
│  │  │  │  │     │  │  │     └─ RNVectorIconsSpec-generated.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  ├─ safeareacontext_autolinked_build
│  │  │  │  │     │  │  ├─ CMakeFiles
│  │  │  │  │     │  │  │  └─ react_codegen_safeareacontext.dir
│  │  │  │  │     │  │  │     ├─ 9f6f6be174adebe3cd0c34ca495df0c7
│  │  │  │  │     │  │  │     │  └─ jni
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ safeareacontext
│  │  │  │  │     │  │  │     │                 └─ safeareacontextJSI-generated.cpp.o
│  │  │  │  │     │  │  │     ├─ a1d3d0d7006545f905a8ea8373937a4d
│  │  │  │  │     │  │  │     │  ├─ android
│  │  │  │  │     │  │  │     │  │  └─ build
│  │  │  │  │     │  │  │     │  │     └─ generated
│  │  │  │  │     │  │  │     │  │        └─ source
│  │  │  │  │     │  │  │     │  │           └─ codegen
│  │  │  │  │     │  │  │     │  │              └─ jni
│  │  │  │  │     │  │  │     │  │                 └─ safeareacontext-generated.cpp.o
│  │  │  │  │     │  │  │     │  └─ common
│  │  │  │  │     │  │  │     │     └─ cpp
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ safeareacontext
│  │  │  │  │     │  │  │     │                    └─ RNCSafeAreaViewState.cpp.o
│  │  │  │  │     │  │  │     ├─ a773985f0f2e09e145f56a0b75e38e9b
│  │  │  │  │     │  │  │     │  └─ codegen
│  │  │  │  │     │  │  │     │     └─ jni
│  │  │  │  │     │  │  │     │        └─ react
│  │  │  │  │     │  │  │     │           └─ renderer
│  │  │  │  │     │  │  │     │              └─ components
│  │  │  │  │     │  │  │     │                 └─ safeareacontext
│  │  │  │  │     │  │  │     │                    └─ ComponentDescriptors.cpp.o
│  │  │  │  │     │  │  │     ├─ b744071d122ced8e068cecf0f5ca0d89
│  │  │  │  │     │  │  │     │  └─ cpp
│  │  │  │  │     │  │  │     │     └─ react
│  │  │  │  │     │  │  │     │        └─ renderer
│  │  │  │  │     │  │  │     │           └─ components
│  │  │  │  │     │  │  │     │              └─ safeareacontext
│  │  │  │  │     │  │  │     │                 └─ RNCSafeAreaViewShadowNode.cpp.o
│  │  │  │  │     │  │  │     └─ c1b726b4478e52471b2f14dae633ebb7
│  │  │  │  │     │  │  │        └─ source
│  │  │  │  │     │  │  │           └─ codegen
│  │  │  │  │     │  │  │              └─ jni
│  │  │  │  │     │  │  │                 └─ react
│  │  │  │  │     │  │  │                    └─ renderer
│  │  │  │  │     │  │  │                       └─ components
│  │  │  │  │     │  │  │                          └─ safeareacontext
│  │  │  │  │     │  │  │                             ├─ EventEmitters.cpp.o
│  │  │  │  │     │  │  │                             ├─ Props.cpp.o
│  │  │  │  │     │  │  │                             ├─ ShadowNodes.cpp.o
│  │  │  │  │     │  │  │                             └─ States.cpp.o
│  │  │  │  │     │  │  └─ cmake_install.cmake
│  │  │  │  │     │  └─ symbol_folder_index.txt
│  │  │  │  │     └─ x86_64
│  │  │  │  │        ├─ .cmake
│  │  │  │  │        │  └─ api
│  │  │  │  │        │     └─ v1
│  │  │  │  │        │        ├─ query
│  │  │  │  │        │        │  └─ client-agp
│  │  │  │  │        │        │     ├─ cache-v2
│  │  │  │  │        │        │     ├─ cmakeFiles-v1
│  │  │  │  │        │        │     └─ codemodel-v2
│  │  │  │  │        │        └─ reply
│  │  │  │  │        │           ├─ cache-v2-8827bd33321171464298.json
│  │  │  │  │        │           ├─ cmakeFiles-v1-3837d7e40c0d101994d1.json
│  │  │  │  │        │           ├─ codemodel-v2-cba789b601aed6ec6db4.json
│  │  │  │  │        │           ├─ directory-.-Debug-d0094a50bb2071803777.json
│  │  │  │  │        │           ├─ directory-ReactNativeBlobUtilSpec_autolinked_build-Debug-4dff1583f330db125ee9.json
│  │  │  │  │        │           ├─ directory-rnasyncstorage_autolinked_build-Debug-1e080f56bfae790e50ec.json
│  │  │  │  │        │           ├─ directory-rngesturehandler_codegen_autolinked_build-Debug-52cb5462322c76d52fed.json
│  │  │  │  │        │           ├─ directory-rnpdf_autolinked_build-Debug-e96e0d61f0b4e5193a6d.json
│  │  │  │  │        │           ├─ directory-rnreanimated_autolinked_build-Debug-5728b3c51bf401bcbdfb.json
│  │  │  │  │        │           ├─ directory-rnscreens_autolinked_build-Debug-1a6aa31328e8e535fd84.json
│  │  │  │  │        │           ├─ directory-RNVectorIconsSpec_autolinked_build-Debug-17e087bd8d3124c615a3.json
│  │  │  │  │        │           ├─ directory-safeareacontext_autolinked_build-Debug-42cb9c95c87161281639.json
│  │  │  │  │        │           ├─ index-2025-05-19T07-52-44-0669.json
│  │  │  │  │        │           ├─ target-appmodules-Debug-2a421876125c775b8b43.json
│  │  │  │  │        │           ├─ target-react_codegen_ReactNativeBlobUtilSpec-Debug-14ededdbc784cd4c1810.json
│  │  │  │  │        │           ├─ target-react_codegen_rnasyncstorage-Debug-620fcbfb21cb455675b6.json
│  │  │  │  │        │           ├─ target-react_codegen_rngesturehandler_codegen-Debug-c6e1c3d49bfe04ad1485.json
│  │  │  │  │        │           ├─ target-react_codegen_rnpdf-Debug-6e431262800157b876b7.json
│  │  │  │  │        │           ├─ target-react_codegen_rnreanimated-Debug-2d41e6563119f2386c2e.json
│  │  │  │  │        │           ├─ target-react_codegen_rnscreens-Debug-027239535480128b1993.json
│  │  │  │  │        │           ├─ target-react_codegen_RNVectorIconsSpec-Debug-7d168b3792834298d259.json
│  │  │  │  │        │           └─ target-react_codegen_safeareacontext-Debug-6f5b2bb1f1492e292482.json
│  │  │  │  │        ├─ .ninja_deps
│  │  │  │  │        ├─ .ninja_log
│  │  │  │  │        ├─ additional_project_files.txt
│  │  │  │  │        ├─ android_gradle_build.json
│  │  │  │  │        ├─ android_gradle_build_mini.json
│  │  │  │  │        ├─ build.ninja
│  │  │  │  │        ├─ build_file_index.txt
│  │  │  │  │        ├─ CMakeCache.txt
│  │  │  │  │        ├─ CMakeFiles
│  │  │  │  │        │  ├─ 3.22.1-g37088a8-dirty
│  │  │  │  │        │  │  ├─ CMakeCCompiler.cmake
│  │  │  │  │        │  │  ├─ CMakeCXXCompiler.cmake
│  │  │  │  │        │  │  ├─ CMakeDetermineCompilerABI_C.bin
│  │  │  │  │        │  │  ├─ CMakeDetermineCompilerABI_CXX.bin
│  │  │  │  │        │  │  ├─ CMakeSystem.cmake
│  │  │  │  │        │  │  ├─ CompilerIdC
│  │  │  │  │        │  │  │  ├─ CMakeCCompilerId.c
│  │  │  │  │        │  │  │  ├─ CMakeCCompilerId.o
│  │  │  │  │        │  │  │  └─ tmp
│  │  │  │  │        │  │  └─ CompilerIdCXX
│  │  │  │  │        │  │     ├─ CMakeCXXCompilerId.cpp
│  │  │  │  │        │  │     ├─ CMakeCXXCompilerId.o
│  │  │  │  │        │  │     └─ tmp
│  │  │  │  │        │  ├─ appmodules.dir
│  │  │  │  │        │  │  ├─ C_
│  │  │  │  │        │  │  │  └─ Code
│  │  │  │  │        │  │  │     └─ nec-book-app
│  │  │  │  │        │  │  │        └─ android
│  │  │  │  │        │  │  │           └─ app
│  │  │  │  │        │  │  │              └─ build
│  │  │  │  │        │  │  │                 └─ generated
│  │  │  │  │        │  │  │                    └─ autolinking
│  │  │  │  │        │  │  │                       └─ src
│  │  │  │  │        │  │  │                          └─ main
│  │  │  │  │        │  │  │                             └─ jni
│  │  │  │  │        │  │  │                                └─ autolinking.cpp.o
│  │  │  │  │        │  │  └─ OnLoad.cpp.o
│  │  │  │  │        │  ├─ cmake.check_cache
│  │  │  │  │        │  ├─ cmake.verify_globs
│  │  │  │  │        │  ├─ CMakeOutput.log
│  │  │  │  │        │  ├─ CMakeTmp
│  │  │  │  │        │  ├─ rules.ninja
│  │  │  │  │        │  ├─ TargetDirectories.txt
│  │  │  │  │        │  └─ VerifyGlobs.cmake
│  │  │  │  │        ├─ cmake_install.cmake
│  │  │  │  │        ├─ compile_commands.json
│  │  │  │  │        ├─ compile_commands.json.bin
│  │  │  │  │        ├─ configure_fingerprint.bin
│  │  │  │  │        ├─ metadata_generation_command.txt
│  │  │  │  │        ├─ prefab_config.json
│  │  │  │  │        ├─ ReactNativeBlobUtilSpec_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_ReactNativeBlobUtilSpec.dir
│  │  │  │  │        │  │     ├─ react
│  │  │  │  │        │  │     │  └─ renderer
│  │  │  │  │        │  │     │     └─ components
│  │  │  │  │        │  │     │        └─ ReactNativeBlobUtilSpec
│  │  │  │  │        │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │           ├─ Props.cpp.o
│  │  │  │  │        │  │     │           ├─ ReactNativeBlobUtilSpecJSI-generated.cpp.o
│  │  │  │  │        │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │           └─ States.cpp.o
│  │  │  │  │        │  │     └─ ReactNativeBlobUtilSpec-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ rnasyncstorage_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_rnasyncstorage.dir
│  │  │  │  │        │  │     ├─ react
│  │  │  │  │        │  │     │  └─ renderer
│  │  │  │  │        │  │     │     └─ components
│  │  │  │  │        │  │     │        └─ rnasyncstorage
│  │  │  │  │        │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │           ├─ Props.cpp.o
│  │  │  │  │        │  │     │           ├─ rnasyncstorageJSI-generated.cpp.o
│  │  │  │  │        │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │           └─ States.cpp.o
│  │  │  │  │        │  │     └─ rnasyncstorage-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ rngesturehandler_codegen_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_rngesturehandler_codegen.dir
│  │  │  │  │        │  │     ├─ bac033cd950586cef66695376748dd33
│  │  │  │  │        │  │     │  └─ rngesturehandler_codegenJSI-generated.cpp.o
│  │  │  │  │        │  │     ├─ react
│  │  │  │  │        │  │     │  └─ renderer
│  │  │  │  │        │  │     │     └─ components
│  │  │  │  │        │  │     │        └─ rngesturehandler_codegen
│  │  │  │  │        │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │           ├─ Props.cpp.o
│  │  │  │  │        │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │           └─ States.cpp.o
│  │  │  │  │        │  │     └─ rngesturehandler_codegen-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ rnpdf_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_rnpdf.dir
│  │  │  │  │        │  │     ├─ react
│  │  │  │  │        │  │     │  └─ renderer
│  │  │  │  │        │  │     │     └─ components
│  │  │  │  │        │  │     │        └─ rnpdf
│  │  │  │  │        │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │           ├─ Props.cpp.o
│  │  │  │  │        │  │     │           ├─ rnpdfJSI-generated.cpp.o
│  │  │  │  │        │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │           └─ States.cpp.o
│  │  │  │  │        │  │     └─ rnpdf-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ rnreanimated_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_rnreanimated.dir
│  │  │  │  │        │  │     ├─ react
│  │  │  │  │        │  │     │  └─ renderer
│  │  │  │  │        │  │     │     └─ components
│  │  │  │  │        │  │     │        └─ rnreanimated
│  │  │  │  │        │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │           ├─ Props.cpp.o
│  │  │  │  │        │  │     │           ├─ rnreanimatedJSI-generated.cpp.o
│  │  │  │  │        │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │           └─ States.cpp.o
│  │  │  │  │        │  │     └─ rnreanimated-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ rnscreens_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_rnscreens.dir
│  │  │  │  │        │  │     ├─ 391f4a68aed65e0f0d78d3ea11250c82
│  │  │  │  │        │  │     │  └─ common
│  │  │  │  │        │  │     │     └─ cpp
│  │  │  │  │        │  │     │        └─ react
│  │  │  │  │        │  │     │           └─ renderer
│  │  │  │  │        │  │     │              └─ components
│  │  │  │  │        │  │     │                 └─ rnscreens
│  │  │  │  │        │  │     │                    ├─ RNSFullWindowOverlayShadowNode.cpp.o
│  │  │  │  │        │  │     │                    ├─ RNSModalScreenShadowNode.cpp.o
│  │  │  │  │        │  │     │                    ├─ RNSScreenShadowNode.cpp.o
│  │  │  │  │        │  │     │                    ├─ RNSScreenStackHeaderConfigShadowNode.cpp.o
│  │  │  │  │        │  │     │                    ├─ RNSScreenStackHeaderConfigState.cpp.o
│  │  │  │  │        │  │     │                    └─ RNSScreenStackHeaderSubviewState.cpp.o
│  │  │  │  │        │  │     ├─ 8a31dbcdf5039f0f2fa66c1dddf2dc23
│  │  │  │  │        │  │     │  └─ cpp
│  │  │  │  │        │  │     │     └─ react
│  │  │  │  │        │  │     │        └─ renderer
│  │  │  │  │        │  │     │           └─ components
│  │  │  │  │        │  │     │              └─ rnscreens
│  │  │  │  │        │  │     │                 └─ RNSScreenStackHeaderSubviewShadowNode.cpp.o
│  │  │  │  │        │  │     ├─ b3b0db3b5b0256c2f5b806fee963c037
│  │  │  │  │        │  │     │  └─ source
│  │  │  │  │        │  │     │     └─ codegen
│  │  │  │  │        │  │     │        └─ jni
│  │  │  │  │        │  │     │           └─ react
│  │  │  │  │        │  │     │              └─ renderer
│  │  │  │  │        │  │     │                 └─ components
│  │  │  │  │        │  │     │                    └─ rnscreens
│  │  │  │  │        │  │     │                       ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │                       └─ rnscreensJSI-generated.cpp.o
│  │  │  │  │        │  │     ├─ C_
│  │  │  │  │        │  │     │  └─ Code
│  │  │  │  │        │  │     │     └─ nec-book-app
│  │  │  │  │        │  │     ├─ d2526614ffd397f3aa77f5487a3a56fc
│  │  │  │  │        │  │     │  └─ generated
│  │  │  │  │        │  │     │     └─ source
│  │  │  │  │        │  │     │        └─ codegen
│  │  │  │  │        │  │     │           └─ jni
│  │  │  │  │        │  │     │              └─ react
│  │  │  │  │        │  │     │                 └─ renderer
│  │  │  │  │        │  │     │                    └─ components
│  │  │  │  │        │  │     │                       └─ rnscreens
│  │  │  │  │        │  │     │                          └─ EventEmitters.cpp.o
│  │  │  │  │        │  │     ├─ f3a08f4af0f7d908d38d8a678dc00767
│  │  │  │  │        │  │     │  └─ build
│  │  │  │  │        │  │     │     └─ generated
│  │  │  │  │        │  │     │        └─ source
│  │  │  │  │        │  │     │           └─ codegen
│  │  │  │  │        │  │     │              └─ jni
│  │  │  │  │        │  │     │                 └─ react
│  │  │  │  │        │  │     │                    └─ renderer
│  │  │  │  │        │  │     │                       └─ components
│  │  │  │  │        │  │     │                          └─ rnscreens
│  │  │  │  │        │  │     │                             ├─ Props.cpp.o
│  │  │  │  │        │  │     │                             ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │                             └─ States.cpp.o
│  │  │  │  │        │  │     └─ rnscreens.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ RNVectorIconsSpec_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_RNVectorIconsSpec.dir
│  │  │  │  │        │  │     ├─ react
│  │  │  │  │        │  │     │  └─ renderer
│  │  │  │  │        │  │     │     └─ components
│  │  │  │  │        │  │     │        └─ RNVectorIconsSpec
│  │  │  │  │        │  │     │           ├─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     │           ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │           ├─ Props.cpp.o
│  │  │  │  │        │  │     │           ├─ RNVectorIconsSpecJSI-generated.cpp.o
│  │  │  │  │        │  │     │           ├─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     │           └─ States.cpp.o
│  │  │  │  │        │  │     └─ RNVectorIconsSpec-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        ├─ safeareacontext_autolinked_build
│  │  │  │  │        │  ├─ CMakeFiles
│  │  │  │  │        │  │  └─ react_codegen_safeareacontext.dir
│  │  │  │  │        │  │     ├─ 9f6f6be174adebe3cd0c34ca495df0c7
│  │  │  │  │        │  │     │  └─ jni
│  │  │  │  │        │  │     │     └─ react
│  │  │  │  │        │  │     │        └─ renderer
│  │  │  │  │        │  │     │           └─ components
│  │  │  │  │        │  │     │              └─ safeareacontext
│  │  │  │  │        │  │     │                 └─ ComponentDescriptors.cpp.o
│  │  │  │  │        │  │     ├─ a1d3d0d7006545f905a8ea8373937a4d
│  │  │  │  │        │  │     │  └─ android
│  │  │  │  │        │  │     │     └─ build
│  │  │  │  │        │  │     │        └─ generated
│  │  │  │  │        │  │     │           └─ source
│  │  │  │  │        │  │     │              └─ codegen
│  │  │  │  │        │  │     │                 └─ jni
│  │  │  │  │        │  │     │                    └─ safeareacontext-generated.cpp.o
│  │  │  │  │        │  │     ├─ a773985f0f2e09e145f56a0b75e38e9b
│  │  │  │  │        │  │     │  └─ codegen
│  │  │  │  │        │  │     │     └─ jni
│  │  │  │  │        │  │     │        └─ react
│  │  │  │  │        │  │     │           └─ renderer
│  │  │  │  │        │  │     │              └─ components
│  │  │  │  │        │  │     │                 └─ safeareacontext
│  │  │  │  │        │  │     │                    ├─ EventEmitters.cpp.o
│  │  │  │  │        │  │     │                    └─ ShadowNodes.cpp.o
│  │  │  │  │        │  │     ├─ b744071d122ced8e068cecf0f5ca0d89
│  │  │  │  │        │  │     │  └─ cpp
│  │  │  │  │        │  │     │     └─ react
│  │  │  │  │        │  │     │        └─ renderer
│  │  │  │  │        │  │     │           └─ components
│  │  │  │  │        │  │     │              └─ safeareacontext
│  │  │  │  │        │  │     │                 ├─ RNCSafeAreaViewShadowNode.cpp.o
│  │  │  │  │        │  │     │                 └─ RNCSafeAreaViewState.cpp.o
│  │  │  │  │        │  │     ├─ c1b726b4478e52471b2f14dae633ebb7
│  │  │  │  │        │  │     │  └─ source
│  │  │  │  │        │  │     │     └─ codegen
│  │  │  │  │        │  │     │        └─ jni
│  │  │  │  │        │  │     │           └─ react
│  │  │  │  │        │  │     │              └─ renderer
│  │  │  │  │        │  │     │                 └─ components
│  │  │  │  │        │  │     │                    └─ safeareacontext
│  │  │  │  │        │  │     │                       ├─ Props.cpp.o
│  │  │  │  │        │  │     │                       └─ States.cpp.o
│  │  │  │  │        │  │     └─ fd8bc836bb836a7a1ab7dc250312be4a
│  │  │  │  │        │  │        └─ react
│  │  │  │  │        │  │           └─ renderer
│  │  │  │  │        │  │              └─ components
│  │  │  │  │        │  │                 └─ safeareacontext
│  │  │  │  │        │  │                    └─ safeareacontextJSI-generated.cpp.o
│  │  │  │  │        │  └─ cmake_install.cmake
│  │  │  │  │        └─ symbol_folder_index.txt
│  │  │  │  └─ tools
│  │  │  │     └─ debug
│  │  │  │        ├─ arm64-v8a
│  │  │  │        │  └─ compile_commands.json
│  │  │  │        ├─ armeabi-v7a
│  │  │  │        │  └─ compile_commands.json
│  │  │  │        ├─ x86
│  │  │  │        │  └─ compile_commands.json
│  │  │  │        └─ x86_64
│  │  │  │           └─ compile_commands.json
│  │  │  ├─ build
│  │  │  │  ├─ generated
│  │  │  │  │  ├─ ap_generated_sources
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ out
│  │  │  │  │  ├─ autolinking
│  │  │  │  │  │  └─ src
│  │  │  │  │  │     └─ main
│  │  │  │  │  │        ├─ java
│  │  │  │  │  │        │  └─ com
│  │  │  │  │  │        │     └─ facebook
│  │  │  │  │  │        │        └─ react
│  │  │  │  │  │        │           └─ PackageList.java
│  │  │  │  │  │        └─ jni
│  │  │  │  │  │           ├─ Android-autolinking.cmake
│  │  │  │  │  │           ├─ autolinking.cpp
│  │  │  │  │  │           └─ autolinking.h
│  │  │  │  │  ├─ res
│  │  │  │  │  │  ├─ pngs
│  │  │  │  │  │  │  └─ debug
│  │  │  │  │  │  └─ resValues
│  │  │  │  │  │     └─ debug
│  │  │  │  │  │        └─ values
│  │  │  │  │  │           └─ gradleResValues.xml
│  │  │  │  │  └─ source
│  │  │  │  │     └─ buildConfig
│  │  │  │  │        └─ debug
│  │  │  │  │           └─ com
│  │  │  │  │              └─ myapp
│  │  │  │  │                 └─ BuildConfig.java
│  │  │  │  ├─ intermediates
│  │  │  │  │  ├─ aar_metadata_check
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ checkDebugAarMetadata
│  │  │  │  │  ├─ annotation_processor_list
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ javaPreCompileDebug
│  │  │  │  │  │        └─ annotationProcessors.json
│  │  │  │  │  ├─ apk_ide_redirect_file
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ createDebugApkListingFileRedirect
│  │  │  │  │  │        └─ redirect.txt
│  │  │  │  │  ├─ app_metadata
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ writeDebugAppMetadata
│  │  │  │  │  │        └─ app-metadata.properties
│  │  │  │  │  ├─ assets
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugAssets
│  │  │  │  │  │        └─ fonts
│  │  │  │  │  │           ├─ AntDesign.ttf
│  │  │  │  │  │           ├─ Entypo.ttf
│  │  │  │  │  │           ├─ EvilIcons.ttf
│  │  │  │  │  │           ├─ Feather.ttf
│  │  │  │  │  │           ├─ FontAwesome.ttf
│  │  │  │  │  │           ├─ FontAwesome5_Brands.ttf
│  │  │  │  │  │           ├─ FontAwesome5_Regular.ttf
│  │  │  │  │  │           ├─ FontAwesome5_Solid.ttf
│  │  │  │  │  │           ├─ FontAwesome6_Brands.ttf
│  │  │  │  │  │           ├─ FontAwesome6_Regular.ttf
│  │  │  │  │  │           ├─ FontAwesome6_Solid.ttf
│  │  │  │  │  │           ├─ Fontisto.ttf
│  │  │  │  │  │           ├─ Foundation.ttf
│  │  │  │  │  │           ├─ Ionicons.ttf
│  │  │  │  │  │           ├─ MaterialCommunityIcons.ttf
│  │  │  │  │  │           ├─ MaterialIcons.ttf
│  │  │  │  │  │           ├─ Octicons.ttf
│  │  │  │  │  │           ├─ SimpleLineIcons.ttf
│  │  │  │  │  │           └─ Zocial.ttf
│  │  │  │  │  ├─ compatible_screen_manifest
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ createDebugCompatibleScreenManifests
│  │  │  │  │  │        └─ output-metadata.json
│  │  │  │  │  ├─ compile_and_runtime_not_namespaced_r_class_jar
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugResources
│  │  │  │  │  │        └─ R.jar
│  │  │  │  │  ├─ compressed_assets
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ compressDebugAssets
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           └─ assets
│  │  │  │  │  │              └─ fonts
│  │  │  │  │  │                 ├─ AntDesign.ttf.jar
│  │  │  │  │  │                 ├─ Entypo.ttf.jar
│  │  │  │  │  │                 ├─ EvilIcons.ttf.jar
│  │  │  │  │  │                 ├─ Feather.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome5_Brands.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome5_Regular.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome5_Solid.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome6_Brands.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome6_Regular.ttf.jar
│  │  │  │  │  │                 ├─ FontAwesome6_Solid.ttf.jar
│  │  │  │  │  │                 ├─ Fontisto.ttf.jar
│  │  │  │  │  │                 ├─ Foundation.ttf.jar
│  │  │  │  │  │                 ├─ Ionicons.ttf.jar
│  │  │  │  │  │                 ├─ MaterialCommunityIcons.ttf.jar
│  │  │  │  │  │                 ├─ MaterialIcons.ttf.jar
│  │  │  │  │  │                 ├─ Octicons.ttf.jar
│  │  │  │  │  │                 ├─ SimpleLineIcons.ttf.jar
│  │  │  │  │  │                 └─ Zocial.ttf.jar
│  │  │  │  │  ├─ cxx
│  │  │  │  │  │  ├─ Debug
│  │  │  │  │  │  │  └─ 266f2j4f
│  │  │  │  │  │  │     ├─ logs
│  │  │  │  │  │  │     │  ├─ arm64-v8a
│  │  │  │  │  │  │     │  │  ├─ build_command_appmodules.bat
│  │  │  │  │  │  │     │  │  ├─ build_command_targets.bat
│  │  │  │  │  │  │     │  │  ├─ build_model.json
│  │  │  │  │  │  │     │  │  ├─ build_stderr_appmodules.txt
│  │  │  │  │  │  │     │  │  ├─ build_stderr_targets.txt
│  │  │  │  │  │  │     │  │  ├─ build_stdout_appmodules.txt
│  │  │  │  │  │  │     │  │  ├─ build_stdout_targets.txt
│  │  │  │  │  │  │     │  │  ├─ configure_command.bat
│  │  │  │  │  │  │     │  │  ├─ configure_stderr.txt
│  │  │  │  │  │  │     │  │  ├─ configure_stdout.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10023_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10285_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1036_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1054_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10574_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10844_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11117_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11382_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11666_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11935_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12198_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1245_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12466_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1273_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12741_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1306_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13109_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13372_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_135_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13643_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13927_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14181_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14506_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_145_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_146_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_147_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14869_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_148_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_15151_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1521_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1694_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1790_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1962_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2050_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2320_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2589_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2718_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2867_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3104_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3132_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3412_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3418_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3693_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3744_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3950_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4021_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_410_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4304_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4584_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_477_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4843_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5113_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5377_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5670_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_591_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6050_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6316_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6585_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_699_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7088_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7352_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7605_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_771_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7882_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8168_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_828_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8428_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8703_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8953_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9221_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9480_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_956_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9757_timing.txt
│  │  │  │  │  │  │     │  │  ├─ metadata_generation_record.json
│  │  │  │  │  │  │     │  │  ├─ prefab_command.bat
│  │  │  │  │  │  │     │  │  ├─ prefab_stderr.txt
│  │  │  │  │  │  │     │  │  └─ prefab_stdout.txt
│  │  │  │  │  │  │     │  ├─ armeabi-v7a
│  │  │  │  │  │  │     │  │  ├─ build_command_appmodules.bat
│  │  │  │  │  │  │     │  │  ├─ build_command_targets.bat
│  │  │  │  │  │  │     │  │  ├─ build_model.json
│  │  │  │  │  │  │     │  │  ├─ build_stderr_appmodules.txt
│  │  │  │  │  │  │     │  │  ├─ build_stderr_targets.txt
│  │  │  │  │  │  │     │  │  ├─ build_stdout_appmodules.txt
│  │  │  │  │  │  │     │  │  ├─ build_stdout_targets.txt
│  │  │  │  │  │  │     │  │  ├─ configure_command.bat
│  │  │  │  │  │  │     │  │  ├─ configure_stderr.txt
│  │  │  │  │  │  │     │  │  ├─ configure_stdout.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10024_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10302_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1036_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1054_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10569_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10844_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11121_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11390_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11652_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11932_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12186_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1245_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12472_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1272_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12737_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1310_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13119_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13372_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13643_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13910_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_139_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14187_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14514_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_146_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14882_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_148_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_150_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1511_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_15152_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_151_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1694_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1790_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1975_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2056_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2331_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2596_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2728_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2861_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3105_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3143_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3419_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3420_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3680_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3744_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3966_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4008_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_410_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4304_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4567_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_477_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4843_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5113_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5391_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5656_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_591_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6048_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6313_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6580_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_699_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7088_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7354_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7620_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_771_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7885_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8152_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_828_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8425_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8702_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8950_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9220_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9498_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_956_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9764_timing.txt
│  │  │  │  │  │  │     │  │  ├─ metadata_generation_record.json
│  │  │  │  │  │  │     │  │  ├─ prefab_command.bat
│  │  │  │  │  │  │     │  │  ├─ prefab_stderr.txt
│  │  │  │  │  │  │     │  │  └─ prefab_stdout.txt
│  │  │  │  │  │  │     │  ├─ x86
│  │  │  │  │  │  │     │  │  ├─ build_command_appmodules.bat
│  │  │  │  │  │  │     │  │  ├─ build_command_targets.bat
│  │  │  │  │  │  │     │  │  ├─ build_model.json
│  │  │  │  │  │  │     │  │  ├─ build_stderr_appmodules.txt
│  │  │  │  │  │  │     │  │  ├─ build_stderr_targets.txt
│  │  │  │  │  │  │     │  │  ├─ build_stdout_appmodules.txt
│  │  │  │  │  │  │     │  │  ├─ build_stdout_targets.txt
│  │  │  │  │  │  │     │  │  ├─ configure_command.bat
│  │  │  │  │  │  │     │  │  ├─ configure_stderr.txt
│  │  │  │  │  │  │     │  │  ├─ configure_stdout.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10024_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10302_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1036_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1054_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10569_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_10844_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11121_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11381_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11652_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_11932_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12186_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1245_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12469_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_12730_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1285_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13101_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1310_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13372_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13643_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_13910_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_139_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_140_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14180_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14514_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_146_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_14882_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_148_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1511_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_15160_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_151_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1694_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1790_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_1975_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2045_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2330_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2596_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2711_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_2877_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3089_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3138_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3421_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3435_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3697_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3744_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_3966_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4008_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_410_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4304_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4567_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_477_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_4843_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5121_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5391_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_5656_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_591_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6048_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6322_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_6580_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_699_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7088_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7352_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7620_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_771_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_7891_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8152_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_828_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8432_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8702_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_8950_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9220_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9494_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_956_timing.txt
│  │  │  │  │  │  │     │  │  ├─ generate_cxx_metadata_9765_timing.txt
│  │  │  │  │  │  │     │  │  ├─ metadata_generation_record.json
│  │  │  │  │  │  │     │  │  ├─ prefab_command.bat
│  │  │  │  │  │  │     │  │  ├─ prefab_stderr.txt
│  │  │  │  │  │  │     │  │  └─ prefab_stdout.txt
│  │  │  │  │  │  │     │  └─ x86_64
│  │  │  │  │  │  │     │     ├─ build_command_appmodules.bat
│  │  │  │  │  │  │     │     ├─ build_command_targets.bat
│  │  │  │  │  │  │     │     ├─ build_model.json
│  │  │  │  │  │  │     │     ├─ build_stderr_appmodules.txt
│  │  │  │  │  │  │     │     ├─ build_stderr_targets.txt
│  │  │  │  │  │  │     │     ├─ build_stdout_appmodules.txt
│  │  │  │  │  │  │     │     ├─ build_stdout_targets.txt
│  │  │  │  │  │  │     │     ├─ configure_command.bat
│  │  │  │  │  │  │     │     ├─ configure_stderr.txt
│  │  │  │  │  │  │     │     ├─ configure_stdout.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_10024_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_10291_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1036_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1054_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_10569_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_10844_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_11121_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_11381_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_11652_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_11932_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_12193_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1245_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_12469_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_12730_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1285_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_130_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_13101_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1310_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_13372_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_13643_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_13923_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_14180_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_14514_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_146_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_14882_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_148_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1511_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_15160_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_151_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1694_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1790_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_1975_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_2041_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_2330_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_2596_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_2721_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_2877_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3091_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3138_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3416_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3435_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3697_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3744_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_3966_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_4008_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_410_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_4304_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_4567_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_476_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_4843_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_5110_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_5383_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_5656_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_591_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_6048_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_6313_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_6580_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_699_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_7096_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_7352_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_7604_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_777_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_7891_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_8164_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_828_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_8418_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_8702_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_8963_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_9229_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_9494_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_956_timing.txt
│  │  │  │  │  │  │     │     ├─ generate_cxx_metadata_9768_timing.txt
│  │  │  │  │  │  │     │     ├─ metadata_generation_record.json
│  │  │  │  │  │  │     │     ├─ prefab_command.bat
│  │  │  │  │  │  │     │     ├─ prefab_stderr.txt
│  │  │  │  │  │  │     │     └─ prefab_stdout.txt
│  │  │  │  │  │  │     └─ obj
│  │  │  │  │  │  │        ├─ arm64-v8a
│  │  │  │  │  │  │        │  ├─ libappmodules.so
│  │  │  │  │  │  │        │  ├─ libc++_shared.so
│  │  │  │  │  │  │        │  ├─ libfbjni.so
│  │  │  │  │  │  │        │  ├─ libjsi.so
│  │  │  │  │  │  │        │  ├─ libreactnative.so
│  │  │  │  │  │  │        │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │  │        │  └─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │  │        ├─ armeabi-v7a
│  │  │  │  │  │  │        │  ├─ libappmodules.so
│  │  │  │  │  │  │        │  ├─ libc++_shared.so
│  │  │  │  │  │  │        │  ├─ libfbjni.so
│  │  │  │  │  │  │        │  ├─ libjsi.so
│  │  │  │  │  │  │        │  ├─ libreactnative.so
│  │  │  │  │  │  │        │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │  │        │  └─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │  │        ├─ x86
│  │  │  │  │  │  │        │  ├─ libappmodules.so
│  │  │  │  │  │  │        │  ├─ libc++_shared.so
│  │  │  │  │  │  │        │  ├─ libfbjni.so
│  │  │  │  │  │  │        │  ├─ libjsi.so
│  │  │  │  │  │  │        │  ├─ libreactnative.so
│  │  │  │  │  │  │        │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │  │        │  └─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │  │        └─ x86_64
│  │  │  │  │  │  │           ├─ libappmodules.so
│  │  │  │  │  │  │           ├─ libc++_shared.so
│  │  │  │  │  │  │           ├─ libfbjni.so
│  │  │  │  │  │  │           ├─ libjsi.so
│  │  │  │  │  │  │           ├─ libreactnative.so
│  │  │  │  │  │  │           ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │  │           └─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │  └─ refs
│  │  │  │  │  │     └─ react-native-reanimated
│  │  │  │  │  │        ├─ 1jm4116k
│  │  │  │  │  │        │  ├─ modules
│  │  │  │  │  │        │  │  ├─ reanimated
│  │  │  │  │  │        │  │  │  ├─ include
│  │  │  │  │  │        │  │  │  │  └─ placeholder.txt
│  │  │  │  │  │        │  │  │  ├─ libs
│  │  │  │  │  │        │  │  │  │  └─ android.x86
│  │  │  │  │  │        │  │  │  │     └─ abi.json
│  │  │  │  │  │        │  │  │  └─ module.json
│  │  │  │  │  │        │  │  └─ worklets
│  │  │  │  │  │        │  │     ├─ include
│  │  │  │  │  │        │  │     │  └─ placeholder.txt
│  │  │  │  │  │        │  │     ├─ libs
│  │  │  │  │  │        │  │     │  └─ android.x86
│  │  │  │  │  │        │  │     │     └─ abi.json
│  │  │  │  │  │        │  │     └─ module.json
│  │  │  │  │  │        │  ├─ prefab.json
│  │  │  │  │  │        │  └─ prefab_publication.json
│  │  │  │  │  │        ├─ 443px54k
│  │  │  │  │  │        │  ├─ modules
│  │  │  │  │  │        │  │  ├─ reanimated
│  │  │  │  │  │        │  │  │  ├─ include
│  │  │  │  │  │        │  │  │  │  └─ placeholder.txt
│  │  │  │  │  │        │  │  │  ├─ libs
│  │  │  │  │  │        │  │  │  │  └─ android.x86_64
│  │  │  │  │  │        │  │  │  │     └─ abi.json
│  │  │  │  │  │        │  │  │  └─ module.json
│  │  │  │  │  │        │  │  └─ worklets
│  │  │  │  │  │        │  │     ├─ include
│  │  │  │  │  │        │  │     │  └─ placeholder.txt
│  │  │  │  │  │        │  │     ├─ libs
│  │  │  │  │  │        │  │     │  └─ android.x86_64
│  │  │  │  │  │        │  │     │     └─ abi.json
│  │  │  │  │  │        │  │     └─ module.json
│  │  │  │  │  │        │  ├─ prefab.json
│  │  │  │  │  │        │  └─ prefab_publication.json
│  │  │  │  │  │        ├─ 4fo53j2i
│  │  │  │  │  │        │  ├─ modules
│  │  │  │  │  │        │  │  ├─ reanimated
│  │  │  │  │  │        │  │  │  ├─ include
│  │  │  │  │  │        │  │  │  │  └─ placeholder.txt
│  │  │  │  │  │        │  │  │  ├─ libs
│  │  │  │  │  │        │  │  │  │  └─ android.arm64-v8a
│  │  │  │  │  │        │  │  │  │     └─ abi.json
│  │  │  │  │  │        │  │  │  └─ module.json
│  │  │  │  │  │        │  │  └─ worklets
│  │  │  │  │  │        │  │     ├─ include
│  │  │  │  │  │        │  │     │  └─ placeholder.txt
│  │  │  │  │  │        │  │     ├─ libs
│  │  │  │  │  │        │  │     │  └─ android.arm64-v8a
│  │  │  │  │  │        │  │     │     └─ abi.json
│  │  │  │  │  │        │  │     └─ module.json
│  │  │  │  │  │        │  ├─ prefab.json
│  │  │  │  │  │        │  └─ prefab_publication.json
│  │  │  │  │  │        └─ x3a263p5
│  │  │  │  │  │           ├─ modules
│  │  │  │  │  │           │  ├─ reanimated
│  │  │  │  │  │           │  │  ├─ include
│  │  │  │  │  │           │  │  │  └─ placeholder.txt
│  │  │  │  │  │           │  │  ├─ libs
│  │  │  │  │  │           │  │  │  └─ android.armeabi-v7a
│  │  │  │  │  │           │  │  │     └─ abi.json
│  │  │  │  │  │           │  │  └─ module.json
│  │  │  │  │  │           │  └─ worklets
│  │  │  │  │  │           │     ├─ include
│  │  │  │  │  │           │     │  └─ placeholder.txt
│  │  │  │  │  │           │     ├─ libs
│  │  │  │  │  │           │     │  └─ android.armeabi-v7a
│  │  │  │  │  │           │     │     └─ abi.json
│  │  │  │  │  │           │     └─ module.json
│  │  │  │  │  │           ├─ prefab.json
│  │  │  │  │  │           └─ prefab_publication.json
│  │  │  │  │  ├─ data_binding_layout_info_type_merge
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugResources
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ data_binding_layout_info_type_package
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ packageDebugResources
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ desugar_graph
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           ├─ currentProject
│  │  │  │  │  │           │  ├─ dirs_bucket_0
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_1
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_2
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_3
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_4
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_5
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_6
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_7
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_8
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ dirs_bucket_9
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_0
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_1
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_2
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_3
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_4
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_5
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_6
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_7
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  ├─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_8
│  │  │  │  │  │           │  │  └─ graph.bin
│  │  │  │  │  │           │  └─ jar_4434536ad05b3bdaf20d61a10ab75aed4b02f79db956ab9f1eb915be57169783_bucket_9
│  │  │  │  │  │           │     └─ graph.bin
│  │  │  │  │  │           ├─ externalLibs
│  │  │  │  │  │           ├─ mixedScopes
│  │  │  │  │  │           └─ otherProjects
│  │  │  │  │  ├─ dex
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     ├─ mergeExtDexDebug
│  │  │  │  │  │     │  ├─ classes.dex
│  │  │  │  │  │     │  └─ classes2.dex
│  │  │  │  │  │     ├─ mergeLibDexDebug
│  │  │  │  │  │     │  ├─ 0
│  │  │  │  │  │     │  ├─ 1
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 10
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 11
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 12
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 13
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 14
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 15
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 2
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 3
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 4
│  │  │  │  │  │     │  ├─ 5
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 6
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 7
│  │  │  │  │  │     │  │  └─ classes.dex
│  │  │  │  │  │     │  ├─ 8
│  │  │  │  │  │     │  └─ 9
│  │  │  │  │  │     │     └─ classes.dex
│  │  │  │  │  │     └─ mergeProjectDexDebug
│  │  │  │  │  │        ├─ 0
│  │  │  │  │  │        │  └─ classes.dex
│  │  │  │  │  │        ├─ 1
│  │  │  │  │  │        ├─ 10
│  │  │  │  │  │        │  └─ classes.dex
│  │  │  │  │  │        ├─ 11
│  │  │  │  │  │        ├─ 12
│  │  │  │  │  │        ├─ 13
│  │  │  │  │  │        ├─ 14
│  │  │  │  │  │        │  └─ classes.dex
│  │  │  │  │  │        ├─ 15
│  │  │  │  │  │        ├─ 2
│  │  │  │  │  │        ├─ 3
│  │  │  │  │  │        ├─ 4
│  │  │  │  │  │        ├─ 5
│  │  │  │  │  │        ├─ 6
│  │  │  │  │  │        ├─ 7
│  │  │  │  │  │        ├─ 8
│  │  │  │  │  │        └─ 9
│  │  │  │  │  ├─ dex_archive_input_jar_hashes
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ dex_number_of_buckets_file
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ duplicate_classes_check
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ checkDebugDuplicateClasses
│  │  │  │  │  ├─ external_file_lib_dex_archives
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ desugarDebugFileDependencies
│  │  │  │  │  ├─ external_libs_dex_archive
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ external_libs_dex_archive_with_artifact_transforms
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ global_synthetics_dex
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugGlobalSynthetics
│  │  │  │  │  ├─ global_synthetics_external_lib
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ global_synthetics_external_libs_artifact_transform
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ global_synthetics_file_lib
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ desugarDebugFileDependencies
│  │  │  │  │  ├─ global_synthetics_mixed_scope
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ global_synthetics_project
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ global_synthetics_subproject
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ incremental
│  │  │  │  │  │  ├─ debug
│  │  │  │  │  │  │  ├─ mergeDebugResources
│  │  │  │  │  │  │  │  ├─ compile-file-map.properties
│  │  │  │  │  │  │  │  ├─ merged.dir
│  │  │  │  │  │  │  │  │  ├─ values
│  │  │  │  │  │  │  │  │  │  └─ values.xml
│  │  │  │  │  │  │  │  │  ├─ values-af
│  │  │  │  │  │  │  │  │  │  └─ values-af.xml
│  │  │  │  │  │  │  │  │  ├─ values-am
│  │  │  │  │  │  │  │  │  │  └─ values-am.xml
│  │  │  │  │  │  │  │  │  ├─ values-ar
│  │  │  │  │  │  │  │  │  │  └─ values-ar.xml
│  │  │  │  │  │  │  │  │  ├─ values-as
│  │  │  │  │  │  │  │  │  │  └─ values-as.xml
│  │  │  │  │  │  │  │  │  ├─ values-az
│  │  │  │  │  │  │  │  │  │  └─ values-az.xml
│  │  │  │  │  │  │  │  │  ├─ values-b+es+419
│  │  │  │  │  │  │  │  │  │  └─ values-b+es+419.xml
│  │  │  │  │  │  │  │  │  ├─ values-b+sr+Latn
│  │  │  │  │  │  │  │  │  │  └─ values-b+sr+Latn.xml
│  │  │  │  │  │  │  │  │  ├─ values-be
│  │  │  │  │  │  │  │  │  │  └─ values-be.xml
│  │  │  │  │  │  │  │  │  ├─ values-bg
│  │  │  │  │  │  │  │  │  │  └─ values-bg.xml
│  │  │  │  │  │  │  │  │  ├─ values-bn
│  │  │  │  │  │  │  │  │  │  └─ values-bn.xml
│  │  │  │  │  │  │  │  │  ├─ values-bs
│  │  │  │  │  │  │  │  │  │  └─ values-bs.xml
│  │  │  │  │  │  │  │  │  ├─ values-ca
│  │  │  │  │  │  │  │  │  │  └─ values-ca.xml
│  │  │  │  │  │  │  │  │  ├─ values-cs
│  │  │  │  │  │  │  │  │  │  └─ values-cs.xml
│  │  │  │  │  │  │  │  │  ├─ values-da
│  │  │  │  │  │  │  │  │  │  └─ values-da.xml
│  │  │  │  │  │  │  │  │  ├─ values-de
│  │  │  │  │  │  │  │  │  │  └─ values-de.xml
│  │  │  │  │  │  │  │  │  ├─ values-el
│  │  │  │  │  │  │  │  │  │  └─ values-el.xml
│  │  │  │  │  │  │  │  │  ├─ values-en-rAU
│  │  │  │  │  │  │  │  │  │  └─ values-en-rAU.xml
│  │  │  │  │  │  │  │  │  ├─ values-en-rCA
│  │  │  │  │  │  │  │  │  │  └─ values-en-rCA.xml
│  │  │  │  │  │  │  │  │  ├─ values-en-rGB
│  │  │  │  │  │  │  │  │  │  └─ values-en-rGB.xml
│  │  │  │  │  │  │  │  │  ├─ values-en-rIN
│  │  │  │  │  │  │  │  │  │  └─ values-en-rIN.xml
│  │  │  │  │  │  │  │  │  ├─ values-en-rXC
│  │  │  │  │  │  │  │  │  │  └─ values-en-rXC.xml
│  │  │  │  │  │  │  │  │  ├─ values-es
│  │  │  │  │  │  │  │  │  │  └─ values-es.xml
│  │  │  │  │  │  │  │  │  ├─ values-es-rES
│  │  │  │  │  │  │  │  │  │  └─ values-es-rES.xml
│  │  │  │  │  │  │  │  │  ├─ values-es-rUS
│  │  │  │  │  │  │  │  │  │  └─ values-es-rUS.xml
│  │  │  │  │  │  │  │  │  ├─ values-et
│  │  │  │  │  │  │  │  │  │  └─ values-et.xml
│  │  │  │  │  │  │  │  │  ├─ values-eu
│  │  │  │  │  │  │  │  │  │  └─ values-eu.xml
│  │  │  │  │  │  │  │  │  ├─ values-fa
│  │  │  │  │  │  │  │  │  │  └─ values-fa.xml
│  │  │  │  │  │  │  │  │  ├─ values-fi
│  │  │  │  │  │  │  │  │  │  └─ values-fi.xml
│  │  │  │  │  │  │  │  │  ├─ values-fr
│  │  │  │  │  │  │  │  │  │  └─ values-fr.xml
│  │  │  │  │  │  │  │  │  ├─ values-fr-rCA
│  │  │  │  │  │  │  │  │  │  └─ values-fr-rCA.xml
│  │  │  │  │  │  │  │  │  ├─ values-gl
│  │  │  │  │  │  │  │  │  │  └─ values-gl.xml
│  │  │  │  │  │  │  │  │  ├─ values-gu
│  │  │  │  │  │  │  │  │  │  └─ values-gu.xml
│  │  │  │  │  │  │  │  │  ├─ values-h320dp-port-v13
│  │  │  │  │  │  │  │  │  │  └─ values-h320dp-port-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-h360dp-land-v13
│  │  │  │  │  │  │  │  │  │  └─ values-h360dp-land-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-h480dp-land-v13
│  │  │  │  │  │  │  │  │  │  └─ values-h480dp-land-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-h550dp-port-v13
│  │  │  │  │  │  │  │  │  │  └─ values-h550dp-port-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-h720dp-v13
│  │  │  │  │  │  │  │  │  │  └─ values-h720dp-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-hdpi-v4
│  │  │  │  │  │  │  │  │  │  └─ values-hdpi-v4.xml
│  │  │  │  │  │  │  │  │  ├─ values-hi
│  │  │  │  │  │  │  │  │  │  └─ values-hi.xml
│  │  │  │  │  │  │  │  │  ├─ values-hr
│  │  │  │  │  │  │  │  │  │  └─ values-hr.xml
│  │  │  │  │  │  │  │  │  ├─ values-hu
│  │  │  │  │  │  │  │  │  │  └─ values-hu.xml
│  │  │  │  │  │  │  │  │  ├─ values-hy
│  │  │  │  │  │  │  │  │  │  └─ values-hy.xml
│  │  │  │  │  │  │  │  │  ├─ values-in
│  │  │  │  │  │  │  │  │  │  └─ values-in.xml
│  │  │  │  │  │  │  │  │  ├─ values-is
│  │  │  │  │  │  │  │  │  │  └─ values-is.xml
│  │  │  │  │  │  │  │  │  ├─ values-it
│  │  │  │  │  │  │  │  │  │  └─ values-it.xml
│  │  │  │  │  │  │  │  │  ├─ values-iw
│  │  │  │  │  │  │  │  │  │  └─ values-iw.xml
│  │  │  │  │  │  │  │  │  ├─ values-ja
│  │  │  │  │  │  │  │  │  │  └─ values-ja.xml
│  │  │  │  │  │  │  │  │  ├─ values-ka
│  │  │  │  │  │  │  │  │  │  └─ values-ka.xml
│  │  │  │  │  │  │  │  │  ├─ values-kk
│  │  │  │  │  │  │  │  │  │  └─ values-kk.xml
│  │  │  │  │  │  │  │  │  ├─ values-km
│  │  │  │  │  │  │  │  │  │  └─ values-km.xml
│  │  │  │  │  │  │  │  │  ├─ values-kn
│  │  │  │  │  │  │  │  │  │  └─ values-kn.xml
│  │  │  │  │  │  │  │  │  ├─ values-ko
│  │  │  │  │  │  │  │  │  │  └─ values-ko.xml
│  │  │  │  │  │  │  │  │  ├─ values-ky
│  │  │  │  │  │  │  │  │  │  └─ values-ky.xml
│  │  │  │  │  │  │  │  │  ├─ values-land
│  │  │  │  │  │  │  │  │  │  └─ values-land.xml
│  │  │  │  │  │  │  │  │  ├─ values-large-v4
│  │  │  │  │  │  │  │  │  │  └─ values-large-v4.xml
│  │  │  │  │  │  │  │  │  ├─ values-ldltr-v21
│  │  │  │  │  │  │  │  │  │  └─ values-ldltr-v21.xml
│  │  │  │  │  │  │  │  │  ├─ values-ldrtl-v17
│  │  │  │  │  │  │  │  │  │  └─ values-ldrtl-v17.xml
│  │  │  │  │  │  │  │  │  ├─ values-lo
│  │  │  │  │  │  │  │  │  │  └─ values-lo.xml
│  │  │  │  │  │  │  │  │  ├─ values-lt
│  │  │  │  │  │  │  │  │  │  └─ values-lt.xml
│  │  │  │  │  │  │  │  │  ├─ values-lv
│  │  │  │  │  │  │  │  │  │  └─ values-lv.xml
│  │  │  │  │  │  │  │  │  ├─ values-mk
│  │  │  │  │  │  │  │  │  │  └─ values-mk.xml
│  │  │  │  │  │  │  │  │  ├─ values-ml
│  │  │  │  │  │  │  │  │  │  └─ values-ml.xml
│  │  │  │  │  │  │  │  │  ├─ values-mn
│  │  │  │  │  │  │  │  │  │  └─ values-mn.xml
│  │  │  │  │  │  │  │  │  ├─ values-mr
│  │  │  │  │  │  │  │  │  │  └─ values-mr.xml
│  │  │  │  │  │  │  │  │  ├─ values-ms
│  │  │  │  │  │  │  │  │  │  └─ values-ms.xml
│  │  │  │  │  │  │  │  │  ├─ values-my
│  │  │  │  │  │  │  │  │  │  └─ values-my.xml
│  │  │  │  │  │  │  │  │  ├─ values-nb
│  │  │  │  │  │  │  │  │  │  └─ values-nb.xml
│  │  │  │  │  │  │  │  │  ├─ values-ne
│  │  │  │  │  │  │  │  │  │  └─ values-ne.xml
│  │  │  │  │  │  │  │  │  ├─ values-night-v8
│  │  │  │  │  │  │  │  │  │  └─ values-night-v8.xml
│  │  │  │  │  │  │  │  │  ├─ values-nl
│  │  │  │  │  │  │  │  │  │  └─ values-nl.xml
│  │  │  │  │  │  │  │  │  ├─ values-or
│  │  │  │  │  │  │  │  │  │  └─ values-or.xml
│  │  │  │  │  │  │  │  │  ├─ values-pa
│  │  │  │  │  │  │  │  │  │  └─ values-pa.xml
│  │  │  │  │  │  │  │  │  ├─ values-pl
│  │  │  │  │  │  │  │  │  │  └─ values-pl.xml
│  │  │  │  │  │  │  │  │  ├─ values-port
│  │  │  │  │  │  │  │  │  │  └─ values-port.xml
│  │  │  │  │  │  │  │  │  ├─ values-pt
│  │  │  │  │  │  │  │  │  │  └─ values-pt.xml
│  │  │  │  │  │  │  │  │  ├─ values-pt-rBR
│  │  │  │  │  │  │  │  │  │  └─ values-pt-rBR.xml
│  │  │  │  │  │  │  │  │  ├─ values-pt-rPT
│  │  │  │  │  │  │  │  │  │  └─ values-pt-rPT.xml
│  │  │  │  │  │  │  │  │  ├─ values-ro
│  │  │  │  │  │  │  │  │  │  └─ values-ro.xml
│  │  │  │  │  │  │  │  │  ├─ values-ru
│  │  │  │  │  │  │  │  │  │  └─ values-ru.xml
│  │  │  │  │  │  │  │  │  ├─ values-si
│  │  │  │  │  │  │  │  │  │  └─ values-si.xml
│  │  │  │  │  │  │  │  │  ├─ values-sk
│  │  │  │  │  │  │  │  │  │  └─ values-sk.xml
│  │  │  │  │  │  │  │  │  ├─ values-sl
│  │  │  │  │  │  │  │  │  │  └─ values-sl.xml
│  │  │  │  │  │  │  │  │  ├─ values-small-v4
│  │  │  │  │  │  │  │  │  │  └─ values-small-v4.xml
│  │  │  │  │  │  │  │  │  ├─ values-sq
│  │  │  │  │  │  │  │  │  │  └─ values-sq.xml
│  │  │  │  │  │  │  │  │  ├─ values-sr
│  │  │  │  │  │  │  │  │  │  └─ values-sr.xml
│  │  │  │  │  │  │  │  │  ├─ values-sv
│  │  │  │  │  │  │  │  │  │  └─ values-sv.xml
│  │  │  │  │  │  │  │  │  ├─ values-sw
│  │  │  │  │  │  │  │  │  │  └─ values-sw.xml
│  │  │  │  │  │  │  │  │  ├─ values-sw600dp-v13
│  │  │  │  │  │  │  │  │  │  └─ values-sw600dp-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-ta
│  │  │  │  │  │  │  │  │  │  └─ values-ta.xml
│  │  │  │  │  │  │  │  │  ├─ values-te
│  │  │  │  │  │  │  │  │  │  └─ values-te.xml
│  │  │  │  │  │  │  │  │  ├─ values-th
│  │  │  │  │  │  │  │  │  │  └─ values-th.xml
│  │  │  │  │  │  │  │  │  ├─ values-tl
│  │  │  │  │  │  │  │  │  │  └─ values-tl.xml
│  │  │  │  │  │  │  │  │  ├─ values-tr
│  │  │  │  │  │  │  │  │  │  └─ values-tr.xml
│  │  │  │  │  │  │  │  │  ├─ values-uk
│  │  │  │  │  │  │  │  │  │  └─ values-uk.xml
│  │  │  │  │  │  │  │  │  ├─ values-ur
│  │  │  │  │  │  │  │  │  │  └─ values-ur.xml
│  │  │  │  │  │  │  │  │  ├─ values-uz
│  │  │  │  │  │  │  │  │  │  └─ values-uz.xml
│  │  │  │  │  │  │  │  │  ├─ values-v16
│  │  │  │  │  │  │  │  │  │  └─ values-v16.xml
│  │  │  │  │  │  │  │  │  ├─ values-v17
│  │  │  │  │  │  │  │  │  │  └─ values-v17.xml
│  │  │  │  │  │  │  │  │  ├─ values-v18
│  │  │  │  │  │  │  │  │  │  └─ values-v18.xml
│  │  │  │  │  │  │  │  │  ├─ values-v21
│  │  │  │  │  │  │  │  │  │  └─ values-v21.xml
│  │  │  │  │  │  │  │  │  ├─ values-v22
│  │  │  │  │  │  │  │  │  │  └─ values-v22.xml
│  │  │  │  │  │  │  │  │  ├─ values-v23
│  │  │  │  │  │  │  │  │  │  └─ values-v23.xml
│  │  │  │  │  │  │  │  │  ├─ values-v24
│  │  │  │  │  │  │  │  │  │  └─ values-v24.xml
│  │  │  │  │  │  │  │  │  ├─ values-v25
│  │  │  │  │  │  │  │  │  │  └─ values-v25.xml
│  │  │  │  │  │  │  │  │  ├─ values-v26
│  │  │  │  │  │  │  │  │  │  └─ values-v26.xml
│  │  │  │  │  │  │  │  │  ├─ values-v28
│  │  │  │  │  │  │  │  │  │  └─ values-v28.xml
│  │  │  │  │  │  │  │  │  ├─ values-v31
│  │  │  │  │  │  │  │  │  │  └─ values-v31.xml
│  │  │  │  │  │  │  │  │  ├─ values-vi
│  │  │  │  │  │  │  │  │  │  └─ values-vi.xml
│  │  │  │  │  │  │  │  │  ├─ values-w320dp-land-v13
│  │  │  │  │  │  │  │  │  │  └─ values-w320dp-land-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-w360dp-port-v13
│  │  │  │  │  │  │  │  │  │  └─ values-w360dp-port-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-w480dp-port-v13
│  │  │  │  │  │  │  │  │  │  └─ values-w480dp-port-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-w600dp-land-v13
│  │  │  │  │  │  │  │  │  │  └─ values-w600dp-land-v13.xml
│  │  │  │  │  │  │  │  │  ├─ values-watch-v20
│  │  │  │  │  │  │  │  │  │  └─ values-watch-v20.xml
│  │  │  │  │  │  │  │  │  ├─ values-watch-v21
│  │  │  │  │  │  │  │  │  │  └─ values-watch-v21.xml
│  │  │  │  │  │  │  │  │  ├─ values-xlarge-v4
│  │  │  │  │  │  │  │  │  │  └─ values-xlarge-v4.xml
│  │  │  │  │  │  │  │  │  ├─ values-zh-rCN
│  │  │  │  │  │  │  │  │  │  └─ values-zh-rCN.xml
│  │  │  │  │  │  │  │  │  ├─ values-zh-rHK
│  │  │  │  │  │  │  │  │  │  └─ values-zh-rHK.xml
│  │  │  │  │  │  │  │  │  ├─ values-zh-rTW
│  │  │  │  │  │  │  │  │  │  └─ values-zh-rTW.xml
│  │  │  │  │  │  │  │  │  └─ values-zu
│  │  │  │  │  │  │  │  │     └─ values-zu.xml
│  │  │  │  │  │  │  │  ├─ merger.xml
│  │  │  │  │  │  │  │  └─ stripped.dir
│  │  │  │  │  │  │  └─ packageDebugResources
│  │  │  │  │  │  │     ├─ compile-file-map.properties
│  │  │  │  │  │  │     ├─ merged.dir
│  │  │  │  │  │  │     │  └─ values
│  │  │  │  │  │  │     │     └─ values.xml
│  │  │  │  │  │  │     ├─ merger.xml
│  │  │  │  │  │  │     └─ stripped.dir
│  │  │  │  │  │  ├─ debug-mergeJavaRes
│  │  │  │  │  │  │  ├─ merge-state
│  │  │  │  │  │  │  └─ zip-cache
│  │  │  │  │  │  │     ├─ +fH9OiCnro+cH9lvd04EKySvwtE=
│  │  │  │  │  │  │     ├─ +XW6c7C7d0Gy54meR3tIV0+mXFc=
│  │  │  │  │  │  │     ├─ 047DWl7ck3KWF9MbQTle7JtQxtM=
│  │  │  │  │  │  │     ├─ 1C3ufAUUAqK8maUQUEii2EMwWo4=
│  │  │  │  │  │  │     ├─ 1FgdDET6Fbp7pZVZbv7RhUqD1Kg=
│  │  │  │  │  │  │     ├─ 1ODCFDy58jImDhLwu5RzTZdq6tI=
│  │  │  │  │  │  │     ├─ 1z8DwgR_pJ5EhjvjNTeAjT3b29s=
│  │  │  │  │  │  │     ├─ 2IG886ZhdqucgDbvaBNPFG7GNHQ=
│  │  │  │  │  │  │     ├─ 2KXy+pdN25Qg0XJnA4JSKzgXQxw=
│  │  │  │  │  │  │     ├─ 3FtatL+JVFFmgYXbgkyrBjBLaJ0=
│  │  │  │  │  │  │     ├─ 3QsI_CHKu5nrnQR8cwWF5HtxNDs=
│  │  │  │  │  │  │     ├─ 3Vo5Oqz8iGK0L_Mg6Qw7M2j4Q9M=
│  │  │  │  │  │  │     ├─ 4R3+mF0kVnDNm0GUucw9RNpqs9I=
│  │  │  │  │  │  │     ├─ 5suMrRKpHx9kH1kJSr_HN4ekngk=
│  │  │  │  │  │  │     ├─ 6joTqrxtXKHtb5pYE2iLd0PzK+c=
│  │  │  │  │  │  │     ├─ 6mozBgnyFIlZPNQo6iYA9Iu_fvc=
│  │  │  │  │  │  │     ├─ 6usCwCE1_f+rEELcS5Z63WVPEH4=
│  │  │  │  │  │  │     ├─ 6_7Dc0rKp3d1JLIiVpcqTi5RWOo=
│  │  │  │  │  │  │     ├─ 72TTFYCQclXR+XuAPwxM6qOVYx4=
│  │  │  │  │  │  │     ├─ 7mA7MLSOU72E9cqd9OwfejoAw0s=
│  │  │  │  │  │  │     ├─ 8isFSJyZ+7p9_diZELFvAhQSO6Y=
│  │  │  │  │  │  │     ├─ 9MhtgHoPIcgIh72PdRpvDia555U=
│  │  │  │  │  │  │     ├─ 9y1gHLYTvDmkWjdwolUOtvTNhmU=
│  │  │  │  │  │  │     ├─ abPjy2blJwpgdRaD+Ezs5TomI+s=
│  │  │  │  │  │  │     ├─ an4hygmpZlaP_0FLGa7RnbiSj98=
│  │  │  │  │  │  │     ├─ aRbMZ4YFgj3BidRmsZL1ZLjxRxQ=
│  │  │  │  │  │  │     ├─ Au0_X4fR5ygJ3ERehQc2m9RHZJg=
│  │  │  │  │  │  │     ├─ ax0TZzuvTCcL1u71aOuk18TgwmI=
│  │  │  │  │  │  │     ├─ B7u8XdZ0U4X7idtiOeXd3AekqVw=
│  │  │  │  │  │  │     ├─ bMZ_jnhgzf05Ys7_zxfM9E2bi5k=
│  │  │  │  │  │  │     ├─ BnBpeYfvRb2oQ2jGIQ2gfcdHLSI=
│  │  │  │  │  │  │     ├─ c4xl3717koLDhkc4x7AdNMzSY4s=
│  │  │  │  │  │  │     ├─ cM4pZfPvquoReZqYtmo2fTsmaY8=
│  │  │  │  │  │  │     ├─ coBEzb7V0PAsnhLbQP_dyZQ0tik=
│  │  │  │  │  │  │     ├─ dghCLlLgJQ8WDibqIEHniXEuicU=
│  │  │  │  │  │  │     ├─ E8aJ+S8IGGI_eIzSruHb58kr9DQ=
│  │  │  │  │  │  │     ├─ enfMBnPFLt3HKt1wTmPonSPpgcE=
│  │  │  │  │  │  │     ├─ Eo3oZzzs7EvGrQqj9La+f+joqNs=
│  │  │  │  │  │  │     ├─ EYkZy2QbrLNaxpd29l1in4st8oo=
│  │  │  │  │  │  │     ├─ f4ua6jI7cYO_tH4Q3st3b4k3b7A=
│  │  │  │  │  │  │     ├─ Fgy1YW0l7M27ul55mC1tddN2XeI=
│  │  │  │  │  │  │     ├─ Fl2weiWFRiTl80jkiLHwjrufPwI=
│  │  │  │  │  │  │     ├─ FLfJ3JORQ3J436xqOrQ71aUGZFk=
│  │  │  │  │  │  │     ├─ fNguwLIVticzLxpDkJbmKcKzSTs=
│  │  │  │  │  │  │     ├─ g3s3XcDyzdpHWaNA9PfQxH_Kjds=
│  │  │  │  │  │  │     ├─ GUj7FfSCdHE9k4mtieEQJWdiqSk=
│  │  │  │  │  │  │     ├─ gWWXxYNfYsEmUibSPo7mh8XXP+U=
│  │  │  │  │  │  │     ├─ gZqX_85uD5zVXKSOclBW2zay3eE=
│  │  │  │  │  │  │     ├─ h9M2bVhwHEnEx2NtUz2_n_LlNAY=
│  │  │  │  │  │  │     ├─ HooHzB0Cyozf5WtX5CaIa69_Fyg=
│  │  │  │  │  │  │     ├─ I4L91l73qNwBbSNGcsb+uKjYsiI=
│  │  │  │  │  │  │     ├─ ieRmA5_rnm4vThq0CsKovLAV3ZM=
│  │  │  │  │  │  │     ├─ Ijt94J1lVvMq3XNcy9a_+q0SpzA=
│  │  │  │  │  │  │     ├─ ipmjRQX+0QyXjbMBH3_lwUm8pMU=
│  │  │  │  │  │  │     ├─ J19uUnAKGvY9QgnsOfrVNmdSiCg=
│  │  │  │  │  │  │     ├─ JBN3BEZ3QX6ItTLngbjqp4wc+Lo=
│  │  │  │  │  │  │     ├─ JCkZvrIP6MYRpxOjkou1E9eUwn8=
│  │  │  │  │  │  │     ├─ JFNB5xZrLOehGtli2YXYvaG0TqU=
│  │  │  │  │  │  │     ├─ JkVfaDv3Uj83miAd0kaU_4ncSUE=
│  │  │  │  │  │  │     ├─ jnG6z_E82GPnXZ8flCFxqhuo15g=
│  │  │  │  │  │  │     ├─ jyUeOsnry2wQjbuM+A0s5bBf7zg=
│  │  │  │  │  │  │     ├─ K2d73wmvuQe8csze+BuVF_AV+QA=
│  │  │  │  │  │  │     ├─ K9yFKOiUR8a3x3zyJ_z4GTYfLCY=
│  │  │  │  │  │  │     ├─ KNGc15UU9VqZbcBU8S_SFn5+EuY=
│  │  │  │  │  │  │     ├─ kqYprTk6npyD153A3ekG4uT4Tv0=
│  │  │  │  │  │  │     ├─ l9iRIDgwIFn7C9R+jl3fSvT5hMU=
│  │  │  │  │  │  │     ├─ LIsUBH3BZ7FKeEWHBPWcDYkeZdY=
│  │  │  │  │  │  │     ├─ M8w9MRI38cVgsGwTzNf8V1QAgZI=
│  │  │  │  │  │  │     ├─ msJyYIRpr9rIUzyv_usAP1PGAXk=
│  │  │  │  │  │  │     ├─ mv5rUbIoys2TTDvGoeeBtHZXTn8=
│  │  │  │  │  │  │     ├─ N+CtN+szt6LaJ3TuoVVEAOLyEpw=
│  │  │  │  │  │  │     ├─ N9rumYlOICMG_SpgvobgDSnCN0k=
│  │  │  │  │  │  │     ├─ ncWDinnxgn7D_gMDxCbiGBCZtEs=
│  │  │  │  │  │  │     ├─ NsIV+6qDQXpz6FmiDUt+pir7a0w=
│  │  │  │  │  │  │     ├─ nuIlOswNpYhPvYpY6QgjXpE3fk0=
│  │  │  │  │  │  │     ├─ O5tz_pTX5_bZ1p5Knf9ZFmj5YqY=
│  │  │  │  │  │  │     ├─ OKqdJR8CFarSec3TAIILRkyEYUs=
│  │  │  │  │  │  │     ├─ oZwMMluB0fH2P1B+Mq89OuOWXEU=
│  │  │  │  │  │  │     ├─ P8mjU_3tGYP4Dj1MNHcelTdDJLw=
│  │  │  │  │  │  │     ├─ piSOsKrU5384gw2+9LyAQBbygnk=
│  │  │  │  │  │  │     ├─ POg1d_kqJM7VCdj0JV5n6cnHNLs=
│  │  │  │  │  │  │     ├─ Px5+d_vPICWD8gZm_MJbTqw7DzI=
│  │  │  │  │  │  │     ├─ PY9dbdcb1XBCC5BWsrap48qntPc=
│  │  │  │  │  │  │     ├─ qg1JXYPhZED9WCu+7ltBwNFK3_4=
│  │  │  │  │  │  │     ├─ r2mFBdK46L7OUARxhX78__GIj7c=
│  │  │  │  │  │  │     ├─ RHyYL+B8xOv5WlAo1lR35NoQ7bM=
│  │  │  │  │  │  │     ├─ Rx6af9obumRbNrNLDCfoHnhSnyI=
│  │  │  │  │  │  │     ├─ SFbWe7J9aNVbZFBHGObnMoqb6Tc=
│  │  │  │  │  │  │     ├─ tq3bUyQBM_lgkdnKL1UVqzYfA0o=
│  │  │  │  │  │  │     ├─ UFOSbd24wMAadgVxozKDHo31g6E=
│  │  │  │  │  │  │     ├─ UH10jVYrLfzgtPK8Je0rSf32LXs=
│  │  │  │  │  │  │     ├─ UiCWuV1Zfq7zlMBd9YukGTJBpS0=
│  │  │  │  │  │  │     ├─ uiCzxVfoRIrCt0pl238c8g5Z_+I=
│  │  │  │  │  │  │     ├─ UIgWBo_bguvzEnn1fsyh7q8OGTA=
│  │  │  │  │  │  │     ├─ unCyMjuDMyW3ly+9PJefM+PRneo=
│  │  │  │  │  │  │     ├─ UnHNXePGxOTa++KGd2TonVe1Nuo=
│  │  │  │  │  │  │     ├─ Upez9hG732jFfdxJH5iO3lx5E4o=
│  │  │  │  │  │  │     ├─ Urwrjt4UQ+UYFOG6sSx+cni2eL8=
│  │  │  │  │  │  │     ├─ uVnYRwfnf7YS1Vek8P0TBHCrFOc=
│  │  │  │  │  │  │     ├─ uwCDkqTgwMjFYUAFfVLpXfxHOQI=
│  │  │  │  │  │  │     ├─ vkhz7wpd9M_6nP296zG_tGEQMHk=
│  │  │  │  │  │  │     ├─ VkUQ08xhKHcwr3rtoDBJDcU9OiU=
│  │  │  │  │  │  │     ├─ vrydHeC1oMP50MksNDcq4UC6gxY=
│  │  │  │  │  │  │     ├─ W2zMlDSyiSX8KNPHoXVWPeWV72Q=
│  │  │  │  │  │  │     ├─ wgXKMF05q41p6zp1GqC1o_eZroU=
│  │  │  │  │  │  │     ├─ wHyO4VFDcp1zgY7XnYHMbeKqNxQ=
│  │  │  │  │  │  │     ├─ wLqVbKTNnUyKLX55YcYYbyFyeDw=
│  │  │  │  │  │  │     ├─ wnq9f1RGEpBQyzgDfZAjZD+hs4U=
│  │  │  │  │  │  │     ├─ Wwf1C2jLd1KYF5ver5PSEMQsZ84=
│  │  │  │  │  │  │     ├─ Y6k35hY7xdS3tB3hmjDgyAPwkh4=
│  │  │  │  │  │  │     ├─ YbYBbOWqy38Xw8lvcKiXpanxLo8=
│  │  │  │  │  │  │     ├─ z4ugkFY_6FYkyt++VQif93bcGgw=
│  │  │  │  │  │  │     └─ zHjG+lpOOZ5fHpAKz_ZLBZbZqq0=
│  │  │  │  │  │  ├─ mergeDebugAssets
│  │  │  │  │  │  │  └─ merger.xml
│  │  │  │  │  │  ├─ mergeDebugJniLibFolders
│  │  │  │  │  │  │  └─ merger.xml
│  │  │  │  │  │  ├─ mergeDebugShaders
│  │  │  │  │  │  │  └─ merger.xml
│  │  │  │  │  │  └─ packageDebug
│  │  │  │  │  │     └─ tmp
│  │  │  │  │  │        └─ debug
│  │  │  │  │  │           ├─ dex-renamer-state.txt
│  │  │  │  │  │           └─ zip-cache
│  │  │  │  │  │              ├─ androidResources
│  │  │  │  │  │              └─ javaResources0
│  │  │  │  │  ├─ javac
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ compileDebugJavaWithJavac
│  │  │  │  │  │        └─ classes
│  │  │  │  │  │           └─ com
│  │  │  │  │  │              ├─ facebook
│  │  │  │  │  │              │  └─ react
│  │  │  │  │  │              │     └─ PackageList.class
│  │  │  │  │  │              └─ myapp
│  │  │  │  │  │                 └─ BuildConfig.class
│  │  │  │  │  ├─ java_res
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugJavaRes
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           ├─ com
│  │  │  │  │  │           │  └─ myapp
│  │  │  │  │  │           └─ META-INF
│  │  │  │  │  │              └─ app_debug.kotlin_module
│  │  │  │  │  ├─ linked_resources_binary_format
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugResources
│  │  │  │  │  │        ├─ linked-resources-binary-format-debug.ap_
│  │  │  │  │  │        └─ output-metadata.json
│  │  │  │  │  ├─ local_only_symbol_list
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ parseDebugLocalResources
│  │  │  │  │  │        └─ R-def.txt
│  │  │  │  │  ├─ manifest_merge_blame_file
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugMainManifest
│  │  │  │  │  │        └─ manifest-merger-blame-debug-report.txt
│  │  │  │  │  ├─ merged_java_res
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugJavaResource
│  │  │  │  │  │        └─ base.jar
│  │  │  │  │  ├─ merged_jni_libs
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugJniLibFolders
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ merged_manifest
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugMainManifest
│  │  │  │  │  │        └─ AndroidManifest.xml
│  │  │  │  │  ├─ merged_manifests
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugManifest
│  │  │  │  │  │        ├─ AndroidManifest.xml
│  │  │  │  │  │        └─ output-metadata.json
│  │  │  │  │  ├─ merged_native_libs
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugNativeLibs
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           └─ lib
│  │  │  │  │  │              ├─ arm64-v8a
│  │  │  │  │  │              │  ├─ libappmodules.so
│  │  │  │  │  │              │  ├─ libc++_shared.so
│  │  │  │  │  │              │  ├─ libfbjni.so
│  │  │  │  │  │              │  ├─ libgesturehandler.so
│  │  │  │  │  │              │  ├─ libhermes.so
│  │  │  │  │  │              │  ├─ libhermestooling.so
│  │  │  │  │  │              │  ├─ libimagepipeline.so
│  │  │  │  │  │              │  ├─ libjsi.so
│  │  │  │  │  │              │  ├─ libmmkv.so
│  │  │  │  │  │              │  ├─ libnative-filters.so
│  │  │  │  │  │              │  ├─ libnative-imagetranscoder.so
│  │  │  │  │  │              │  ├─ libpdfium.so
│  │  │  │  │  │              │  ├─ libpdfiumandroid.so
│  │  │  │  │  │              │  ├─ libreactnative.so
│  │  │  │  │  │              │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │              │  ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │              │  ├─ libreanimated.so
│  │  │  │  │  │              │  ├─ librnscreens.so
│  │  │  │  │  │              │  └─ libworklets.so
│  │  │  │  │  │              ├─ armeabi-v7a
│  │  │  │  │  │              │  ├─ libappmodules.so
│  │  │  │  │  │              │  ├─ libc++_shared.so
│  │  │  │  │  │              │  ├─ libfbjni.so
│  │  │  │  │  │              │  ├─ libgesturehandler.so
│  │  │  │  │  │              │  ├─ libhermes.so
│  │  │  │  │  │              │  ├─ libhermestooling.so
│  │  │  │  │  │              │  ├─ libimagepipeline.so
│  │  │  │  │  │              │  ├─ libjsi.so
│  │  │  │  │  │              │  ├─ libmmkv.so
│  │  │  │  │  │              │  ├─ libnative-filters.so
│  │  │  │  │  │              │  ├─ libnative-imagetranscoder.so
│  │  │  │  │  │              │  ├─ libpdfium.so
│  │  │  │  │  │              │  ├─ libpdfiumandroid.so
│  │  │  │  │  │              │  ├─ libreactnative.so
│  │  │  │  │  │              │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │              │  ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │              │  ├─ libreanimated.so
│  │  │  │  │  │              │  ├─ librnscreens.so
│  │  │  │  │  │              │  └─ libworklets.so
│  │  │  │  │  │              ├─ x86
│  │  │  │  │  │              │  ├─ libappmodules.so
│  │  │  │  │  │              │  ├─ libc++_shared.so
│  │  │  │  │  │              │  ├─ libfbjni.so
│  │  │  │  │  │              │  ├─ libgesturehandler.so
│  │  │  │  │  │              │  ├─ libhermes.so
│  │  │  │  │  │              │  ├─ libhermestooling.so
│  │  │  │  │  │              │  ├─ libimagepipeline.so
│  │  │  │  │  │              │  ├─ libjsi.so
│  │  │  │  │  │              │  ├─ libmmkv.so
│  │  │  │  │  │              │  ├─ libnative-filters.so
│  │  │  │  │  │              │  ├─ libnative-imagetranscoder.so
│  │  │  │  │  │              │  ├─ libpdfium.so
│  │  │  │  │  │              │  ├─ libpdfiumandroid.so
│  │  │  │  │  │              │  ├─ libreactnative.so
│  │  │  │  │  │              │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │              │  ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │              │  ├─ libreanimated.so
│  │  │  │  │  │              │  ├─ librnscreens.so
│  │  │  │  │  │              │  └─ libworklets.so
│  │  │  │  │  │              └─ x86_64
│  │  │  │  │  │                 ├─ libappmodules.so
│  │  │  │  │  │                 ├─ libc++_shared.so
│  │  │  │  │  │                 ├─ libfbjni.so
│  │  │  │  │  │                 ├─ libgesturehandler.so
│  │  │  │  │  │                 ├─ libhermes.so
│  │  │  │  │  │                 ├─ libhermestooling.so
│  │  │  │  │  │                 ├─ libimagepipeline.so
│  │  │  │  │  │                 ├─ libjsi.so
│  │  │  │  │  │                 ├─ libmmkv.so
│  │  │  │  │  │                 ├─ libnative-filters.so
│  │  │  │  │  │                 ├─ libnative-imagetranscoder.so
│  │  │  │  │  │                 ├─ libpdfium.so
│  │  │  │  │  │                 ├─ libpdfiumandroid.so
│  │  │  │  │  │                 ├─ libreactnative.so
│  │  │  │  │  │                 ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │                 ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │                 ├─ libreanimated.so
│  │  │  │  │  │                 ├─ librnscreens.so
│  │  │  │  │  │                 └─ libworklets.so
│  │  │  │  │  ├─ merged_res
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugResources
│  │  │  │  │  │        ├─ drawable_rn_edit_text_material.xml.flat
│  │  │  │  │  │        ├─ mipmap-hdpi_ic_launcher.png.flat
│  │  │  │  │  │        ├─ mipmap-hdpi_ic_launcher_round.png.flat
│  │  │  │  │  │        ├─ mipmap-mdpi_ic_launcher.png.flat
│  │  │  │  │  │        ├─ mipmap-mdpi_ic_launcher_round.png.flat
│  │  │  │  │  │        ├─ mipmap-xhdpi_ic_launcher.png.flat
│  │  │  │  │  │        ├─ mipmap-xhdpi_ic_launcher_round.png.flat
│  │  │  │  │  │        ├─ mipmap-xxhdpi_ic_launcher.png.flat
│  │  │  │  │  │        ├─ mipmap-xxhdpi_ic_launcher_round.png.flat
│  │  │  │  │  │        ├─ mipmap-xxxhdpi_ic_launcher.png.flat
│  │  │  │  │  │        ├─ mipmap-xxxhdpi_ic_launcher_round.png.flat
│  │  │  │  │  │        ├─ values-af_values-af.arsc.flat
│  │  │  │  │  │        ├─ values-am_values-am.arsc.flat
│  │  │  │  │  │        ├─ values-ar_values-ar.arsc.flat
│  │  │  │  │  │        ├─ values-as_values-as.arsc.flat
│  │  │  │  │  │        ├─ values-az_values-az.arsc.flat
│  │  │  │  │  │        ├─ values-b+es+419_values-b+es+419.arsc.flat
│  │  │  │  │  │        ├─ values-b+sr+Latn_values-b+sr+Latn.arsc.flat
│  │  │  │  │  │        ├─ values-be_values-be.arsc.flat
│  │  │  │  │  │        ├─ values-bg_values-bg.arsc.flat
│  │  │  │  │  │        ├─ values-bn_values-bn.arsc.flat
│  │  │  │  │  │        ├─ values-bs_values-bs.arsc.flat
│  │  │  │  │  │        ├─ values-ca_values-ca.arsc.flat
│  │  │  │  │  │        ├─ values-cs_values-cs.arsc.flat
│  │  │  │  │  │        ├─ values-da_values-da.arsc.flat
│  │  │  │  │  │        ├─ values-de_values-de.arsc.flat
│  │  │  │  │  │        ├─ values-el_values-el.arsc.flat
│  │  │  │  │  │        ├─ values-en-rAU_values-en-rAU.arsc.flat
│  │  │  │  │  │        ├─ values-en-rCA_values-en-rCA.arsc.flat
│  │  │  │  │  │        ├─ values-en-rGB_values-en-rGB.arsc.flat
│  │  │  │  │  │        ├─ values-en-rIN_values-en-rIN.arsc.flat
│  │  │  │  │  │        ├─ values-en-rXC_values-en-rXC.arsc.flat
│  │  │  │  │  │        ├─ values-es-rES_values-es-rES.arsc.flat
│  │  │  │  │  │        ├─ values-es-rUS_values-es-rUS.arsc.flat
│  │  │  │  │  │        ├─ values-es_values-es.arsc.flat
│  │  │  │  │  │        ├─ values-et_values-et.arsc.flat
│  │  │  │  │  │        ├─ values-eu_values-eu.arsc.flat
│  │  │  │  │  │        ├─ values-fa_values-fa.arsc.flat
│  │  │  │  │  │        ├─ values-fi_values-fi.arsc.flat
│  │  │  │  │  │        ├─ values-fr-rCA_values-fr-rCA.arsc.flat
│  │  │  │  │  │        ├─ values-fr_values-fr.arsc.flat
│  │  │  │  │  │        ├─ values-gl_values-gl.arsc.flat
│  │  │  │  │  │        ├─ values-gu_values-gu.arsc.flat
│  │  │  │  │  │        ├─ values-h320dp-port-v13_values-h320dp-port-v13.arsc.flat
│  │  │  │  │  │        ├─ values-h360dp-land-v13_values-h360dp-land-v13.arsc.flat
│  │  │  │  │  │        ├─ values-h480dp-land-v13_values-h480dp-land-v13.arsc.flat
│  │  │  │  │  │        ├─ values-h550dp-port-v13_values-h550dp-port-v13.arsc.flat
│  │  │  │  │  │        ├─ values-h720dp-v13_values-h720dp-v13.arsc.flat
│  │  │  │  │  │        ├─ values-hdpi-v4_values-hdpi-v4.arsc.flat
│  │  │  │  │  │        ├─ values-hi_values-hi.arsc.flat
│  │  │  │  │  │        ├─ values-hr_values-hr.arsc.flat
│  │  │  │  │  │        ├─ values-hu_values-hu.arsc.flat
│  │  │  │  │  │        ├─ values-hy_values-hy.arsc.flat
│  │  │  │  │  │        ├─ values-in_values-in.arsc.flat
│  │  │  │  │  │        ├─ values-is_values-is.arsc.flat
│  │  │  │  │  │        ├─ values-it_values-it.arsc.flat
│  │  │  │  │  │        ├─ values-iw_values-iw.arsc.flat
│  │  │  │  │  │        ├─ values-ja_values-ja.arsc.flat
│  │  │  │  │  │        ├─ values-ka_values-ka.arsc.flat
│  │  │  │  │  │        ├─ values-kk_values-kk.arsc.flat
│  │  │  │  │  │        ├─ values-km_values-km.arsc.flat
│  │  │  │  │  │        ├─ values-kn_values-kn.arsc.flat
│  │  │  │  │  │        ├─ values-ko_values-ko.arsc.flat
│  │  │  │  │  │        ├─ values-ky_values-ky.arsc.flat
│  │  │  │  │  │        ├─ values-land_values-land.arsc.flat
│  │  │  │  │  │        ├─ values-large-v4_values-large-v4.arsc.flat
│  │  │  │  │  │        ├─ values-ldltr-v21_values-ldltr-v21.arsc.flat
│  │  │  │  │  │        ├─ values-ldrtl-v17_values-ldrtl-v17.arsc.flat
│  │  │  │  │  │        ├─ values-lo_values-lo.arsc.flat
│  │  │  │  │  │        ├─ values-lt_values-lt.arsc.flat
│  │  │  │  │  │        ├─ values-lv_values-lv.arsc.flat
│  │  │  │  │  │        ├─ values-mk_values-mk.arsc.flat
│  │  │  │  │  │        ├─ values-ml_values-ml.arsc.flat
│  │  │  │  │  │        ├─ values-mn_values-mn.arsc.flat
│  │  │  │  │  │        ├─ values-mr_values-mr.arsc.flat
│  │  │  │  │  │        ├─ values-ms_values-ms.arsc.flat
│  │  │  │  │  │        ├─ values-my_values-my.arsc.flat
│  │  │  │  │  │        ├─ values-nb_values-nb.arsc.flat
│  │  │  │  │  │        ├─ values-ne_values-ne.arsc.flat
│  │  │  │  │  │        ├─ values-night-v8_values-night-v8.arsc.flat
│  │  │  │  │  │        ├─ values-nl_values-nl.arsc.flat
│  │  │  │  │  │        ├─ values-or_values-or.arsc.flat
│  │  │  │  │  │        ├─ values-pa_values-pa.arsc.flat
│  │  │  │  │  │        ├─ values-pl_values-pl.arsc.flat
│  │  │  │  │  │        ├─ values-port_values-port.arsc.flat
│  │  │  │  │  │        ├─ values-pt-rBR_values-pt-rBR.arsc.flat
│  │  │  │  │  │        ├─ values-pt-rPT_values-pt-rPT.arsc.flat
│  │  │  │  │  │        ├─ values-pt_values-pt.arsc.flat
│  │  │  │  │  │        ├─ values-ro_values-ro.arsc.flat
│  │  │  │  │  │        ├─ values-ru_values-ru.arsc.flat
│  │  │  │  │  │        ├─ values-si_values-si.arsc.flat
│  │  │  │  │  │        ├─ values-sk_values-sk.arsc.flat
│  │  │  │  │  │        ├─ values-sl_values-sl.arsc.flat
│  │  │  │  │  │        ├─ values-small-v4_values-small-v4.arsc.flat
│  │  │  │  │  │        ├─ values-sq_values-sq.arsc.flat
│  │  │  │  │  │        ├─ values-sr_values-sr.arsc.flat
│  │  │  │  │  │        ├─ values-sv_values-sv.arsc.flat
│  │  │  │  │  │        ├─ values-sw600dp-v13_values-sw600dp-v13.arsc.flat
│  │  │  │  │  │        ├─ values-sw_values-sw.arsc.flat
│  │  │  │  │  │        ├─ values-ta_values-ta.arsc.flat
│  │  │  │  │  │        ├─ values-te_values-te.arsc.flat
│  │  │  │  │  │        ├─ values-th_values-th.arsc.flat
│  │  │  │  │  │        ├─ values-tl_values-tl.arsc.flat
│  │  │  │  │  │        ├─ values-tr_values-tr.arsc.flat
│  │  │  │  │  │        ├─ values-uk_values-uk.arsc.flat
│  │  │  │  │  │        ├─ values-ur_values-ur.arsc.flat
│  │  │  │  │  │        ├─ values-uz_values-uz.arsc.flat
│  │  │  │  │  │        ├─ values-v16_values-v16.arsc.flat
│  │  │  │  │  │        ├─ values-v17_values-v17.arsc.flat
│  │  │  │  │  │        ├─ values-v18_values-v18.arsc.flat
│  │  │  │  │  │        ├─ values-v21_values-v21.arsc.flat
│  │  │  │  │  │        ├─ values-v22_values-v22.arsc.flat
│  │  │  │  │  │        ├─ values-v23_values-v23.arsc.flat
│  │  │  │  │  │        ├─ values-v24_values-v24.arsc.flat
│  │  │  │  │  │        ├─ values-v25_values-v25.arsc.flat
│  │  │  │  │  │        ├─ values-v26_values-v26.arsc.flat
│  │  │  │  │  │        ├─ values-v28_values-v28.arsc.flat
│  │  │  │  │  │        ├─ values-v31_values-v31.arsc.flat
│  │  │  │  │  │        ├─ values-vi_values-vi.arsc.flat
│  │  │  │  │  │        ├─ values-w320dp-land-v13_values-w320dp-land-v13.arsc.flat
│  │  │  │  │  │        ├─ values-w360dp-port-v13_values-w360dp-port-v13.arsc.flat
│  │  │  │  │  │        ├─ values-w480dp-port-v13_values-w480dp-port-v13.arsc.flat
│  │  │  │  │  │        ├─ values-w600dp-land-v13_values-w600dp-land-v13.arsc.flat
│  │  │  │  │  │        ├─ values-watch-v20_values-watch-v20.arsc.flat
│  │  │  │  │  │        ├─ values-watch-v21_values-watch-v21.arsc.flat
│  │  │  │  │  │        ├─ values-xlarge-v4_values-xlarge-v4.arsc.flat
│  │  │  │  │  │        ├─ values-zh-rCN_values-zh-rCN.arsc.flat
│  │  │  │  │  │        ├─ values-zh-rHK_values-zh-rHK.arsc.flat
│  │  │  │  │  │        ├─ values-zh-rTW_values-zh-rTW.arsc.flat
│  │  │  │  │  │        ├─ values-zu_values-zu.arsc.flat
│  │  │  │  │  │        └─ values_values.arsc.flat
│  │  │  │  │  ├─ merged_res_blame_folder
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugResources
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           ├─ multi-v2
│  │  │  │  │  │           │  ├─ mergeDebugResources.json
│  │  │  │  │  │           │  ├─ values-af.json
│  │  │  │  │  │           │  ├─ values-am.json
│  │  │  │  │  │           │  ├─ values-ar.json
│  │  │  │  │  │           │  ├─ values-as.json
│  │  │  │  │  │           │  ├─ values-az.json
│  │  │  │  │  │           │  ├─ values-b+es+419.json
│  │  │  │  │  │           │  ├─ values-b+sr+Latn.json
│  │  │  │  │  │           │  ├─ values-be.json
│  │  │  │  │  │           │  ├─ values-bg.json
│  │  │  │  │  │           │  ├─ values-bn.json
│  │  │  │  │  │           │  ├─ values-bs.json
│  │  │  │  │  │           │  ├─ values-ca.json
│  │  │  │  │  │           │  ├─ values-cs.json
│  │  │  │  │  │           │  ├─ values-da.json
│  │  │  │  │  │           │  ├─ values-de.json
│  │  │  │  │  │           │  ├─ values-el.json
│  │  │  │  │  │           │  ├─ values-en-rAU.json
│  │  │  │  │  │           │  ├─ values-en-rCA.json
│  │  │  │  │  │           │  ├─ values-en-rGB.json
│  │  │  │  │  │           │  ├─ values-en-rIN.json
│  │  │  │  │  │           │  ├─ values-en-rXC.json
│  │  │  │  │  │           │  ├─ values-es-rES.json
│  │  │  │  │  │           │  ├─ values-es-rUS.json
│  │  │  │  │  │           │  ├─ values-es.json
│  │  │  │  │  │           │  ├─ values-et.json
│  │  │  │  │  │           │  ├─ values-eu.json
│  │  │  │  │  │           │  ├─ values-fa.json
│  │  │  │  │  │           │  ├─ values-fi.json
│  │  │  │  │  │           │  ├─ values-fr-rCA.json
│  │  │  │  │  │           │  ├─ values-fr.json
│  │  │  │  │  │           │  ├─ values-gl.json
│  │  │  │  │  │           │  ├─ values-gu.json
│  │  │  │  │  │           │  ├─ values-h320dp-port-v13.json
│  │  │  │  │  │           │  ├─ values-h360dp-land-v13.json
│  │  │  │  │  │           │  ├─ values-h480dp-land-v13.json
│  │  │  │  │  │           │  ├─ values-h550dp-port-v13.json
│  │  │  │  │  │           │  ├─ values-h720dp-v13.json
│  │  │  │  │  │           │  ├─ values-hdpi-v4.json
│  │  │  │  │  │           │  ├─ values-hi.json
│  │  │  │  │  │           │  ├─ values-hr.json
│  │  │  │  │  │           │  ├─ values-hu.json
│  │  │  │  │  │           │  ├─ values-hy.json
│  │  │  │  │  │           │  ├─ values-in.json
│  │  │  │  │  │           │  ├─ values-is.json
│  │  │  │  │  │           │  ├─ values-it.json
│  │  │  │  │  │           │  ├─ values-iw.json
│  │  │  │  │  │           │  ├─ values-ja.json
│  │  │  │  │  │           │  ├─ values-ka.json
│  │  │  │  │  │           │  ├─ values-kk.json
│  │  │  │  │  │           │  ├─ values-km.json
│  │  │  │  │  │           │  ├─ values-kn.json
│  │  │  │  │  │           │  ├─ values-ko.json
│  │  │  │  │  │           │  ├─ values-ky.json
│  │  │  │  │  │           │  ├─ values-land.json
│  │  │  │  │  │           │  ├─ values-large-v4.json
│  │  │  │  │  │           │  ├─ values-ldltr-v21.json
│  │  │  │  │  │           │  ├─ values-ldrtl-v17.json
│  │  │  │  │  │           │  ├─ values-lo.json
│  │  │  │  │  │           │  ├─ values-lt.json
│  │  │  │  │  │           │  ├─ values-lv.json
│  │  │  │  │  │           │  ├─ values-mk.json
│  │  │  │  │  │           │  ├─ values-ml.json
│  │  │  │  │  │           │  ├─ values-mn.json
│  │  │  │  │  │           │  ├─ values-mr.json
│  │  │  │  │  │           │  ├─ values-ms.json
│  │  │  │  │  │           │  ├─ values-my.json
│  │  │  │  │  │           │  ├─ values-nb.json
│  │  │  │  │  │           │  ├─ values-ne.json
│  │  │  │  │  │           │  ├─ values-night-v8.json
│  │  │  │  │  │           │  ├─ values-nl.json
│  │  │  │  │  │           │  ├─ values-or.json
│  │  │  │  │  │           │  ├─ values-pa.json
│  │  │  │  │  │           │  ├─ values-pl.json
│  │  │  │  │  │           │  ├─ values-port.json
│  │  │  │  │  │           │  ├─ values-pt-rBR.json
│  │  │  │  │  │           │  ├─ values-pt-rPT.json
│  │  │  │  │  │           │  ├─ values-pt.json
│  │  │  │  │  │           │  ├─ values-ro.json
│  │  │  │  │  │           │  ├─ values-ru.json
│  │  │  │  │  │           │  ├─ values-si.json
│  │  │  │  │  │           │  ├─ values-sk.json
│  │  │  │  │  │           │  ├─ values-sl.json
│  │  │  │  │  │           │  ├─ values-small-v4.json
│  │  │  │  │  │           │  ├─ values-sq.json
│  │  │  │  │  │           │  ├─ values-sr.json
│  │  │  │  │  │           │  ├─ values-sv.json
│  │  │  │  │  │           │  ├─ values-sw.json
│  │  │  │  │  │           │  ├─ values-sw600dp-v13.json
│  │  │  │  │  │           │  ├─ values-ta.json
│  │  │  │  │  │           │  ├─ values-te.json
│  │  │  │  │  │           │  ├─ values-th.json
│  │  │  │  │  │           │  ├─ values-tl.json
│  │  │  │  │  │           │  ├─ values-tr.json
│  │  │  │  │  │           │  ├─ values-uk.json
│  │  │  │  │  │           │  ├─ values-ur.json
│  │  │  │  │  │           │  ├─ values-uz.json
│  │  │  │  │  │           │  ├─ values-v16.json
│  │  │  │  │  │           │  ├─ values-v17.json
│  │  │  │  │  │           │  ├─ values-v18.json
│  │  │  │  │  │           │  ├─ values-v21.json
│  │  │  │  │  │           │  ├─ values-v22.json
│  │  │  │  │  │           │  ├─ values-v23.json
│  │  │  │  │  │           │  ├─ values-v24.json
│  │  │  │  │  │           │  ├─ values-v25.json
│  │  │  │  │  │           │  ├─ values-v26.json
│  │  │  │  │  │           │  ├─ values-v28.json
│  │  │  │  │  │           │  ├─ values-v31.json
│  │  │  │  │  │           │  ├─ values-vi.json
│  │  │  │  │  │           │  ├─ values-w320dp-land-v13.json
│  │  │  │  │  │           │  ├─ values-w360dp-port-v13.json
│  │  │  │  │  │           │  ├─ values-w480dp-port-v13.json
│  │  │  │  │  │           │  ├─ values-w600dp-land-v13.json
│  │  │  │  │  │           │  ├─ values-watch-v20.json
│  │  │  │  │  │           │  ├─ values-watch-v21.json
│  │  │  │  │  │           │  ├─ values-xlarge-v4.json
│  │  │  │  │  │           │  ├─ values-zh-rCN.json
│  │  │  │  │  │           │  ├─ values-zh-rHK.json
│  │  │  │  │  │           │  ├─ values-zh-rTW.json
│  │  │  │  │  │           │  ├─ values-zu.json
│  │  │  │  │  │           │  └─ values.json
│  │  │  │  │  │           └─ single
│  │  │  │  │  │              └─ mergeDebugResources.json
│  │  │  │  │  ├─ merged_shaders
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugShaders
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ merged_test_only_native_libs
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mergeDebugNativeLibs
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ mixed_scope_dex_archive
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ navigation_json
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ extractDeepLinksDebug
│  │  │  │  │  │        └─ navigation.json
│  │  │  │  │  ├─ nested_resources_validation_report
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ generateDebugResources
│  │  │  │  │  │        └─ nestedResourcesValidationReport.txt
│  │  │  │  │  ├─ packaged_manifests
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugManifestForPackage
│  │  │  │  │  │        ├─ AndroidManifest.xml
│  │  │  │  │  │        └─ output-metadata.json
│  │  │  │  │  ├─ packaged_res
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ packageDebugResources
│  │  │  │  │  │        ├─ drawable
│  │  │  │  │  │        │  └─ rn_edit_text_material.xml
│  │  │  │  │  │        ├─ mipmap-hdpi-v4
│  │  │  │  │  │        │  ├─ ic_launcher.png
│  │  │  │  │  │        │  └─ ic_launcher_round.png
│  │  │  │  │  │        ├─ mipmap-mdpi-v4
│  │  │  │  │  │        │  ├─ ic_launcher.png
│  │  │  │  │  │        │  └─ ic_launcher_round.png
│  │  │  │  │  │        ├─ mipmap-xhdpi-v4
│  │  │  │  │  │        │  ├─ ic_launcher.png
│  │  │  │  │  │        │  └─ ic_launcher_round.png
│  │  │  │  │  │        ├─ mipmap-xxhdpi-v4
│  │  │  │  │  │        │  ├─ ic_launcher.png
│  │  │  │  │  │        │  └─ ic_launcher_round.png
│  │  │  │  │  │        ├─ mipmap-xxxhdpi-v4
│  │  │  │  │  │        │  ├─ ic_launcher.png
│  │  │  │  │  │        │  └─ ic_launcher_round.png
│  │  │  │  │  │        └─ values
│  │  │  │  │  │           └─ values.xml
│  │  │  │  │  ├─ project_dex_archive
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_0.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_1.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_2.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_3.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_4.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_5.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_6.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_7.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_8.jar
│  │  │  │  │  │           ├─ 990fd8704355a33b80dfbc89a81775f700c2abcf0c8a82bfd37a0e4e0357b21c_9.jar
│  │  │  │  │  │           └─ com
│  │  │  │  │  │              ├─ facebook
│  │  │  │  │  │              │  └─ react
│  │  │  │  │  │              │     └─ PackageList.dex
│  │  │  │  │  │              └─ myapp
│  │  │  │  │  │                 ├─ BuildConfig.dex
│  │  │  │  │  │                 ├─ MainActivity.dex
│  │  │  │  │  │                 ├─ MainApplication$reactNativeHost$1.dex
│  │  │  │  │  │                 └─ MainApplication.dex
│  │  │  │  │  ├─ runtime_symbol_list
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugResources
│  │  │  │  │  │        └─ R.txt
│  │  │  │  │  ├─ signing_config_versions
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ writeDebugSigningConfigVersions
│  │  │  │  │  │        └─ signing-config-versions.json
│  │  │  │  │  ├─ source_set_path_map
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ mapDebugSourceSetPaths
│  │  │  │  │  │        └─ file-map.txt
│  │  │  │  │  ├─ stable_resource_ids_file
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugResources
│  │  │  │  │  │        └─ stableIds.txt
│  │  │  │  │  ├─ stripped_native_libs
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ stripDebugDebugSymbols
│  │  │  │  │  │        └─ out
│  │  │  │  │  │           └─ lib
│  │  │  │  │  │              ├─ arm64-v8a
│  │  │  │  │  │              │  ├─ libappmodules.so
│  │  │  │  │  │              │  ├─ libc++_shared.so
│  │  │  │  │  │              │  ├─ libfbjni.so
│  │  │  │  │  │              │  ├─ libgesturehandler.so
│  │  │  │  │  │              │  ├─ libhermes.so
│  │  │  │  │  │              │  ├─ libhermestooling.so
│  │  │  │  │  │              │  ├─ libimagepipeline.so
│  │  │  │  │  │              │  ├─ libjsi.so
│  │  │  │  │  │              │  ├─ libmmkv.so
│  │  │  │  │  │              │  ├─ libnative-filters.so
│  │  │  │  │  │              │  ├─ libnative-imagetranscoder.so
│  │  │  │  │  │              │  ├─ libpdfium.so
│  │  │  │  │  │              │  ├─ libpdfiumandroid.so
│  │  │  │  │  │              │  ├─ libreactnative.so
│  │  │  │  │  │              │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │              │  ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │              │  ├─ libreanimated.so
│  │  │  │  │  │              │  ├─ librnscreens.so
│  │  │  │  │  │              │  └─ libworklets.so
│  │  │  │  │  │              ├─ armeabi-v7a
│  │  │  │  │  │              │  ├─ libappmodules.so
│  │  │  │  │  │              │  ├─ libc++_shared.so
│  │  │  │  │  │              │  ├─ libfbjni.so
│  │  │  │  │  │              │  ├─ libgesturehandler.so
│  │  │  │  │  │              │  ├─ libhermes.so
│  │  │  │  │  │              │  ├─ libhermestooling.so
│  │  │  │  │  │              │  ├─ libimagepipeline.so
│  │  │  │  │  │              │  ├─ libjsi.so
│  │  │  │  │  │              │  ├─ libmmkv.so
│  │  │  │  │  │              │  ├─ libnative-filters.so
│  │  │  │  │  │              │  ├─ libnative-imagetranscoder.so
│  │  │  │  │  │              │  ├─ libpdfium.so
│  │  │  │  │  │              │  ├─ libpdfiumandroid.so
│  │  │  │  │  │              │  ├─ libreactnative.so
│  │  │  │  │  │              │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │              │  ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │              │  ├─ libreanimated.so
│  │  │  │  │  │              │  ├─ librnscreens.so
│  │  │  │  │  │              │  └─ libworklets.so
│  │  │  │  │  │              ├─ x86
│  │  │  │  │  │              │  ├─ libappmodules.so
│  │  │  │  │  │              │  ├─ libc++_shared.so
│  │  │  │  │  │              │  ├─ libfbjni.so
│  │  │  │  │  │              │  ├─ libgesturehandler.so
│  │  │  │  │  │              │  ├─ libhermes.so
│  │  │  │  │  │              │  ├─ libhermestooling.so
│  │  │  │  │  │              │  ├─ libimagepipeline.so
│  │  │  │  │  │              │  ├─ libjsi.so
│  │  │  │  │  │              │  ├─ libmmkv.so
│  │  │  │  │  │              │  ├─ libnative-filters.so
│  │  │  │  │  │              │  ├─ libnative-imagetranscoder.so
│  │  │  │  │  │              │  ├─ libpdfium.so
│  │  │  │  │  │              │  ├─ libpdfiumandroid.so
│  │  │  │  │  │              │  ├─ libreactnative.so
│  │  │  │  │  │              │  ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │              │  ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │              │  ├─ libreanimated.so
│  │  │  │  │  │              │  ├─ librnscreens.so
│  │  │  │  │  │              │  └─ libworklets.so
│  │  │  │  │  │              └─ x86_64
│  │  │  │  │  │                 ├─ libappmodules.so
│  │  │  │  │  │                 ├─ libc++_shared.so
│  │  │  │  │  │                 ├─ libfbjni.so
│  │  │  │  │  │                 ├─ libgesturehandler.so
│  │  │  │  │  │                 ├─ libhermes.so
│  │  │  │  │  │                 ├─ libhermestooling.so
│  │  │  │  │  │                 ├─ libimagepipeline.so
│  │  │  │  │  │                 ├─ libjsi.so
│  │  │  │  │  │                 ├─ libmmkv.so
│  │  │  │  │  │                 ├─ libnative-filters.so
│  │  │  │  │  │                 ├─ libnative-imagetranscoder.so
│  │  │  │  │  │                 ├─ libpdfium.so
│  │  │  │  │  │                 ├─ libpdfiumandroid.so
│  │  │  │  │  │                 ├─ libreactnative.so
│  │  │  │  │  │                 ├─ libreact_codegen_rnscreens.so
│  │  │  │  │  │                 ├─ libreact_codegen_safeareacontext.so
│  │  │  │  │  │                 ├─ libreanimated.so
│  │  │  │  │  │                 ├─ librnscreens.so
│  │  │  │  │  │                 └─ libworklets.so
│  │  │  │  │  ├─ sub_project_dex_archive
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ dexBuilderDebug
│  │  │  │  │  │        └─ out
│  │  │  │  │  ├─ symbol_list_with_package_name
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     └─ processDebugResources
│  │  │  │  │  │        └─ package-aware-r.txt
│  │  │  │  │  └─ validate_signing_config
│  │  │  │  │     └─ debug
│  │  │  │  │        └─ validateSigningDebug
│  │  │  │  ├─ kotlin
│  │  │  │  │  └─ compileDebugKotlin
│  │  │  │  │     ├─ cacheable
│  │  │  │  │     │  ├─ caches-jvm
│  │  │  │  │     │  │  ├─ inputs
│  │  │  │  │     │  │  │  ├─ source-to-output.tab
│  │  │  │  │     │  │  │  ├─ source-to-output.tab.keystream
│  │  │  │  │     │  │  │  ├─ source-to-output.tab.keystream.len
│  │  │  │  │     │  │  │  ├─ source-to-output.tab.len
│  │  │  │  │     │  │  │  ├─ source-to-output.tab.values.at
│  │  │  │  │     │  │  │  ├─ source-to-output.tab_i
│  │  │  │  │     │  │  │  └─ source-to-output.tab_i.len
│  │  │  │  │     │  │  ├─ jvm
│  │  │  │  │     │  │  │  └─ kotlin
│  │  │  │  │     │  │  │     ├─ class-attributes.tab
│  │  │  │  │     │  │  │     ├─ class-attributes.tab.keystream
│  │  │  │  │     │  │  │     ├─ class-attributes.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ class-attributes.tab.len
│  │  │  │  │     │  │  │     ├─ class-attributes.tab.values.at
│  │  │  │  │     │  │  │     ├─ class-attributes.tab_i
│  │  │  │  │     │  │  │     ├─ class-attributes.tab_i.len
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab.keystream
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab.len
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab.values.at
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab_i
│  │  │  │  │     │  │  │     ├─ class-fq-name-to-source.tab_i.len
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab.keystream
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab.len
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab.values.at
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab_i
│  │  │  │  │     │  │  │     ├─ internal-name-to-source.tab_i.len
│  │  │  │  │     │  │  │     ├─ proto.tab
│  │  │  │  │     │  │  │     ├─ proto.tab.keystream
│  │  │  │  │     │  │  │     ├─ proto.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ proto.tab.len
│  │  │  │  │     │  │  │     ├─ proto.tab.values.at
│  │  │  │  │     │  │  │     ├─ proto.tab_i
│  │  │  │  │     │  │  │     ├─ proto.tab_i.len
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab.keystream
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab.len
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab.values.at
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab_i
│  │  │  │  │     │  │  │     ├─ source-to-classes.tab_i.len
│  │  │  │  │     │  │  │     ├─ subtypes.tab
│  │  │  │  │     │  │  │     ├─ subtypes.tab.keystream
│  │  │  │  │     │  │  │     ├─ subtypes.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ subtypes.tab.len
│  │  │  │  │     │  │  │     ├─ subtypes.tab.values.at
│  │  │  │  │     │  │  │     ├─ subtypes.tab_i
│  │  │  │  │     │  │  │     ├─ subtypes.tab_i.len
│  │  │  │  │     │  │  │     ├─ supertypes.tab
│  │  │  │  │     │  │  │     ├─ supertypes.tab.keystream
│  │  │  │  │     │  │  │     ├─ supertypes.tab.keystream.len
│  │  │  │  │     │  │  │     ├─ supertypes.tab.len
│  │  │  │  │     │  │  │     ├─ supertypes.tab.values.at
│  │  │  │  │     │  │  │     ├─ supertypes.tab_i
│  │  │  │  │     │  │  │     └─ supertypes.tab_i.len
│  │  │  │  │     │  │  └─ lookups
│  │  │  │  │     │  │     ├─ counters.tab
│  │  │  │  │     │  │     ├─ file-to-id.tab
│  │  │  │  │     │  │     ├─ file-to-id.tab.keystream
│  │  │  │  │     │  │     ├─ file-to-id.tab.keystream.len
│  │  │  │  │     │  │     ├─ file-to-id.tab.len
│  │  │  │  │     │  │     ├─ file-to-id.tab.values.at
│  │  │  │  │     │  │     ├─ file-to-id.tab_i
│  │  │  │  │     │  │     ├─ file-to-id.tab_i.len
│  │  │  │  │     │  │     ├─ id-to-file.tab
│  │  │  │  │     │  │     ├─ id-to-file.tab.keystream
│  │  │  │  │     │  │     ├─ id-to-file.tab.keystream.len
│  │  │  │  │     │  │     ├─ id-to-file.tab.len
│  │  │  │  │     │  │     ├─ id-to-file.tab.values.at
│  │  │  │  │     │  │     ├─ id-to-file.tab_i
│  │  │  │  │     │  │     ├─ id-to-file.tab_i.len
│  │  │  │  │     │  │     ├─ lookups.tab
│  │  │  │  │     │  │     ├─ lookups.tab.keystream
│  │  │  │  │     │  │     ├─ lookups.tab.keystream.len
│  │  │  │  │     │  │     ├─ lookups.tab.len
│  │  │  │  │     │  │     ├─ lookups.tab.values.at
│  │  │  │  │     │  │     ├─ lookups.tab_i
│  │  │  │  │     │  │     └─ lookups.tab_i.len
│  │  │  │  │     │  └─ last-build.bin
│  │  │  │  │     ├─ classpath-snapshot
│  │  │  │  │     │  └─ shrunk-classpath-snapshot.bin
│  │  │  │  │     └─ local-state
│  │  │  │  │        └─ build-history.bin
│  │  │  │  ├─ outputs
│  │  │  │  │  ├─ apk
│  │  │  │  │  │  └─ debug
│  │  │  │  │  │     ├─ app-debug.apk
│  │  │  │  │  │     └─ output-metadata.json
│  │  │  │  │  └─ logs
│  │  │  │  │     └─ manifest-merger-debug-report.txt
│  │  │  │  └─ tmp
│  │  │  │     ├─ compileDebugJavaWithJavac
│  │  │  │     │  ├─ compileTransaction
│  │  │  │     │  │  ├─ backup-dir
│  │  │  │     │  │  └─ stash-dir
│  │  │  │     │  │     └─ PackageList.class.uniqueId0
│  │  │  │     │  └─ previous-compilation-data.bin
│  │  │  │     └─ kotlin-classes
│  │  │  │        └─ debug
│  │  │  │           ├─ com
│  │  │  │           │  └─ myapp
│  │  │  │           │     ├─ MainActivity.class
│  │  │  │           │     ├─ MainApplication$reactNativeHost$1.class
│  │  │  │           │     └─ MainApplication.class
│  │  │  │           └─ META-INF
│  │  │  │              └─ app_debug.kotlin_module
│  │  │  ├─ build.gradle
│  │  │  ├─ debug.keystore
│  │  │  ├─ proguard-rules.pro
│  │  │  └─ src
│  │  │     ├─ debug
│  │  │     │  └─ AndroidManifest.xml
│  │  │     └─ main
│  │  │        ├─ AndroidManifest.xml
│  │  │        ├─ assets
│  │  │        │  └─ fonts
│  │  │        │     ├─ AntDesign.ttf
│  │  │        │     ├─ Entypo.ttf
│  │  │        │     ├─ EvilIcons.ttf
│  │  │        │     ├─ Feather.ttf
│  │  │        │     ├─ FontAwesome.ttf
│  │  │        │     ├─ FontAwesome5_Brands.ttf
│  │  │        │     ├─ FontAwesome5_Regular.ttf
│  │  │        │     ├─ FontAwesome5_Solid.ttf
│  │  │        │     ├─ FontAwesome6_Brands.ttf
│  │  │        │     ├─ FontAwesome6_Regular.ttf
│  │  │        │     ├─ FontAwesome6_Solid.ttf
│  │  │        │     ├─ Fontisto.ttf
│  │  │        │     ├─ Foundation.ttf
│  │  │        │     ├─ Ionicons.ttf
│  │  │        │     ├─ MaterialCommunityIcons.ttf
│  │  │        │     ├─ MaterialIcons.ttf
│  │  │        │     ├─ Octicons.ttf
│  │  │        │     ├─ SimpleLineIcons.ttf
│  │  │        │     └─ Zocial.ttf
│  │  │        ├─ java
│  │  │        │  └─ com
│  │  │        │     └─ myapp
│  │  │        │        ├─ MainActivity.kt
│  │  │        │        └─ MainApplication.kt
│  │  │        └─ res
│  │  │           ├─ drawable
│  │  │           │  └─ rn_edit_text_material.xml
│  │  │           ├─ mipmap-hdpi
│  │  │           │  ├─ ic_launcher.png
│  │  │           │  └─ ic_launcher_round.png
│  │  │           ├─ mipmap-mdpi
│  │  │           │  ├─ ic_launcher.png
│  │  │           │  └─ ic_launcher_round.png
│  │  │           ├─ mipmap-xhdpi
│  │  │           │  ├─ ic_launcher.png
│  │  │           │  └─ ic_launcher_round.png
│  │  │           ├─ mipmap-xxhdpi
│  │  │           │  ├─ ic_launcher.png
│  │  │           │  └─ ic_launcher_round.png
│  │  │           ├─ mipmap-xxxhdpi
│  │  │           │  ├─ ic_launcher.png
│  │  │           │  └─ ic_launcher_round.png
│  │  │           └─ values
│  │  │              ├─ strings.xml
│  │  │              └─ styles.xml
│  │  ├─ build
│  │  │  ├─ generated
│  │  │  │  └─ autolinking
│  │  │  │     ├─ autolinking.json
│  │  │  │     ├─ package-lock.json.sha
│  │  │  │     ├─ package.json.sha
│  │  │  │     └─ react-native.config.js.sha
│  │  │  └─ reports
│  │  │     └─ problems
│  │  │        └─ problems-report.html
│  │  ├─ build.gradle
│  │  ├─ gradle
│  │  │  └─ wrapper
│  │  │     ├─ gradle-wrapper.jar
│  │  │     └─ gradle-wrapper.properties
│  │  ├─ gradle.properties
│  │  ├─ gradlew
│  │  ├─ gradlew.bat
│  │  ├─ link-assets-manifest.json
│  │  └─ settings.gradle
│  ├─ app.json
│  ├─ App.tsx
│  ├─ babel.config.js
│  ├─ Gemfile
│  ├─ index.js
│  ├─ ios
│  │  ├─ .xcode.env
│  │  ├─ link-assets-manifest.json
│  │  ├─ MyApp
│  │  │  ├─ AppDelegate.swift
│  │  │  ├─ Images.xcassets
│  │  │  │  ├─ AppIcon.appiconset
│  │  │  │  │  └─ Contents.json
│  │  │  │  └─ Contents.json
│  │  │  ├─ Info.plist
│  │  │  ├─ LaunchScreen.storyboard
│  │  │  └─ PrivacyInfo.xcprivacy
│  │  ├─ MyApp.xcodeproj
│  │  │  ├─ project.pbxproj
│  │  │  └─ xcshareddata
│  │  │     └─ xcschemes
│  │  │        └─ MyApp.xcscheme
│  │  └─ Podfile
│  ├─ jest.config.js
│  ├─ metro.config.js
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ react-native.config.js
│  ├─ README.md
│  ├─ src
│  │  ├─ api.ts
│  │  ├─ contexts
│  │  │  ├─ CartContext.tsx
│  │  │  ├─ DownloadContext.tsx
│  │  │  ├─ ToastContext.tsx
│  │  │  └─ UserContext.tsx
│  │  ├─ models
│  │  │  ├─ BookModel.ts
│  │  │  ├─ BookOrder.ts
│  │  │  ├─ Cart.ts
│  │  │  └─ UserModel.ts
│  │  ├─ navigation
│  │  │  └─ types.ts
│  │  ├─ screens
│  │  │  ├─ base
│  │  │  │  ├─ BooksScreen.tsx
│  │  │  │  ├─ CartScreen.tsx
│  │  │  │  ├─ MyBooksScreen.tsx
│  │  │  │  ├─ MyOrdersScreen.tsx
│  │  │  │  ├─ panes
│  │  │  │  │  ├─ PurchasePane.tsx
│  │  │  │  │  └─ ReaderPane.tsx
│  │  │  │  └─ ProfileScreen.tsx
│  │  │  ├─ BaseScreen.tsx
│  │  │  ├─ BookDetailScreen.tsx
│  │  │  ├─ DownloadListScreen.tsx
│  │  │  ├─ LoginScreen.tsx
│  │  │  ├─ OrderDetailScreen.tsx
│  │  │  ├─ PurchaseHistoryScreen.tsx
│  │  │  ├─ RegisterScreen.tsx
│  │  │  └─ TopUpScreen.tsx
│  │  ├─ services
│  │  │  ├─ BookOrderService.ts
│  │  │  ├─ BookService.ts
│  │  │  ├─ DownloadService.ts
│  │  │  └─ UserService.ts
│  │  └─ utils
│  │     └─ db.ts
│  ├─ tsconfig.json
│  └─ __tests__
│     └─ App.test.tsx
└─ nec-book-desktop-app
   ├─ .venv
   │  ├─ Include
   │  ├─ Lib
   │  │  └─ site-packages
   │  │     ├─ pip
   │  │     │  ├─ py.typed
   │  │     │  ├─ _internal
   │  │     │  │  ├─ build_env.py
   │  │     │  │  ├─ cache.py
   │  │     │  │  ├─ cli
   │  │     │  │  │  ├─ autocompletion.py
   │  │     │  │  │  ├─ base_command.py
   │  │     │  │  │  ├─ cmdoptions.py
   │  │     │  │  │  ├─ command_context.py
   │  │     │  │  │  ├─ index_command.py
   │  │     │  │  │  ├─ main.py
   │  │     │  │  │  ├─ main_parser.py
   │  │     │  │  │  ├─ parser.py
   │  │     │  │  │  ├─ progress_bars.py
   │  │     │  │  │  ├─ req_command.py
   │  │     │  │  │  ├─ spinners.py
   │  │     │  │  │  ├─ status_codes.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ autocompletion.cpython-313.pyc
   │  │     │  │  │     ├─ base_command.cpython-313.pyc
   │  │     │  │  │     ├─ cmdoptions.cpython-313.pyc
   │  │     │  │  │     ├─ command_context.cpython-313.pyc
   │  │     │  │  │     ├─ index_command.cpython-313.pyc
   │  │     │  │  │     ├─ main.cpython-313.pyc
   │  │     │  │  │     ├─ main_parser.cpython-313.pyc
   │  │     │  │  │     ├─ parser.cpython-313.pyc
   │  │     │  │  │     ├─ progress_bars.cpython-313.pyc
   │  │     │  │  │     ├─ req_command.cpython-313.pyc
   │  │     │  │  │     ├─ spinners.cpython-313.pyc
   │  │     │  │  │     ├─ status_codes.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ commands
   │  │     │  │  │  ├─ cache.py
   │  │     │  │  │  ├─ check.py
   │  │     │  │  │  ├─ completion.py
   │  │     │  │  │  ├─ configuration.py
   │  │     │  │  │  ├─ debug.py
   │  │     │  │  │  ├─ download.py
   │  │     │  │  │  ├─ freeze.py
   │  │     │  │  │  ├─ hash.py
   │  │     │  │  │  ├─ help.py
   │  │     │  │  │  ├─ index.py
   │  │     │  │  │  ├─ inspect.py
   │  │     │  │  │  ├─ install.py
   │  │     │  │  │  ├─ list.py
   │  │     │  │  │  ├─ lock.py
   │  │     │  │  │  ├─ search.py
   │  │     │  │  │  ├─ show.py
   │  │     │  │  │  ├─ uninstall.py
   │  │     │  │  │  ├─ wheel.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ cache.cpython-313.pyc
   │  │     │  │  │     ├─ check.cpython-313.pyc
   │  │     │  │  │     ├─ completion.cpython-313.pyc
   │  │     │  │  │     ├─ configuration.cpython-313.pyc
   │  │     │  │  │     ├─ debug.cpython-313.pyc
   │  │     │  │  │     ├─ download.cpython-313.pyc
   │  │     │  │  │     ├─ freeze.cpython-313.pyc
   │  │     │  │  │     ├─ hash.cpython-313.pyc
   │  │     │  │  │     ├─ help.cpython-313.pyc
   │  │     │  │  │     ├─ index.cpython-313.pyc
   │  │     │  │  │     ├─ inspect.cpython-313.pyc
   │  │     │  │  │     ├─ install.cpython-313.pyc
   │  │     │  │  │     ├─ list.cpython-313.pyc
   │  │     │  │  │     ├─ lock.cpython-313.pyc
   │  │     │  │  │     ├─ search.cpython-313.pyc
   │  │     │  │  │     ├─ show.cpython-313.pyc
   │  │     │  │  │     ├─ uninstall.cpython-313.pyc
   │  │     │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ configuration.py
   │  │     │  │  ├─ distributions
   │  │     │  │  │  ├─ base.py
   │  │     │  │  │  ├─ installed.py
   │  │     │  │  │  ├─ sdist.py
   │  │     │  │  │  ├─ wheel.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ base.cpython-313.pyc
   │  │     │  │  │     ├─ installed.cpython-313.pyc
   │  │     │  │  │     ├─ sdist.cpython-313.pyc
   │  │     │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ exceptions.py
   │  │     │  │  ├─ index
   │  │     │  │  │  ├─ collector.py
   │  │     │  │  │  ├─ package_finder.py
   │  │     │  │  │  ├─ sources.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ collector.cpython-313.pyc
   │  │     │  │  │     ├─ package_finder.cpython-313.pyc
   │  │     │  │  │     ├─ sources.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ locations
   │  │     │  │  │  ├─ base.py
   │  │     │  │  │  ├─ _distutils.py
   │  │     │  │  │  ├─ _sysconfig.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ base.cpython-313.pyc
   │  │     │  │  │     ├─ _distutils.cpython-313.pyc
   │  │     │  │  │     ├─ _sysconfig.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ main.py
   │  │     │  │  ├─ metadata
   │  │     │  │  │  ├─ base.py
   │  │     │  │  │  ├─ importlib
   │  │     │  │  │  │  ├─ _compat.py
   │  │     │  │  │  │  ├─ _dists.py
   │  │     │  │  │  │  ├─ _envs.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ _compat.cpython-313.pyc
   │  │     │  │  │  │     ├─ _dists.cpython-313.pyc
   │  │     │  │  │  │     ├─ _envs.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ pkg_resources.py
   │  │     │  │  │  ├─ _json.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ base.cpython-313.pyc
   │  │     │  │  │     ├─ pkg_resources.cpython-313.pyc
   │  │     │  │  │     ├─ _json.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ models
   │  │     │  │  │  ├─ candidate.py
   │  │     │  │  │  ├─ direct_url.py
   │  │     │  │  │  ├─ format_control.py
   │  │     │  │  │  ├─ index.py
   │  │     │  │  │  ├─ installation_report.py
   │  │     │  │  │  ├─ link.py
   │  │     │  │  │  ├─ pylock.py
   │  │     │  │  │  ├─ scheme.py
   │  │     │  │  │  ├─ search_scope.py
   │  │     │  │  │  ├─ selection_prefs.py
   │  │     │  │  │  ├─ target_python.py
   │  │     │  │  │  ├─ wheel.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ candidate.cpython-313.pyc
   │  │     │  │  │     ├─ direct_url.cpython-313.pyc
   │  │     │  │  │     ├─ format_control.cpython-313.pyc
   │  │     │  │  │     ├─ index.cpython-313.pyc
   │  │     │  │  │     ├─ installation_report.cpython-313.pyc
   │  │     │  │  │     ├─ link.cpython-313.pyc
   │  │     │  │  │     ├─ pylock.cpython-313.pyc
   │  │     │  │  │     ├─ scheme.cpython-313.pyc
   │  │     │  │  │     ├─ search_scope.cpython-313.pyc
   │  │     │  │  │     ├─ selection_prefs.cpython-313.pyc
   │  │     │  │  │     ├─ target_python.cpython-313.pyc
   │  │     │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ network
   │  │     │  │  │  ├─ auth.py
   │  │     │  │  │  ├─ cache.py
   │  │     │  │  │  ├─ download.py
   │  │     │  │  │  ├─ lazy_wheel.py
   │  │     │  │  │  ├─ session.py
   │  │     │  │  │  ├─ utils.py
   │  │     │  │  │  ├─ xmlrpc.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ auth.cpython-313.pyc
   │  │     │  │  │     ├─ cache.cpython-313.pyc
   │  │     │  │  │     ├─ download.cpython-313.pyc
   │  │     │  │  │     ├─ lazy_wheel.cpython-313.pyc
   │  │     │  │  │     ├─ session.cpython-313.pyc
   │  │     │  │  │     ├─ utils.cpython-313.pyc
   │  │     │  │  │     ├─ xmlrpc.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ operations
   │  │     │  │  │  ├─ build
   │  │     │  │  │  │  ├─ build_tracker.py
   │  │     │  │  │  │  ├─ metadata.py
   │  │     │  │  │  │  ├─ metadata_editable.py
   │  │     │  │  │  │  ├─ metadata_legacy.py
   │  │     │  │  │  │  ├─ wheel.py
   │  │     │  │  │  │  ├─ wheel_editable.py
   │  │     │  │  │  │  ├─ wheel_legacy.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ build_tracker.cpython-313.pyc
   │  │     │  │  │  │     ├─ metadata.cpython-313.pyc
   │  │     │  │  │  │     ├─ metadata_editable.cpython-313.pyc
   │  │     │  │  │  │     ├─ metadata_legacy.cpython-313.pyc
   │  │     │  │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │  │     ├─ wheel_editable.cpython-313.pyc
   │  │     │  │  │  │     ├─ wheel_legacy.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ check.py
   │  │     │  │  │  ├─ freeze.py
   │  │     │  │  │  ├─ install
   │  │     │  │  │  │  ├─ editable_legacy.py
   │  │     │  │  │  │  ├─ wheel.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ editable_legacy.cpython-313.pyc
   │  │     │  │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ prepare.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ check.cpython-313.pyc
   │  │     │  │  │     ├─ freeze.cpython-313.pyc
   │  │     │  │  │     ├─ prepare.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ pyproject.py
   │  │     │  │  ├─ req
   │  │     │  │  │  ├─ constructors.py
   │  │     │  │  │  ├─ req_dependency_group.py
   │  │     │  │  │  ├─ req_file.py
   │  │     │  │  │  ├─ req_install.py
   │  │     │  │  │  ├─ req_set.py
   │  │     │  │  │  ├─ req_uninstall.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ constructors.cpython-313.pyc
   │  │     │  │  │     ├─ req_dependency_group.cpython-313.pyc
   │  │     │  │  │     ├─ req_file.cpython-313.pyc
   │  │     │  │  │     ├─ req_install.cpython-313.pyc
   │  │     │  │  │     ├─ req_set.cpython-313.pyc
   │  │     │  │  │     ├─ req_uninstall.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ resolution
   │  │     │  │  │  ├─ base.py
   │  │     │  │  │  ├─ legacy
   │  │     │  │  │  │  ├─ resolver.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ resolver.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ resolvelib
   │  │     │  │  │  │  ├─ base.py
   │  │     │  │  │  │  ├─ candidates.py
   │  │     │  │  │  │  ├─ factory.py
   │  │     │  │  │  │  ├─ found_candidates.py
   │  │     │  │  │  │  ├─ provider.py
   │  │     │  │  │  │  ├─ reporter.py
   │  │     │  │  │  │  ├─ requirements.py
   │  │     │  │  │  │  ├─ resolver.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ base.cpython-313.pyc
   │  │     │  │  │  │     ├─ candidates.cpython-313.pyc
   │  │     │  │  │  │     ├─ factory.cpython-313.pyc
   │  │     │  │  │  │     ├─ found_candidates.cpython-313.pyc
   │  │     │  │  │  │     ├─ provider.cpython-313.pyc
   │  │     │  │  │  │     ├─ reporter.cpython-313.pyc
   │  │     │  │  │  │     ├─ requirements.cpython-313.pyc
   │  │     │  │  │  │     ├─ resolver.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ base.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ self_outdated_check.py
   │  │     │  │  ├─ utils
   │  │     │  │  │  ├─ appdirs.py
   │  │     │  │  │  ├─ compat.py
   │  │     │  │  │  ├─ compatibility_tags.py
   │  │     │  │  │  ├─ datetime.py
   │  │     │  │  │  ├─ deprecation.py
   │  │     │  │  │  ├─ direct_url_helpers.py
   │  │     │  │  │  ├─ egg_link.py
   │  │     │  │  │  ├─ entrypoints.py
   │  │     │  │  │  ├─ filesystem.py
   │  │     │  │  │  ├─ filetypes.py
   │  │     │  │  │  ├─ glibc.py
   │  │     │  │  │  ├─ hashes.py
   │  │     │  │  │  ├─ logging.py
   │  │     │  │  │  ├─ misc.py
   │  │     │  │  │  ├─ packaging.py
   │  │     │  │  │  ├─ retry.py
   │  │     │  │  │  ├─ setuptools_build.py
   │  │     │  │  │  ├─ subprocess.py
   │  │     │  │  │  ├─ temp_dir.py
   │  │     │  │  │  ├─ unpacking.py
   │  │     │  │  │  ├─ urls.py
   │  │     │  │  │  ├─ virtualenv.py
   │  │     │  │  │  ├─ wheel.py
   │  │     │  │  │  ├─ _jaraco_text.py
   │  │     │  │  │  ├─ _log.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ appdirs.cpython-313.pyc
   │  │     │  │  │     ├─ compat.cpython-313.pyc
   │  │     │  │  │     ├─ compatibility_tags.cpython-313.pyc
   │  │     │  │  │     ├─ datetime.cpython-313.pyc
   │  │     │  │  │     ├─ deprecation.cpython-313.pyc
   │  │     │  │  │     ├─ direct_url_helpers.cpython-313.pyc
   │  │     │  │  │     ├─ egg_link.cpython-313.pyc
   │  │     │  │  │     ├─ entrypoints.cpython-313.pyc
   │  │     │  │  │     ├─ filesystem.cpython-313.pyc
   │  │     │  │  │     ├─ filetypes.cpython-313.pyc
   │  │     │  │  │     ├─ glibc.cpython-313.pyc
   │  │     │  │  │     ├─ hashes.cpython-313.pyc
   │  │     │  │  │     ├─ logging.cpython-313.pyc
   │  │     │  │  │     ├─ misc.cpython-313.pyc
   │  │     │  │  │     ├─ packaging.cpython-313.pyc
   │  │     │  │  │     ├─ retry.cpython-313.pyc
   │  │     │  │  │     ├─ setuptools_build.cpython-313.pyc
   │  │     │  │  │     ├─ subprocess.cpython-313.pyc
   │  │     │  │  │     ├─ temp_dir.cpython-313.pyc
   │  │     │  │  │     ├─ unpacking.cpython-313.pyc
   │  │     │  │  │     ├─ urls.cpython-313.pyc
   │  │     │  │  │     ├─ virtualenv.cpython-313.pyc
   │  │     │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │     ├─ _jaraco_text.cpython-313.pyc
   │  │     │  │  │     ├─ _log.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ vcs
   │  │     │  │  │  ├─ bazaar.py
   │  │     │  │  │  ├─ git.py
   │  │     │  │  │  ├─ mercurial.py
   │  │     │  │  │  ├─ subversion.py
   │  │     │  │  │  ├─ versioncontrol.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ bazaar.cpython-313.pyc
   │  │     │  │  │     ├─ git.cpython-313.pyc
   │  │     │  │  │     ├─ mercurial.cpython-313.pyc
   │  │     │  │  │     ├─ subversion.cpython-313.pyc
   │  │     │  │  │     ├─ versioncontrol.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ wheel_builder.py
   │  │     │  │  ├─ __init__.py
   │  │     │  │  └─ __pycache__
   │  │     │  │     ├─ build_env.cpython-313.pyc
   │  │     │  │     ├─ cache.cpython-313.pyc
   │  │     │  │     ├─ configuration.cpython-313.pyc
   │  │     │  │     ├─ exceptions.cpython-313.pyc
   │  │     │  │     ├─ main.cpython-313.pyc
   │  │     │  │     ├─ pyproject.cpython-313.pyc
   │  │     │  │     ├─ self_outdated_check.cpython-313.pyc
   │  │     │  │     ├─ wheel_builder.cpython-313.pyc
   │  │     │  │     └─ __init__.cpython-313.pyc
   │  │     │  ├─ _vendor
   │  │     │  │  ├─ cachecontrol
   │  │     │  │  │  ├─ adapter.py
   │  │     │  │  │  ├─ cache.py
   │  │     │  │  │  ├─ caches
   │  │     │  │  │  │  ├─ file_cache.py
   │  │     │  │  │  │  ├─ redis_cache.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ file_cache.cpython-313.pyc
   │  │     │  │  │  │     ├─ redis_cache.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ controller.py
   │  │     │  │  │  ├─ filewrapper.py
   │  │     │  │  │  ├─ heuristics.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ serialize.py
   │  │     │  │  │  ├─ wrapper.py
   │  │     │  │  │  ├─ _cmd.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ adapter.cpython-313.pyc
   │  │     │  │  │     ├─ cache.cpython-313.pyc
   │  │     │  │  │     ├─ controller.cpython-313.pyc
   │  │     │  │  │     ├─ filewrapper.cpython-313.pyc
   │  │     │  │  │     ├─ heuristics.cpython-313.pyc
   │  │     │  │  │     ├─ serialize.cpython-313.pyc
   │  │     │  │  │     ├─ wrapper.cpython-313.pyc
   │  │     │  │  │     ├─ _cmd.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ certifi
   │  │     │  │  │  ├─ cacert.pem
   │  │     │  │  │  ├─ core.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __main__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ core.cpython-313.pyc
   │  │     │  │  │     ├─ __init__.cpython-313.pyc
   │  │     │  │  │     └─ __main__.cpython-313.pyc
   │  │     │  │  ├─ dependency_groups
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ _implementation.py
   │  │     │  │  │  ├─ _lint_dependency_groups.py
   │  │     │  │  │  ├─ _pip_wrapper.py
   │  │     │  │  │  ├─ _toml_compat.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __main__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ _implementation.cpython-313.pyc
   │  │     │  │  │     ├─ _lint_dependency_groups.cpython-313.pyc
   │  │     │  │  │     ├─ _pip_wrapper.cpython-313.pyc
   │  │     │  │  │     ├─ _toml_compat.cpython-313.pyc
   │  │     │  │  │     ├─ __init__.cpython-313.pyc
   │  │     │  │  │     └─ __main__.cpython-313.pyc
   │  │     │  │  ├─ distlib
   │  │     │  │  │  ├─ compat.py
   │  │     │  │  │  ├─ database.py
   │  │     │  │  │  ├─ index.py
   │  │     │  │  │  ├─ locators.py
   │  │     │  │  │  ├─ manifest.py
   │  │     │  │  │  ├─ markers.py
   │  │     │  │  │  ├─ metadata.py
   │  │     │  │  │  ├─ resources.py
   │  │     │  │  │  ├─ scripts.py
   │  │     │  │  │  ├─ t32.exe
   │  │     │  │  │  ├─ t64-arm.exe
   │  │     │  │  │  ├─ t64.exe
   │  │     │  │  │  ├─ util.py
   │  │     │  │  │  ├─ version.py
   │  │     │  │  │  ├─ w32.exe
   │  │     │  │  │  ├─ w64-arm.exe
   │  │     │  │  │  ├─ w64.exe
   │  │     │  │  │  ├─ wheel.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ compat.cpython-313.pyc
   │  │     │  │  │     ├─ database.cpython-313.pyc
   │  │     │  │  │     ├─ index.cpython-313.pyc
   │  │     │  │  │     ├─ locators.cpython-313.pyc
   │  │     │  │  │     ├─ manifest.cpython-313.pyc
   │  │     │  │  │     ├─ markers.cpython-313.pyc
   │  │     │  │  │     ├─ metadata.cpython-313.pyc
   │  │     │  │  │     ├─ resources.cpython-313.pyc
   │  │     │  │  │     ├─ scripts.cpython-313.pyc
   │  │     │  │  │     ├─ util.cpython-313.pyc
   │  │     │  │  │     ├─ version.cpython-313.pyc
   │  │     │  │  │     ├─ wheel.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ distro
   │  │     │  │  │  ├─ distro.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __main__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ distro.cpython-313.pyc
   │  │     │  │  │     ├─ __init__.cpython-313.pyc
   │  │     │  │  │     └─ __main__.cpython-313.pyc
   │  │     │  │  ├─ idna
   │  │     │  │  │  ├─ codec.py
   │  │     │  │  │  ├─ compat.py
   │  │     │  │  │  ├─ core.py
   │  │     │  │  │  ├─ idnadata.py
   │  │     │  │  │  ├─ intranges.py
   │  │     │  │  │  ├─ package_data.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ uts46data.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ codec.cpython-313.pyc
   │  │     │  │  │     ├─ compat.cpython-313.pyc
   │  │     │  │  │     ├─ core.cpython-313.pyc
   │  │     │  │  │     ├─ idnadata.cpython-313.pyc
   │  │     │  │  │     ├─ intranges.cpython-313.pyc
   │  │     │  │  │     ├─ package_data.cpython-313.pyc
   │  │     │  │  │     ├─ uts46data.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ msgpack
   │  │     │  │  │  ├─ exceptions.py
   │  │     │  │  │  ├─ ext.py
   │  │     │  │  │  ├─ fallback.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ exceptions.cpython-313.pyc
   │  │     │  │  │     ├─ ext.cpython-313.pyc
   │  │     │  │  │     ├─ fallback.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ packaging
   │  │     │  │  │  ├─ licenses
   │  │     │  │  │  │  ├─ _spdx.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ _spdx.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ markers.py
   │  │     │  │  │  ├─ metadata.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ requirements.py
   │  │     │  │  │  ├─ specifiers.py
   │  │     │  │  │  ├─ tags.py
   │  │     │  │  │  ├─ utils.py
   │  │     │  │  │  ├─ version.py
   │  │     │  │  │  ├─ _elffile.py
   │  │     │  │  │  ├─ _manylinux.py
   │  │     │  │  │  ├─ _musllinux.py
   │  │     │  │  │  ├─ _parser.py
   │  │     │  │  │  ├─ _structures.py
   │  │     │  │  │  ├─ _tokenizer.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ markers.cpython-313.pyc
   │  │     │  │  │     ├─ metadata.cpython-313.pyc
   │  │     │  │  │     ├─ requirements.cpython-313.pyc
   │  │     │  │  │     ├─ specifiers.cpython-313.pyc
   │  │     │  │  │     ├─ tags.cpython-313.pyc
   │  │     │  │  │     ├─ utils.cpython-313.pyc
   │  │     │  │  │     ├─ version.cpython-313.pyc
   │  │     │  │  │     ├─ _elffile.cpython-313.pyc
   │  │     │  │  │     ├─ _manylinux.cpython-313.pyc
   │  │     │  │  │     ├─ _musllinux.cpython-313.pyc
   │  │     │  │  │     ├─ _parser.cpython-313.pyc
   │  │     │  │  │     ├─ _structures.cpython-313.pyc
   │  │     │  │  │     ├─ _tokenizer.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ pkg_resources
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ platformdirs
   │  │     │  │  │  ├─ android.py
   │  │     │  │  │  ├─ api.py
   │  │     │  │  │  ├─ macos.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ unix.py
   │  │     │  │  │  ├─ version.py
   │  │     │  │  │  ├─ windows.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __main__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ android.cpython-313.pyc
   │  │     │  │  │     ├─ api.cpython-313.pyc
   │  │     │  │  │     ├─ macos.cpython-313.pyc
   │  │     │  │  │     ├─ unix.cpython-313.pyc
   │  │     │  │  │     ├─ version.cpython-313.pyc
   │  │     │  │  │     ├─ windows.cpython-313.pyc
   │  │     │  │  │     ├─ __init__.cpython-313.pyc
   │  │     │  │  │     └─ __main__.cpython-313.pyc
   │  │     │  │  ├─ pygments
   │  │     │  │  │  ├─ console.py
   │  │     │  │  │  ├─ filter.py
   │  │     │  │  │  ├─ filters
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ formatter.py
   │  │     │  │  │  ├─ formatters
   │  │     │  │  │  │  ├─ _mapping.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ _mapping.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ lexer.py
   │  │     │  │  │  ├─ lexers
   │  │     │  │  │  │  ├─ python.py
   │  │     │  │  │  │  ├─ _mapping.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ python.cpython-313.pyc
   │  │     │  │  │  │     ├─ _mapping.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ modeline.py
   │  │     │  │  │  ├─ plugin.py
   │  │     │  │  │  ├─ regexopt.py
   │  │     │  │  │  ├─ scanner.py
   │  │     │  │  │  ├─ sphinxext.py
   │  │     │  │  │  ├─ style.py
   │  │     │  │  │  ├─ styles
   │  │     │  │  │  │  ├─ _mapping.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ _mapping.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ token.py
   │  │     │  │  │  ├─ unistring.py
   │  │     │  │  │  ├─ util.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __main__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ console.cpython-313.pyc
   │  │     │  │  │     ├─ filter.cpython-313.pyc
   │  │     │  │  │     ├─ formatter.cpython-313.pyc
   │  │     │  │  │     ├─ lexer.cpython-313.pyc
   │  │     │  │  │     ├─ modeline.cpython-313.pyc
   │  │     │  │  │     ├─ plugin.cpython-313.pyc
   │  │     │  │  │     ├─ regexopt.cpython-313.pyc
   │  │     │  │  │     ├─ scanner.cpython-313.pyc
   │  │     │  │  │     ├─ sphinxext.cpython-313.pyc
   │  │     │  │  │     ├─ style.cpython-313.pyc
   │  │     │  │  │     ├─ token.cpython-313.pyc
   │  │     │  │  │     ├─ unistring.cpython-313.pyc
   │  │     │  │  │     ├─ util.cpython-313.pyc
   │  │     │  │  │     ├─ __init__.cpython-313.pyc
   │  │     │  │  │     └─ __main__.cpython-313.pyc
   │  │     │  │  ├─ pyproject_hooks
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ _impl.py
   │  │     │  │  │  ├─ _in_process
   │  │     │  │  │  │  ├─ _in_process.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ _in_process.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ _impl.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ requests
   │  │     │  │  │  ├─ adapters.py
   │  │     │  │  │  ├─ api.py
   │  │     │  │  │  ├─ auth.py
   │  │     │  │  │  ├─ certs.py
   │  │     │  │  │  ├─ compat.py
   │  │     │  │  │  ├─ cookies.py
   │  │     │  │  │  ├─ exceptions.py
   │  │     │  │  │  ├─ help.py
   │  │     │  │  │  ├─ hooks.py
   │  │     │  │  │  ├─ models.py
   │  │     │  │  │  ├─ packages.py
   │  │     │  │  │  ├─ sessions.py
   │  │     │  │  │  ├─ status_codes.py
   │  │     │  │  │  ├─ structures.py
   │  │     │  │  │  ├─ utils.py
   │  │     │  │  │  ├─ _internal_utils.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __pycache__
   │  │     │  │  │  │  ├─ adapters.cpython-313.pyc
   │  │     │  │  │  │  ├─ api.cpython-313.pyc
   │  │     │  │  │  │  ├─ auth.cpython-313.pyc
   │  │     │  │  │  │  ├─ certs.cpython-313.pyc
   │  │     │  │  │  │  ├─ compat.cpython-313.pyc
   │  │     │  │  │  │  ├─ cookies.cpython-313.pyc
   │  │     │  │  │  │  ├─ exceptions.cpython-313.pyc
   │  │     │  │  │  │  ├─ help.cpython-313.pyc
   │  │     │  │  │  │  ├─ hooks.cpython-313.pyc
   │  │     │  │  │  │  ├─ models.cpython-313.pyc
   │  │     │  │  │  │  ├─ packages.cpython-313.pyc
   │  │     │  │  │  │  ├─ sessions.cpython-313.pyc
   │  │     │  │  │  │  ├─ status_codes.cpython-313.pyc
   │  │     │  │  │  │  ├─ structures.cpython-313.pyc
   │  │     │  │  │  │  ├─ utils.cpython-313.pyc
   │  │     │  │  │  │  ├─ _internal_utils.cpython-313.pyc
   │  │     │  │  │  │  ├─ __init__.cpython-313.pyc
   │  │     │  │  │  │  └─ __version__.cpython-313.pyc
   │  │     │  │  │  └─ __version__.py
   │  │     │  │  ├─ resolvelib
   │  │     │  │  │  ├─ providers.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ reporters.py
   │  │     │  │  │  ├─ resolvers
   │  │     │  │  │  │  ├─ abstract.py
   │  │     │  │  │  │  ├─ criterion.py
   │  │     │  │  │  │  ├─ exceptions.py
   │  │     │  │  │  │  ├─ resolution.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ abstract.cpython-313.pyc
   │  │     │  │  │  │     ├─ criterion.cpython-313.pyc
   │  │     │  │  │  │     ├─ exceptions.cpython-313.pyc
   │  │     │  │  │  │     ├─ resolution.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ structs.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ providers.cpython-313.pyc
   │  │     │  │  │     ├─ reporters.cpython-313.pyc
   │  │     │  │  │     ├─ structs.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ rich
   │  │     │  │  │  ├─ abc.py
   │  │     │  │  │  ├─ align.py
   │  │     │  │  │  ├─ ansi.py
   │  │     │  │  │  ├─ bar.py
   │  │     │  │  │  ├─ box.py
   │  │     │  │  │  ├─ cells.py
   │  │     │  │  │  ├─ color.py
   │  │     │  │  │  ├─ color_triplet.py
   │  │     │  │  │  ├─ columns.py
   │  │     │  │  │  ├─ console.py
   │  │     │  │  │  ├─ constrain.py
   │  │     │  │  │  ├─ containers.py
   │  │     │  │  │  ├─ control.py
   │  │     │  │  │  ├─ default_styles.py
   │  │     │  │  │  ├─ diagnose.py
   │  │     │  │  │  ├─ emoji.py
   │  │     │  │  │  ├─ errors.py
   │  │     │  │  │  ├─ filesize.py
   │  │     │  │  │  ├─ file_proxy.py
   │  │     │  │  │  ├─ highlighter.py
   │  │     │  │  │  ├─ json.py
   │  │     │  │  │  ├─ jupyter.py
   │  │     │  │  │  ├─ layout.py
   │  │     │  │  │  ├─ live.py
   │  │     │  │  │  ├─ live_render.py
   │  │     │  │  │  ├─ logging.py
   │  │     │  │  │  ├─ markup.py
   │  │     │  │  │  ├─ measure.py
   │  │     │  │  │  ├─ padding.py
   │  │     │  │  │  ├─ pager.py
   │  │     │  │  │  ├─ palette.py
   │  │     │  │  │  ├─ panel.py
   │  │     │  │  │  ├─ pretty.py
   │  │     │  │  │  ├─ progress.py
   │  │     │  │  │  ├─ progress_bar.py
   │  │     │  │  │  ├─ prompt.py
   │  │     │  │  │  ├─ protocol.py
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ region.py
   │  │     │  │  │  ├─ repr.py
   │  │     │  │  │  ├─ rule.py
   │  │     │  │  │  ├─ scope.py
   │  │     │  │  │  ├─ screen.py
   │  │     │  │  │  ├─ segment.py
   │  │     │  │  │  ├─ spinner.py
   │  │     │  │  │  ├─ status.py
   │  │     │  │  │  ├─ style.py
   │  │     │  │  │  ├─ styled.py
   │  │     │  │  │  ├─ syntax.py
   │  │     │  │  │  ├─ table.py
   │  │     │  │  │  ├─ terminal_theme.py
   │  │     │  │  │  ├─ text.py
   │  │     │  │  │  ├─ theme.py
   │  │     │  │  │  ├─ themes.py
   │  │     │  │  │  ├─ traceback.py
   │  │     │  │  │  ├─ tree.py
   │  │     │  │  │  ├─ _cell_widths.py
   │  │     │  │  │  ├─ _emoji_codes.py
   │  │     │  │  │  ├─ _emoji_replace.py
   │  │     │  │  │  ├─ _export_format.py
   │  │     │  │  │  ├─ _extension.py
   │  │     │  │  │  ├─ _fileno.py
   │  │     │  │  │  ├─ _inspect.py
   │  │     │  │  │  ├─ _log_render.py
   │  │     │  │  │  ├─ _loop.py
   │  │     │  │  │  ├─ _null_file.py
   │  │     │  │  │  ├─ _palettes.py
   │  │     │  │  │  ├─ _pick.py
   │  │     │  │  │  ├─ _ratio.py
   │  │     │  │  │  ├─ _spinners.py
   │  │     │  │  │  ├─ _stack.py
   │  │     │  │  │  ├─ _timer.py
   │  │     │  │  │  ├─ _win32_console.py
   │  │     │  │  │  ├─ _windows.py
   │  │     │  │  │  ├─ _windows_renderer.py
   │  │     │  │  │  ├─ _wrap.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  ├─ __main__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ abc.cpython-313.pyc
   │  │     │  │  │     ├─ align.cpython-313.pyc
   │  │     │  │  │     ├─ ansi.cpython-313.pyc
   │  │     │  │  │     ├─ bar.cpython-313.pyc
   │  │     │  │  │     ├─ box.cpython-313.pyc
   │  │     │  │  │     ├─ cells.cpython-313.pyc
   │  │     │  │  │     ├─ color.cpython-313.pyc
   │  │     │  │  │     ├─ color_triplet.cpython-313.pyc
   │  │     │  │  │     ├─ columns.cpython-313.pyc
   │  │     │  │  │     ├─ console.cpython-313.pyc
   │  │     │  │  │     ├─ constrain.cpython-313.pyc
   │  │     │  │  │     ├─ containers.cpython-313.pyc
   │  │     │  │  │     ├─ control.cpython-313.pyc
   │  │     │  │  │     ├─ default_styles.cpython-313.pyc
   │  │     │  │  │     ├─ diagnose.cpython-313.pyc
   │  │     │  │  │     ├─ emoji.cpython-313.pyc
   │  │     │  │  │     ├─ errors.cpython-313.pyc
   │  │     │  │  │     ├─ filesize.cpython-313.pyc
   │  │     │  │  │     ├─ file_proxy.cpython-313.pyc
   │  │     │  │  │     ├─ highlighter.cpython-313.pyc
   │  │     │  │  │     ├─ json.cpython-313.pyc
   │  │     │  │  │     ├─ jupyter.cpython-313.pyc
   │  │     │  │  │     ├─ layout.cpython-313.pyc
   │  │     │  │  │     ├─ live.cpython-313.pyc
   │  │     │  │  │     ├─ live_render.cpython-313.pyc
   │  │     │  │  │     ├─ logging.cpython-313.pyc
   │  │     │  │  │     ├─ markup.cpython-313.pyc
   │  │     │  │  │     ├─ measure.cpython-313.pyc
   │  │     │  │  │     ├─ padding.cpython-313.pyc
   │  │     │  │  │     ├─ pager.cpython-313.pyc
   │  │     │  │  │     ├─ palette.cpython-313.pyc
   │  │     │  │  │     ├─ panel.cpython-313.pyc
   │  │     │  │  │     ├─ pretty.cpython-313.pyc
   │  │     │  │  │     ├─ progress.cpython-313.pyc
   │  │     │  │  │     ├─ progress_bar.cpython-313.pyc
   │  │     │  │  │     ├─ prompt.cpython-313.pyc
   │  │     │  │  │     ├─ protocol.cpython-313.pyc
   │  │     │  │  │     ├─ region.cpython-313.pyc
   │  │     │  │  │     ├─ repr.cpython-313.pyc
   │  │     │  │  │     ├─ rule.cpython-313.pyc
   │  │     │  │  │     ├─ scope.cpython-313.pyc
   │  │     │  │  │     ├─ screen.cpython-313.pyc
   │  │     │  │  │     ├─ segment.cpython-313.pyc
   │  │     │  │  │     ├─ spinner.cpython-313.pyc
   │  │     │  │  │     ├─ status.cpython-313.pyc
   │  │     │  │  │     ├─ style.cpython-313.pyc
   │  │     │  │  │     ├─ styled.cpython-313.pyc
   │  │     │  │  │     ├─ syntax.cpython-313.pyc
   │  │     │  │  │     ├─ table.cpython-313.pyc
   │  │     │  │  │     ├─ terminal_theme.cpython-313.pyc
   │  │     │  │  │     ├─ text.cpython-313.pyc
   │  │     │  │  │     ├─ theme.cpython-313.pyc
   │  │     │  │  │     ├─ themes.cpython-313.pyc
   │  │     │  │  │     ├─ traceback.cpython-313.pyc
   │  │     │  │  │     ├─ tree.cpython-313.pyc
   │  │     │  │  │     ├─ _cell_widths.cpython-313.pyc
   │  │     │  │  │     ├─ _emoji_codes.cpython-313.pyc
   │  │     │  │  │     ├─ _emoji_replace.cpython-313.pyc
   │  │     │  │  │     ├─ _export_format.cpython-313.pyc
   │  │     │  │  │     ├─ _extension.cpython-313.pyc
   │  │     │  │  │     ├─ _fileno.cpython-313.pyc
   │  │     │  │  │     ├─ _inspect.cpython-313.pyc
   │  │     │  │  │     ├─ _log_render.cpython-313.pyc
   │  │     │  │  │     ├─ _loop.cpython-313.pyc
   │  │     │  │  │     ├─ _null_file.cpython-313.pyc
   │  │     │  │  │     ├─ _palettes.cpython-313.pyc
   │  │     │  │  │     ├─ _pick.cpython-313.pyc
   │  │     │  │  │     ├─ _ratio.cpython-313.pyc
   │  │     │  │  │     ├─ _spinners.cpython-313.pyc
   │  │     │  │  │     ├─ _stack.cpython-313.pyc
   │  │     │  │  │     ├─ _timer.cpython-313.pyc
   │  │     │  │  │     ├─ _win32_console.cpython-313.pyc
   │  │     │  │  │     ├─ _windows.cpython-313.pyc
   │  │     │  │  │     ├─ _windows_renderer.cpython-313.pyc
   │  │     │  │  │     ├─ _wrap.cpython-313.pyc
   │  │     │  │  │     ├─ __init__.cpython-313.pyc
   │  │     │  │  │     └─ __main__.cpython-313.pyc
   │  │     │  │  ├─ tomli
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ _parser.py
   │  │     │  │  │  ├─ _re.py
   │  │     │  │  │  ├─ _types.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ _parser.cpython-313.pyc
   │  │     │  │  │     ├─ _re.cpython-313.pyc
   │  │     │  │  │     ├─ _types.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ tomli_w
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ _writer.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ _writer.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ truststore
   │  │     │  │  │  ├─ py.typed
   │  │     │  │  │  ├─ _api.py
   │  │     │  │  │  ├─ _macos.py
   │  │     │  │  │  ├─ _openssl.py
   │  │     │  │  │  ├─ _ssl_constants.py
   │  │     │  │  │  ├─ _windows.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ _api.cpython-313.pyc
   │  │     │  │  │     ├─ _macos.cpython-313.pyc
   │  │     │  │  │     ├─ _openssl.cpython-313.pyc
   │  │     │  │  │     ├─ _ssl_constants.cpython-313.pyc
   │  │     │  │  │     ├─ _windows.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ typing_extensions.py
   │  │     │  │  ├─ urllib3
   │  │     │  │  │  ├─ connection.py
   │  │     │  │  │  ├─ connectionpool.py
   │  │     │  │  │  ├─ contrib
   │  │     │  │  │  │  ├─ appengine.py
   │  │     │  │  │  │  ├─ ntlmpool.py
   │  │     │  │  │  │  ├─ pyopenssl.py
   │  │     │  │  │  │  ├─ securetransport.py
   │  │     │  │  │  │  ├─ socks.py
   │  │     │  │  │  │  ├─ _appengine_environ.py
   │  │     │  │  │  │  ├─ _securetransport
   │  │     │  │  │  │  │  ├─ bindings.py
   │  │     │  │  │  │  │  ├─ low_level.py
   │  │     │  │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  │  └─ __pycache__
   │  │     │  │  │  │  │     ├─ bindings.cpython-313.pyc
   │  │     │  │  │  │  │     ├─ low_level.cpython-313.pyc
   │  │     │  │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ appengine.cpython-313.pyc
   │  │     │  │  │  │     ├─ ntlmpool.cpython-313.pyc
   │  │     │  │  │  │     ├─ pyopenssl.cpython-313.pyc
   │  │     │  │  │  │     ├─ securetransport.cpython-313.pyc
   │  │     │  │  │  │     ├─ socks.cpython-313.pyc
   │  │     │  │  │  │     ├─ _appengine_environ.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ exceptions.py
   │  │     │  │  │  ├─ fields.py
   │  │     │  │  │  ├─ filepost.py
   │  │     │  │  │  ├─ packages
   │  │     │  │  │  │  ├─ backports
   │  │     │  │  │  │  │  ├─ makefile.py
   │  │     │  │  │  │  │  ├─ weakref_finalize.py
   │  │     │  │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  │  └─ __pycache__
   │  │     │  │  │  │  │     ├─ makefile.cpython-313.pyc
   │  │     │  │  │  │  │     ├─ weakref_finalize.cpython-313.pyc
   │  │     │  │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  │  ├─ six.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ six.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ poolmanager.py
   │  │     │  │  │  ├─ request.py
   │  │     │  │  │  ├─ response.py
   │  │     │  │  │  ├─ util
   │  │     │  │  │  │  ├─ connection.py
   │  │     │  │  │  │  ├─ proxy.py
   │  │     │  │  │  │  ├─ queue.py
   │  │     │  │  │  │  ├─ request.py
   │  │     │  │  │  │  ├─ response.py
   │  │     │  │  │  │  ├─ retry.py
   │  │     │  │  │  │  ├─ ssltransport.py
   │  │     │  │  │  │  ├─ ssl_.py
   │  │     │  │  │  │  ├─ ssl_match_hostname.py
   │  │     │  │  │  │  ├─ timeout.py
   │  │     │  │  │  │  ├─ url.py
   │  │     │  │  │  │  ├─ wait.py
   │  │     │  │  │  │  ├─ __init__.py
   │  │     │  │  │  │  └─ __pycache__
   │  │     │  │  │  │     ├─ connection.cpython-313.pyc
   │  │     │  │  │  │     ├─ proxy.cpython-313.pyc
   │  │     │  │  │  │     ├─ queue.cpython-313.pyc
   │  │     │  │  │  │     ├─ request.cpython-313.pyc
   │  │     │  │  │  │     ├─ response.cpython-313.pyc
   │  │     │  │  │  │     ├─ retry.cpython-313.pyc
   │  │     │  │  │  │     ├─ ssltransport.cpython-313.pyc
   │  │     │  │  │  │     ├─ ssl_.cpython-313.pyc
   │  │     │  │  │  │     ├─ ssl_match_hostname.cpython-313.pyc
   │  │     │  │  │  │     ├─ timeout.cpython-313.pyc
   │  │     │  │  │  │     ├─ url.cpython-313.pyc
   │  │     │  │  │  │     ├─ wait.cpython-313.pyc
   │  │     │  │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  │  ├─ _collections.py
   │  │     │  │  │  ├─ _version.py
   │  │     │  │  │  ├─ __init__.py
   │  │     │  │  │  └─ __pycache__
   │  │     │  │  │     ├─ connection.cpython-313.pyc
   │  │     │  │  │     ├─ connectionpool.cpython-313.pyc
   │  │     │  │  │     ├─ exceptions.cpython-313.pyc
   │  │     │  │  │     ├─ fields.cpython-313.pyc
   │  │     │  │  │     ├─ filepost.cpython-313.pyc
   │  │     │  │  │     ├─ poolmanager.cpython-313.pyc
   │  │     │  │  │     ├─ request.cpython-313.pyc
   │  │     │  │  │     ├─ response.cpython-313.pyc
   │  │     │  │  │     ├─ _collections.cpython-313.pyc
   │  │     │  │  │     ├─ _version.cpython-313.pyc
   │  │     │  │  │     └─ __init__.cpython-313.pyc
   │  │     │  │  ├─ vendor.txt
   │  │     │  │  ├─ __init__.py
   │  │     │  │  └─ __pycache__
   │  │     │  │     ├─ typing_extensions.cpython-313.pyc
   │  │     │  │     └─ __init__.cpython-313.pyc
   │  │     │  ├─ __init__.py
   │  │     │  ├─ __main__.py
   │  │     │  ├─ __pip-runner__.py
   │  │     │  └─ __pycache__
   │  │     │     ├─ __init__.cpython-313.pyc
   │  │     │     ├─ __main__.cpython-313.pyc
   │  │     │     └─ __pip-runner__.cpython-313.pyc
   │  │     └─ pip-25.1.1.dist-info
   │  │        ├─ entry_points.txt
   │  │        ├─ INSTALLER
   │  │        ├─ licenses
   │  │        │  ├─ AUTHORS.txt
   │  │        │  └─ LICENSE.txt
   │  │        ├─ METADATA
   │  │        ├─ RECORD
   │  │        ├─ REQUESTED
   │  │        ├─ top_level.txt
   │  │        └─ WHEEL
   │  ├─ pyvenv.cfg
   │  └─ Scripts
   │     ├─ activate
   │     ├─ activate.bat
   │     ├─ activate.fish
   │     ├─ Activate.ps1
   │     ├─ deactivate.bat
   │     ├─ pip.exe
   │     ├─ pip3.13.exe
   │     ├─ pip3.exe
   │     ├─ python.exe
   │     └─ pythonw.exe
   ├─ dashboard_layout.py
   ├─ main.py
   ├─ resources
   │  ├─ app_icon.png
   │  └─ style.qss
   ├─ screens
   │  ├─ create_user_screen.py
   │  ├─ home_screen.py
   │  ├─ login_screen.py
   │  ├─ users_screen.py
   │  └─ __pycache__
   │     ├─ create_user_screen.cpython-312.pyc
   │     ├─ home_screen.cpython-312.pyc
   │     ├─ login_screen.cpython-312.pyc
   │     └─ users_screen.cpython-312.pyc
   ├─ services
   │  ├─ api_service.py
   │  ├─ auth_service.py
   │  ├─ user_services.py
   │  └─ __pycache__
   │     ├─ api_service.cpython-312.pyc
   │     ├─ auth_service.cpython-311.pyc
   │     ├─ auth_service.cpython-312.pyc
   │     └─ user_services.cpython-312.pyc
   └─ __pycache__
      └─ dashboard_layout.cpython-312.pyc

```