# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 4.0.0 (2025-01-10)


### ⚠ BREAKING CHANGES

* rotate x and y unit measurement
* add style property to ResumableZoom
* add gesture tests and rename component tests to validation
* modify pinch implementation
* **CropZoom:** made many changes to CropZoom
* **Gallery:** fix incorret tap on edge detection
* **Resumable:** onHorizontalBoundsExceeded has been replaced by this
property
* **Resuamble:** this commit will require a major version bump
* **Resumable:** onSwipeRight and onSwipeLeft have been removed
in favor of this new property.
* This commit will require a major version bump
* modifies internal code structure for gallery
* add extendGestures property to ResumableZoom
* **ResumableZoom:** modify condition to trigger swipe gestures
* **bug:** fix jumps issue at the end of pan gesture
* **panWithPinch:** makes panWithPinch opt in for ios users
* **bug:** fix jump at the end of pinch gesture
* renames the package from react-native-zoomable to react-native-zoom-toolkit
* update docs and README.md
* add some small fixes
* create a stand alone resumable component
* **friction:** fix a bug in which friction is always active when panMode is set to friction
* **resumable:** fix pinch gesture with decay animation and friction
* changes the folder structure
* update crop zoom expo guide and fix typos
* add crop zoom docs and its respective guide
* useImageResolution can now fetch bundle image resolution
* add validation scale validations for resumable components
* renames several things
* adds skia example to crop zoom
* modifies folder structure for common gestures
* delete clamp function in favor of Reaniamted's clamp utility
* update crop zoom and snapback documentation
* set up docs project as a workflow
* create a barebone for crop zoom
* **structure:** moves common stuff to the API into a commons folder
* **fix:** add checkout step
* set up a documentation workflow
* updates README.md to latest changes
* setup documentation project
* add additional context to bug-report
* configures template chooser for issues
* resolves inconsistent measuring for images
* removes zIndex property
* removes gesturesEnabled property

### Features

* add  for choosing rotation direction ([54da10d](https://github.com/Glazzes/react-native-zoom-toolkit/commit/54da10d80e21d167d4473ca01c44c4976caf7b35))
* add displaying video prop to gallery component ([d0712a8](https://github.com/Glazzes/react-native-zoom-toolkit/commit/d0712a882a420d0a2427d6708763e6880e86b2b5))
* add extendGestures property to ResumableZoom ([ba8e452](https://github.com/Glazzes/react-native-zoom-toolkit/commit/ba8e452a3afca27aec15b5103e71e67e06105d9b))
* add gesturesEnabled property to ResetableZoom ([588b3bf](https://github.com/Glazzes/react-native-zoom-toolkit/commit/588b3bf99b2ee65510e30923e5c3f4d768299a40))
* add maxScale property to Gallery component ([7f5324c](https://github.com/Glazzes/react-native-zoom-toolkit/commit/7f5324c05c08f62df137aa9ecf9e626b0676b4cc))
* add methods to Gallery ([98bc877](https://github.com/Glazzes/react-native-zoom-toolkit/commit/98bc87773eb582e17ce7e3e5b2087291a0621b75))
* add mode and OverlayComponent property ([2aa8d17](https://github.com/Glazzes/react-native-zoom-toolkit/commit/2aa8d17f43229f587843a09f6dd062d86e2f905c))
* add nested touch event support for SnapbackZoom ([742a6a8](https://github.com/Glazzes/react-native-zoom-toolkit/commit/742a6a8947178193897d06a1bc143613c1224348))
* add onGestureActive to ResetableZoom ([8a8d009](https://github.com/Glazzes/react-native-zoom-toolkit/commit/8a8d009f0c43007d569d2e3633eb673be14f8585))
* add onGestureEnd callback ([cbb61b6](https://github.com/Glazzes/react-native-zoom-toolkit/commit/cbb61b6732c2eaa7bb8c5691df72335eb3a60a2e))
* add programatic zoom method to ResumableZoom ([383eb91](https://github.com/Glazzes/react-native-zoom-toolkit/commit/383eb91d6f4b098e740ea0681f5891cd5136a083))
* add resized children size to onGestureActive ([c86dc20](https://github.com/Glazzes/react-native-zoom-toolkit/commit/c86dc209c83a8eeeb9f1eef593c3057a3ccdce6f))
* add style property to ResumableZoom ([f1cd33b](https://github.com/Glazzes/react-native-zoom-toolkit/commit/f1cd33be7ffeac1da9db1ff1cf2f6a3039bfcc38))
* add tapOnEdgeToItem to Gallery component ([02b5dfe](https://github.com/Glazzes/react-native-zoom-toolkit/commit/02b5dfe8ede34dbd222c9b6a3d273ee2a73a01c3))
* add useTransformationState hook ([4192d4d](https://github.com/Glazzes/react-native-zoom-toolkit/commit/4192d4db312ddb40b60db637adf9e41aefc55220))
* added support for onZoomBegin and onZoomEnd callback ([bf6b453](https://github.com/Glazzes/react-native-zoom-toolkit/commit/bf6b4538b80a6415b1cc250103e8000a46bbf4a6))
* adds skia example to crop zoom ([3a4f3df](https://github.com/Glazzes/react-native-zoom-toolkit/commit/3a4f3df5e200500e0785721601554c4f7bb4c2ae))
* block all gestures when a snapback animation is triggered ([ab6335d](https://github.com/Glazzes/react-native-zoom-toolkit/commit/ab6335db12bbc155270a976302d874e0af626437))
* change workflows ([9043b8e](https://github.com/Glazzes/react-native-zoom-toolkit/commit/9043b8e25962e57981912712fbde2dd3bb84131b))
* create a barebone for crop zoom ([9fd0e98](https://github.com/Glazzes/react-native-zoom-toolkit/commit/9fd0e9879f391fb3454d2ba34ad2924927e4352b))
* create a stand alone resumable component ([42b3090](https://github.com/Glazzes/react-native-zoom-toolkit/commit/42b309096c6684678a120319c5354a4321b68834))
* create resetable zoom component and everything neccesary for it to work ([f061606](https://github.com/Glazzes/react-native-zoom-toolkit/commit/f0616061110d7da3b23f30925034d39aa105634a))
* **cropzoom:** add a couple of features to cropzoom ([3aa919e](https://github.com/Glazzes/react-native-zoom-toolkit/commit/3aa919ec6d3db066fedebef73eafaf7592868b2e))
* **CropZoom:** add onGetureEnd feature to CropZoom ([e0052af](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e0052af07872888b424e548016293ff5dff55783))
* **CropZoom:** add requestState and assignState methods ([d4fcf7b](https://github.com/Glazzes/react-native-zoom-toolkit/commit/d4fcf7bc62f2188eab899312dce16f58abbd3cdc))
* **CropZoom:** improve the rendering calculation of crop zoom inner components ([9050cc2](https://github.com/Glazzes/react-native-zoom-toolkit/commit/9050cc2fd9e37a85ed1ae76200aae2af8d1470de))
* **CropZoom:** improve the rendering calculation of crop zoom inner components ([e2d216c](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e2d216c950a727ee495699d59574b701a23d3740))
* **Gallery:** add allowOverflow property ([fa480be](https://github.com/Glazzes/react-native-zoom-toolkit/commit/fa480be0ecdb2d0aa40754c036697ba69532fd6f))
* **Gallery:** add interactive callbacks ([b40df0e](https://github.com/Glazzes/react-native-zoom-toolkit/commit/b40df0e1b4870541c728063dfa3d9e86a5d36812))
* **Gallery:** add onUpdate callback property ([a7b1003](https://github.com/Glazzes/react-native-zoom-toolkit/commit/a7b1003fe0ac0c63b98b35a7a2736791a41f121b))
* **Gallery:** add onVerticalPull feature ([e27d829](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e27d8297a378025104aa19e53bfe983858706db6))
* **Gallery:** add pinchCenteringMode property ([bab2b10](https://github.com/Glazzes/react-native-zoom-toolkit/commit/bab2b1073a43308c247c671af52ab12158e62d1c))
* **Gallery:** add vertical support ([87f3170](https://github.com/Glazzes/react-native-zoom-toolkit/commit/87f3170315541ca4992aba033b8ad7c1c5e340c2))
* make pinch gesture follow the rules of panMode for clamp mode ([843cba5](https://github.com/Glazzes/react-native-zoom-toolkit/commit/843cba500a8d9cbf03c3558d8e6c41ac96c3f954))
* refactor Gallery and other goodies ([a1f8758](https://github.com/Glazzes/react-native-zoom-toolkit/commit/a1f8758848a2a4e373d0cec23d0cd2b6bd48006e))
* resolves inconsistent measuring for images ([7d62743](https://github.com/Glazzes/react-native-zoom-toolkit/commit/7d627437066923384830800daff40b3de56cbe93))
* **ResuambleZoom:** add assignState method ([5002c30](https://github.com/Glazzes/react-native-zoom-toolkit/commit/5002c303c8b4443f78195d6403b2f62d593b8980))
* **ResuambleZoom:** add onGestureEnd callback ([ac79d94](https://github.com/Glazzes/react-native-zoom-toolkit/commit/ac79d94753994ff78778f8552439ececb5af22d6))
* **resumable!:** adds support for swipe gestures ([2ba60dc](https://github.com/Glazzes/react-native-zoom-toolkit/commit/2ba60dcae09eb5aa5158eefe91c9e79b9902f0a9))
* **Resumable:** add onOverPanning callback property ([1b334ca](https://github.com/Glazzes/react-native-zoom-toolkit/commit/1b334ca9309a5241e8ff305c1d21b8159761d5bf))
* **Resumable:** add onSwipe property to ResumableZoom ([e493584](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e4935847dcafe8d538b29451be839550fdd749ae))
* **ResumableZoom:** add double tap detection support for onGestureEnd ([6e8d088](https://github.com/Glazzes/react-native-zoom-toolkit/commit/6e8d088e4c0b6ad3e301b07bce75419deb35370d))
* **ResumableZoom:** modify condition to trigger swipe gestures ([71dec23](https://github.com/Glazzes/react-native-zoom-toolkit/commit/71dec2321e75a91522fd9d3d24bec61ea7a55489))
* useImageResolution can now fetch bundle image resolution ([cd81692](https://github.com/Glazzes/react-native-zoom-toolkit/commit/cd8169262f4d9ee7d2d74833e2ce9c4872fed5c5))


### Bug Fixes

* add some small fixes ([85d666f](https://github.com/Glazzes/react-native-zoom-toolkit/commit/85d666f9b6a6816f7cc8cccd2e999e629d457a19))
* **bug:** fix jump at the end of pinch gesture ([948783f](https://github.com/Glazzes/react-native-zoom-toolkit/commit/948783f19a6073ac0d09889bd8e3b8e68635c7ef)), closes [#10](https://github.com/Glazzes/react-native-zoom-toolkit/issues/10)
* **bug:** fix jumps issue at the end of pan gesture ([0793748](https://github.com/Glazzes/react-native-zoom-toolkit/commit/0793748d04c579d80586deb9fafc13b34f1a5542)), closes [#10](https://github.com/Glazzes/react-native-zoom-toolkit/issues/10)
* **bug:** fix pinch and pan gesture overlap for good this time ([b46bf1f](https://github.com/Glazzes/react-native-zoom-toolkit/commit/b46bf1f50e3fd2fc65b28f1ce1e0780381613205))
* change crop area's color from yellow to red ([e3962dd](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e3962ddd1380ca8f5718c5b7aa905b3d2d0bd213))
* correct maxScale calculation to be based on the aspect ratio ([ac44cbe](https://github.com/Glazzes/react-native-zoom-toolkit/commit/ac44cbe8b5756a6315e14aa8a872c485c2914d6a))
* **Crop:** add missing scale animation on reset ([599003c](https://github.com/Glazzes/react-native-zoom-toolkit/commit/599003c313ad76e0281429e72adee5ba8ae9da19))
* **CropZoom:** fixes 'crash' when cropping an element with an aspect ratio of one ([ab9f510](https://github.com/Glazzes/react-native-zoom-toolkit/commit/ab9f5102391b1bdf3745e0c1a98a13e1f5d72bdd))
* **CropZoom:** improve pinch gesture calculation while rotated ([27005af](https://github.com/Glazzes/react-native-zoom-toolkit/commit/27005af89cd69f4a58a48a35560fda990b050fe1))
* **docs:** renames zoom2.mp4 back to resumablezoom.mp4 ([1c75397](https://github.com/Glazzes/react-native-zoom-toolkit/commit/1c75397d2676732819410ef5a56e890107087cf4))
* **docs:** you can not rename videos using Github, adds the file manually ([67dd754](https://github.com/Glazzes/react-native-zoom-toolkit/commit/67dd7545e17a6d3f4620a9d524f00fcc9a38e9db))
* **Example:** fix image gallery components not returning to base state when swiping ([62c653c](https://github.com/Glazzes/react-native-zoom-toolkit/commit/62c653cc23e9598c32b259d866415eb54f5f3484))
* **friction:** fix a bug in which friction is always active when panMode is set to friction ([d010379](https://github.com/Glazzes/react-native-zoom-toolkit/commit/d010379a9a4c08f59cf77a9e114dafcd7c811b2a))
* **Gallery:** add boolean flag to rest method ([6776221](https://github.com/Glazzes/react-native-zoom-toolkit/commit/67762212a77feeffb69e99987bc09ab62c34c55b))
* **Gallery:** fix [#44](https://github.com/Glazzes/react-native-zoom-toolkit/issues/44) and flickering on low android devices ([cf11e2f](https://github.com/Glazzes/react-native-zoom-toolkit/commit/cf11e2f8268dbbbb721d2d23ca487f37fe27b3f0))
* **Gallery:** fix a bug where setIndex method would not load previous or next data ([b892a99](https://github.com/Glazzes/react-native-zoom-toolkit/commit/b892a993470bc15a6f31b867b98121d8547f19c7))
* **Gallery:** fix incorret tap on edge detection ([25c21e2](https://github.com/Glazzes/react-native-zoom-toolkit/commit/25c21e2a9e3dc18941b548d48c366a2a1577e7aa))
* **Gallery:** fix memoization of GalleryItem and Reflection ([2c5eae7](https://github.com/Glazzes/react-native-zoom-toolkit/commit/2c5eae72217f8552ff663e34d445b7e1d3d79a84))
* **Gallery:** fix onVerticalPull and onSwipe overlap ([e5a358d](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e5a358da7020231167bcd4e68a0f58ca1823b4aa))
* invalid initial xy position and rotate xy transformation ([a85e0c3](https://github.com/Glazzes/react-native-zoom-toolkit/commit/a85e0c3d8e4c5ea6304a14f417c4d8ef35d10e53))
* **lint:** fix incorrent transforms type in Skia crop zoom example ([53d3e95](https://github.com/Glazzes/react-native-zoom-toolkit/commit/53d3e955d9796aee85135162de81c0125ce19409))
* resolve merge conflicts ([28e520b](https://github.com/Glazzes/react-native-zoom-toolkit/commit/28e520bc5e387d36d69d219cd85f00ebc159611f))
* **ResuambleZoom:** assign minScale to the inital value of scale shared value ([8b4cc70](https://github.com/Glazzes/react-native-zoom-toolkit/commit/8b4cc70c93fb8eef295460c5959e470cacbce40b))
* **Resumable:** allow ResumableZoom's extendGestures to handle big items ([8735f37](https://github.com/Glazzes/react-native-zoom-toolkit/commit/8735f379bf4b7b2885a61729d00f4929c97fb6bb))
* **resumable:** fix pinch gesture with decay animation and friction ([2910360](https://github.com/Glazzes/react-native-zoom-toolkit/commit/29103605c07f7b88839c5b34cbdc9281724ff33a))
* rework ResetableComponent to align with resizeConfig ([e260106](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e2601065a2b5ac70fb028b939e86b8aca444ab2d))
* rotate x and y unit measurement ([baeb5b7](https://github.com/Glazzes/react-native-zoom-toolkit/commit/baeb5b7fd80d0b0acbbea9830d76d04ac19dbcb2))
* set shared values properly in pan commons hook ([8b5ce41](https://github.com/Glazzes/react-native-zoom-toolkit/commit/8b5ce4161491a48456fd201a424366a724afcd00))
* **snapback:** removes unintended onPanStart and onPanEnd properties ([46d2884](https://github.com/Glazzes/react-native-zoom-toolkit/commit/46d288488436cd58e7891aae1787f5bc9dbff4b4))
* **types:** create a TimingConfig type in favor of WithTimingConfig ([c051464](https://github.com/Glazzes/react-native-zoom-toolkit/commit/c0514647c6211a5014675edad02eb31ba576e847))
* update image and video message in example app ([ca42928](https://github.com/Glazzes/react-native-zoom-toolkit/commit/ca42928e4363542fe9c20d400eab472916195646))
* when pulling vertical it will no longer block swipes ([b131625](https://github.com/Glazzes/react-native-zoom-toolkit/commit/b131625a92e025b5bcbc282c8cc102b08dcdf684))
* **zoom:** block all gestures when a snapback occurs ([b378e91](https://github.com/Glazzes/react-native-zoom-toolkit/commit/b378e91a7a09dd488f7cd979144545940d79b9d0))


### ci

* **fix:** add checkout step ([213d156](https://github.com/Glazzes/react-native-zoom-toolkit/commit/213d15618d0c4f8138fe989c3e53775bf71d3a0f))
* set up a documentation workflow ([9fd85aa](https://github.com/Glazzes/react-native-zoom-toolkit/commit/9fd85aa3790c0fb22a5cc60434627fb502a69d87))


* add additional context to bug-report ([f267184](https://github.com/Glazzes/react-native-zoom-toolkit/commit/f267184cea7791ba62f7c3d557fa82aa4e32c72a))
* add crop zoom docs and its respective guide ([db5aae6](https://github.com/Glazzes/react-native-zoom-toolkit/commit/db5aae6912b6bd07d4b35709c5c3cf9b4855b19c))
* add gesture tests and rename component tests to validation ([df7b6ac](https://github.com/Glazzes/react-native-zoom-toolkit/commit/df7b6acd3a3b92ce459498b29d19e6910896276d))
* add validation scale validations for resumable components ([4e9c99a](https://github.com/Glazzes/react-native-zoom-toolkit/commit/4e9c99a582f77cb62c9597193c937759689b9c33))
* changes the folder structure ([0cd4871](https://github.com/Glazzes/react-native-zoom-toolkit/commit/0cd4871d711ebe9e49a72f9d1fcb58f62480d357))
* configures template chooser for issues ([734cd8b](https://github.com/Glazzes/react-native-zoom-toolkit/commit/734cd8b1009a1439e279c2e2f742736ee32bd8b0))
* **CropZoom:** made many changes to CropZoom ([b4861f8](https://github.com/Glazzes/react-native-zoom-toolkit/commit/b4861f8721b02555a7bd5f4ecd0f87e6437e3e57))
* delete clamp function in favor of Reaniamted's clamp utility ([5d54c8a](https://github.com/Glazzes/react-native-zoom-toolkit/commit/5d54c8a26aaf0f9b8a17817f50c2be55f51732fc))
* modifies folder structure for common gestures ([7b0acfa](https://github.com/Glazzes/react-native-zoom-toolkit/commit/7b0acfa71410e5c352e3791b44d393b7b51a1eda))
* modifies internal code structure for gallery ([423049e](https://github.com/Glazzes/react-native-zoom-toolkit/commit/423049eaed73284c52dd0cb807cc953001ad0686))
* modify pinch implementation ([3a5c906](https://github.com/Glazzes/react-native-zoom-toolkit/commit/3a5c906772802ea5589d6e8a3ff7372992b75650))
* **panWithPinch:** makes panWithPinch opt in for ios users ([8422651](https://github.com/Glazzes/react-native-zoom-toolkit/commit/8422651d0818c6b7422907d5a2f375f3c92d4109)), closes [#10](https://github.com/Glazzes/react-native-zoom-toolkit/issues/10)
* rename all instance of panWithPinch property to allowPinchPanning ([4cf796e](https://github.com/Glazzes/react-native-zoom-toolkit/commit/4cf796e1c4690b2e03849c208ef3ad2d982c73c9))
* renames several things ([e5242a5](https://github.com/Glazzes/react-native-zoom-toolkit/commit/e5242a59938871b9106d90e24250da63aa92d961))
* renames the package from react-native-zoomable to react-native-zoom-toolkit ([833975a](https://github.com/Glazzes/react-native-zoom-toolkit/commit/833975a06f5c532279942ac6aeb01f7f17ded683))
* **Resuamble:** remove hitslop property ([596d18c](https://github.com/Glazzes/react-native-zoom-toolkit/commit/596d18cc740796421ed12aa9322442d432fa40ec))
* set up docs project as a workflow ([8614507](https://github.com/Glazzes/react-native-zoom-toolkit/commit/86145076565d592bffa56a4753c735da88aecd3b))
* setup documentation project ([66272ba](https://github.com/Glazzes/react-native-zoom-toolkit/commit/66272baaae570dd5076b4d62b1e212c12e0d4afd))
* **structure:** moves common stuff to the API into a commons folder ([39bd9b0](https://github.com/Glazzes/react-native-zoom-toolkit/commit/39bd9b0fb5c55a51a8e2f29d8e20c0887d90154c))
* update crop zoom and snapback documentation ([39ccd92](https://github.com/Glazzes/react-native-zoom-toolkit/commit/39ccd927653f526b81946e485df13c10da0681c3))
* update crop zoom expo guide and fix typos ([3c3dedd](https://github.com/Glazzes/react-native-zoom-toolkit/commit/3c3deddb86f5cd2388ade3c09a32b0f4c002c8ac))
* update docs and README.md ([04d7561](https://github.com/Glazzes/react-native-zoom-toolkit/commit/04d7561291d49b7ddd0695f3a390bbca1efb95ec))
* updates README.md to latest changes ([d3777ea](https://github.com/Glazzes/react-native-zoom-toolkit/commit/d3777ea498bf264d83b3b035271e63d7a5cae8cb))
