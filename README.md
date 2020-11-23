# jetpackpractice

This is a jetpack practice app.

[Jetpack](https://developer.android.com/jetpack) is a suite of libraries developed by Google, that can help developers write less code that works consistently across Android versions and devices.

Jetpack has a lot of libraries, by the time of creating this project, it has 85 libraries. A huge number.

This project will show examples of how to use these libraries.

Examples will be in alphabetic order with is listed below. Each example will be a submodule and is in a separate branch in git.

All the libraries ar listed here: (names with a * means it's a popular and often-used library)

| Library                                                      | Description                                                  |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [activity *](https://developer.android.com/jetpack/androidx/releases/activity) | Access composable APIs built on top of Activity.             |
| [ads](https://developer.android.com/jetpack/androidx/releases/ads) | Get an advertising ID with or without Play Services.         |
| [annotation](https://developer.android.com/jetpack/androidx/releases/annotation) | Expose metadata that helps tools and other developers understand your app's code. |
| [appcompat *](https://developer.android.com/jetpack/androidx/releases/appcompat) | Allows access to new APIs on older API versions of the platform (many using Material Design). |
| [arch.core](https://developer.android.com/jetpack/androidx/releases/arch-core) | Helper for other arch dependencies, including JUnit test rules that can be used with LiveData. |
| [asynclayoutinflater](https://developer.android.com/jetpack/androidx/releases/asynclayoutinflater) | Inflate layouts asynchronously to avoid jank in the UI.      |
| [autofill](https://developer.android.com/jetpack/androidx/releases/autofill) | Improve autofill accuracy via extending hints.               |
| [benchmark](https://developer.android.com/jetpack/androidx/releases/benchmark) | Accurately measure your code's performance within Android Studio. |
| [biometric](https://developer.android.com/jetpack/androidx/releases/biometric) | Authenticate with biometrics or device credentials, and perform cryptographic operations. |
| [browser](https://developer.android.com/jetpack/androidx/releases/browser) | Display webpages in the user's default browser.              |
| [camera *](https://developer.android.com/jetpack/androidx/releases/camera) | Build mobile camera apps.                                    |
| [car](https://developer.android.com/jetpack/androidx/releases/car) | Develop driving-friendly applications for an Android-powered car. |
| [cardview](https://developer.android.com/jetpack/androidx/releases/cardview) | Implement the Material Design card pattern with round corners and drop shadows. |
| [collection](https://developer.android.com/jetpack/androidx/releases/collection) | Reduce the memory impact of existing and new collections that are small. |
| [compose *](https://developer.android.com/jetpack/androidx/releases/compose) | Define your UI programmatically with composable functions that describe its shape and data dependencies. |
| [compose.animation](https://developer.android.com/jetpack/androidx/releases/compose-animation) | Build animations in their Jetpack Compose applications to enrich the user experience. |
| [compose.compiler](https://developer.android.com/jetpack/androidx/releases/compose-compiler) | Transform @Composable functions and enable optimizations with a Kotlin compiler plugin. |
| [compose.foundation](https://developer.android.com/jetpack/androidx/releases/compose-foundation) | Write Jetpack Compose applications with ready to use building blocks and extend foundation to build your own design system pieces. |
| [compose.material](https://developer.android.com/jetpack/androidx/releases/compose-material) | Build Jetpack Compose UIs with ready to use Material Design Components. This is the higher level entry point of Compose, designed to provide components that match those described at www.material.io. |
| [compose.runtime](https://developer.android.com/jetpack/androidx/releases/compose-runtime) | Fundamental building blocks of Compose's programming model and state management, and core runtime for the Compose Compiler Plugin to target. |
| [compose.ui](https://developer.android.com/jetpack/androidx/releases/compose-ui) | Fundamental components of compose UI needed to interact with the device, including layout, drawing, and input. |
| [concurrent](https://developer.android.com/jetpack/androidx/releases/concurrent) | Move tasks off the main thread with coroutines and take advantage of ListenableFuture. |
| [constraintlayout](https://developer.android.com/jetpack/androidx/releases/constraintlayout) | Position and size widgets in a flexible way with relative positioning. |
| [contentpager](https://developer.android.com/jetpack/androidx/releases/contentpager) | Load and page across ContentProvider data in a background thread. |
| [coordinatorlayout](https://developer.android.com/jetpack/androidx/releases/coordinatorlayout) | Position top-level application widgets, such as AppBarLayout and FloatingActionButton. |
| [core](https://developer.android.com/jetpack/androidx/releases/core) | Target the latest platform features and APIs while also supporting older devices. |
| [cursoradapter](https://developer.android.com/jetpack/androidx/releases/cursoradapter) | Expose Cursor data to a ListView widget.                     |
| [customview](https://developer.android.com/jetpack/androidx/releases/customview) | Implement custom views.                                      |
| [databinding *](https://developer.android.com/jetpack/androidx/releases/databinding) | Bind UI components in your layouts to data sources in your app using a declarative format. |
| [datastore](https://developer.android.com/jetpack/androidx/releases/datastore) | Store data asynchronously, consistently, and transactionally, overcoming some of the drawbacks of SharedPreferences |
| [documentfile](https://developer.android.com/jetpack/androidx/releases/documentfile) | View a file document.                                        |
| [drawerlayout](https://developer.android.com/jetpack/androidx/releases/drawerlayout) | Implement a Material Design drawer widget.                   |
| [dynamicanimation](https://developer.android.com/jetpack/androidx/releases/dynamicanimation) | Create smooth animations with a physics-based animation API. |
| [emoji](https://developer.android.com/jetpack/androidx/releases/emoji) | Display emoji in current and older devices.                  |
| [enterprise](https://developer.android.com/jetpack/androidx/releases/enterprise) | Create enterprise-ready applications.                        |
| [exifinterface](https://developer.android.com/jetpack/androidx/releases/exifinterface) | Read and write image file EXIF tags.                         |
| [fragment *](https://developer.android.com/jetpack/androidx/releases/fragment) | Segment your app into multiple, independent screens that are hosted within an Activity. |
| [games](https://developer.android.com/jetpack/androidx/releases/games) | Use the Android Game SDK natively in your app to perform complex games tasks, like Frame Pacing. |
| [gridlayout](https://developer.android.com/jetpack/androidx/releases/gridlayout) | Implement a grid layout.                                     |
| [heifwriter](https://developer.android.com/jetpack/androidx/releases/heifwriter) | Encode an image or image collection in HEIF format using the available codecs on the Android device. |
| [hilt *](https://developer.android.com/jetpack/androidx/releases/hilt) | Extend the functionality of Dagger Hilt to enable dependency injection of certain classes from the androidx libraries. |
| [interpolator](https://developer.android.com/jetpack/androidx/releases/interpolator) | Use animation interpolators on older platforms.              |
| [jetifier](https://developer.android.com/jetpack/androidx/releases/jetifier) | A standalone tool that migrates a library's dependencies on the deprecated support library to equivalent AndroidX dependencies. |
| [leanback](https://developer.android.com/jetpack/androidx/releases/leanback) | Write apps for Android TV devices using dpad-friendly widgets and template fragments. |
| [legacy](https://developer.android.com/jetpack/androidx/releases/legacy) | This artifact and its classes are deprecated. Starting with Android 8, background check restrictions make this class no longer useful. |
| [lifecycle *](https://developer.android.com/jetpack/androidx/releases/lifecycle) | Build lifecycle-aware components that can adjust behavior based on the current lifecycle state of an activity or fragment. |
| [loader](https://developer.android.com/jetpack/androidx/releases/loader) | Load data for your UI that survives configuration changes.   |
| [localbroadcastmanager](https://developer.android.com/jetpack/androidx/releases/localbroadcastmanager) | This artifact and its classes are deprecated. Use LiveData or reactive streams instead. |
| [media](https://developer.android.com/jetpack/androidx/releases/media) | Share media contents and controls with other apps. Superseded by media2. |
| [media2](https://developer.android.com/jetpack/androidx/releases/media2) | Share media contents and controls with other apps.           |
| [mediarouter](https://developer.android.com/jetpack/androidx/releases/mediarouter) | Enable media display and playback on remote receiver devices using a common user interface. |
| [multidex](https://developer.android.com/jetpack/androidx/releases/multidex) | Deploy applications with multiple dex files on pre-Android 5 devices. |
| [navigation *](https://developer.android.com/jetpack/androidx/releases/navigation) | Build and structure your in-app UI, handle deep links, and navigate between screens. |
| [paging *](https://developer.android.com/jetpack/androidx/releases/paging) | Load data in pages, and present it in a RecyclerView.        |
| [palette](https://developer.android.com/jetpack/androidx/releases/palette) | Extract representative color palettes from images.           |
| [percentlayout](https://developer.android.com/jetpack/androidx/releases/percentlayout) | This artifact and its classes are deprecated. Use ConstraintLayout and associated layouts instead. |
| [preference](https://developer.android.com/jetpack/androidx/releases/preference) | Build interactive settings screens without needing to interact with device storage or manage the UI. |
| [print](https://developer.android.com/jetpack/androidx/releases/print) | Print photos, docs, and other graphics and images from your app. |
| [recommendation](https://developer.android.com/jetpack/androidx/releases/recommendation) | Promote content to the Android TV Launcher home screen.      |
| [recyclerview](https://developer.android.com/jetpack/androidx/releases/recyclerview) | Display large sets of data in your UI while minimizing memory usage. |
| [remotecallback](https://developer.android.com/jetpack/androidx/releases/remotecallback) | Create a wrapper that makes it easier for developers to provide a PendingIntent. |
| [room *](https://developer.android.com/jetpack/androidx/releases/room) | Create, store, and manage persistent data backed by a SQLite database. |
| [savedstate](https://developer.android.com/jetpack/androidx/releases/savedstate) | Write pluggable components that save the UI state when a process dies, and restore it when the process restarts. |
| [security](https://developer.android.com/jetpack/androidx/releases/security) | Safely manage keys and encrypt files and sharedpreferences.  |
| [sharetarget](https://developer.android.com/jetpack/androidx/releases/sharetarget) | Provide backwards compatibility for using shortcuts as direct share targets. |
| [slice](https://developer.android.com/jetpack/androidx/releases/slice) | Display templated UI elements outside your app.              |
| [slidingpanelayout](https://developer.android.com/jetpack/androidx/releases/slidingpanelayout) | Implement a sliding pane UI pattern.                         |
| [startup](https://developer.android.com/jetpack/androidx/releases/startup) | Implement a straightforward, performant way to initialize components at app startup. |
| [sqlite](https://developer.android.com/jetpack/androidx/releases/sqlite) | Work with local SQLite databases. If possible, use Room instead. |
| [swiperefreshlayout](https://developer.android.com/jetpack/androidx/releases/swiperefreshlayout) | Implement the swipe-to-refresh UI pattern.                   |
| [test *](https://developer.android.com/jetpack/androidx/releases/test) | Testing in Android.                                          |
| [textclassifier](https://developer.android.com/jetpack/androidx/releases/textclassifier) | Identifies conversations, links, selections, and other similar constructs in text. |
| [tracing](https://developer.android.com/jetpack/androidx/releases/tracing) | Write trace events to the system trace buffer.               |
| [transition](https://developer.android.com/jetpack/androidx/releases/transition) | Animate motion in the UI with starting and ending layouts.   |
| [tvprovider](https://developer.android.com/jetpack/androidx/releases/tvprovider) | Provide Android TV channels.                                 |
| [ui](https://developer.android.com/jetpack/androidx/releases/ui) | Works with the Jetpack Compose library.                      |
| [vectordrawable](https://developer.android.com/jetpack/androidx/releases/vectordrawable) | Render vector graphics.                                      |
| [versionedparcelable](https://developer.android.com/jetpack/androidx/releases/versionedparcelable) | Provides a stable and compact binary serialization format that can be passed across processes or persisted safely. |
| [viewpager](https://developer.android.com/jetpack/androidx/releases/viewpager) | Display Views or Fragments in a swipeable format. If possible, use viewpager2 instead. |
| [viewpager2](https://developer.android.com/jetpack/androidx/releases/viewpager2) | Display Views or Fragments in a swipeable format.            |
| [wear](https://developer.android.com/jetpack/androidx/releases/wear) | Create applications for Wear OS by Google smartwatches.      |
| [webkit](https://developer.android.com/jetpack/androidx/releases/webkit) | Work with modern WebView APIs on Android 5 and above.        |
| [window](https://developer.android.com/jetpack/androidx/releases/window) | Helps support different device form factors such as foldable devices. |
| [work *](https://developer.android.com/jetpack/androidx/releases/work) | Schedule and execute deferrable, constraint-based background tasks. |
| [Material Design Components *](https://material.io/develop/android) | Modular and customizable Material Design UI components for Android. |

