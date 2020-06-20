## Cross-Platform Mobile Guide for Native iOS & Android Developers

### Overview of Mobile Development
Think about your smartphone. It wasn't too long ago that the smartphone market was only emerging. Before, we had to hop onto a laptop or desktop just to do a quick Google search, and for some of us, this made up even a significant portion of our lifetime. Now everyone is carrying a personalized digital Swiss Army knife in their own pocket. These days, the average person no longer has need to carry around a flashlight or a camera. And the most exciting part about it all is that you, as a mobile software engineer, can develop the skillset to build the apps that go on these devices.

Mobile development is an interesting subfield of programming, as it calls on you to think about the visual design of the front-end client you are building, while bearing in mind the restrictions of the hardware you're building it for--from battery life to network connectivity.

There are many tools available for mobile developers, and the first division to consider is the distinction between native and hybrid platforms. What does this mean? Native indicates the toolsets published and maintained by Apple and Google for their respective platforms. On the flipside, we have hybrid frameworks available that allow us to develop for both Android and iOS with the same codebase. Such frameworks include [Flutter](https://flutter.dev), [React Native](https://facebook.github.io/react-native/), and [Xamarin](https://dotnet.microsoft.com/apps/xamarin), among many others.

### How to Use This Guide
Here, we will focus primarily on native mobile development tools. This is a beginner-friendly list of curated resources and tips for aspiring engineers in both iOS and Android. More advanced developers can still take advantage of this list as a way to organize a variety of the resources available (and are more than welcome to contribute).

Where other lists tend to focus primarily on one platform or the other, this guide aims to reconcile the similarities and differences between both. Native cross-platform development is a powerful alternative to hybrid development, but it can be daunting to learn the nuances of both platforms, especially for beginners. There are a lot of resources in this guide, but it is not meant to be consumed all at once. As you continue through your journey to become a better engineer, you can use this guide as a reference for resources as you encounter different problems to tackle along the way.

### Android

#### References
|Name|Description|
|:--|:--|
|[Official Developer Documentation](https://developer.android.com/docs)|
|[Material Design](https://material.io/design/introduction/#principles)|Visual design guidelines to adhere to as an Android developer|
|[Google Style Guide for Java](https://google.github.io/styleguide/javaguide.html)|
|[Official Android Style Guide for Kotlin](https://developer.android.com/kotlin/style-guide)|
|[Ray Wenderlich Style Guide for Kotlin](https://github.com/raywenderlich/kotlin-style-guide)|
|[Google Codelabs for Android](https://codelabs.developers.google.com/?cat=Android)|
|[Google Developers Community](https://developers.google.com)|
|[Android Developer Roadmap](https://github.com/mobile-roadmap/android-developer-roadmap)|
|[Overview of Dependency Injection](https://developer.android.com/training/dependency-injection/#kotlin)|
|[Must Have Libraries](https://github.com/codepath/android_guides/wiki/Must-Have-Libraries)|Detailed guide to using essential third-party Android libraries|

#### Tools
|Name|Description|
|:--|:--|
|[Dagger 2](https://dagger.dev)|Dependency injection framework for Java and Android|
|[Glide](https://github.com/bumptech/glide)|Image loading and displaying library|
|[Gson](https://github.com/google/gson)|Tool for serializing and deserializing JSON strings into objects|
|[LeakCanary](https://square.github.io/leakcanary/)|Memory leak detection and analysis for Android apps|
|[OkHttp](https://square.github.io/okhttp/)|Client for making HTTP requests in Android|
|[Parcelabler](http://www.parcelabler.com)|Web tool for generating Parcelable objects|
|[Robolectric](https://github.com/robolectric/robolectric)|Simulates instrumented environment within Android unit tests|
|[RxAndroid](https://github.com/ReactiveX/RxAndroid)|Layer built on top of RxJava for Android-specific components|
|[RxJava](https://github.com/ReactiveX/RxJava)|Asynchronous programming through observable streams for JVM|

#### Blogs
* [Android Developers Blog](https://android-developers.googleblog.com)
* [Jake Wharton's Blog](https://jakewharton.com/blog/)
* [ProAndroidDev](https://proandroiddev.com)

#### Podcasts
* [Fragmented](https://fragmentedpodcast.com/category/episodes/)
* [Now in Android](https://open.spotify.com/show/3alx5rvDZgumqA35EWZl18?si=mTGsZbaqQc6P0dMW26_3QA)
* [Talking Kotlin](https://talkingkotlin.com/posts/)

### iOS

#### References
|Name|Description|
|:--|:--|
|[Official Developer Documentation](https://developer.apple.com/documentation/)|
|[Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)|Visual design guidelines to adhere to as an iOS developer|
|[Google Style Guide for Objective-C](http://google.github.io/styleguide/objcguide.html)|
|[Google Style Guide for Swift](https://google.github.io/swift/)|
|[Ray Wenderlich Style Guide for Swift](https://github.com/raywenderlich/swift-style-guide)|
|[Xcode Shortcuts](https://github.com/roblack/xCodeShortcuts)|
|[iOS Developer Roadmap](https://github.com/BohdanOrlov/iOS-Developer-Roadmap)|
|[Apple Developer App](https://apps.apple.com/us/app/apple-developer/id640199958)|
|[Swift Evolution](https://github.com/apple/swift-evolution)|Document of history and proposals for enhancing and evolving the Swift programming language|

#### Tools
|Name|Description|
|:--|:--|
|[Alamofire](https://github.com/Alamofire/Alamofire)|Library for making HTTP network requests in iOS|
|[Build Time Analyzer for Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode)|macOS tool to analyze Xcode project build times|
|[Control Room](https://github.com/twostraws/ControlRoom)|GUI tool built on top of ```simctl``` to control Simulator|
|[RxSwift](https://github.com/ReactiveX/RxSwift)|Asynchronous programming through observable streams, see also: [Combine](https://developer.apple.com/documentation/combine)|
|[Swiftify](https://swiftify.com)|Auto-converter from Objective-C to Swift|
|[SwiftLint](https://github.com/realm/SwiftLint)|Linting tool for Swift files in Xcode|
|[Timelane](http://timelane.tools)|Xcode Instrument to visually profile tasks from Combine and RxSwift|

#### Blogs
* [Hacking with Swift](https://www.hackingwithswift.com/articles)
* [NSHipster](https://nshipster.com)
* [SwiftLee](https://www.avanderlee.com)
* [Swift by Sundell Blog](https://www.swiftbysundell.com/articles/)
* [Use Your Loaf](https://useyourloaf.com)

#### Podcasts
* [iOS Dev Discussions - Sean Allen](https://podcasts.apple.com/us/podcast/ios-dev-discussions-sean-allen/id1426167395)
* [More Than Just Code](https://mtjc.fireside.fm)
* [Swiftly Speaking](https://podcasts.apple.com/us/podcast/swiftly-speaking/id1505697997)
* [Swift by Sundell Podcast](https://www.swiftbysundell.com/podcast/)
* [Swift Unwrapped](https://spec.fm/podcasts/swift-unwrapped)
* [The iPhreaks Show](https://devchat.tv/iphreaks/)

### Considerations for Mobile Developers

#### I. Essential Foundational Concepts
* Types of Views and Layouts
    * How to implement them
    * When to use one over another
* Application Lifecycle
* Application Navigation
* Dynamic UI Management
* JSON Parsing
* Data Persistence
    * SharedPreferences/NSUserDefaults
    * Local device database
    * Cloud database
* Network Requests
* Integration of Third-Party Libraries

#### II. Common Mobile Architectures
* MVC (Model-View-Controller)
* MVP (Model-View-Presenter)
* MVVM (Model-View-ViewModel)
* VIPER (View, Interactor, Presenter, Entity, Router)
* MVI (Model-View-Intent)
* [RIBs (Router-Interactor-Builder)](https://github.com/uber/RIBs/wiki)

#### III. Questions to Think About
##### Product
* What problems does my app attempt to solve?

##### UI/UX
* How can I best maintain parity between my Android and iOS versions?
* How can I best align with the native design guidelines specific to each platform?
* How does my UI appear on different screen sizes?
* What am I doing to make my app accessible for all users?
* What methods should I use to implement my UI?
    * XML/Interface Builder
    * Programmatic
    * Declarative (Jetpack Compose/SwiftUI)

##### Technical
* What range of devices and OS versions should my app target?
* How am I ensuring that my app is the least intensive on battery life as it can be?
* How am I accounting for situations of low or no network connectivity?
* How am I accounting for user data privacy?
* What measures am I taking to prevent fatal crashes in my app?
* How should I structure my code architecture?
* Should I retrieve my app's data from local device storage or from a server?

### Miscellaneous Resources

#### Cross-Platform Resources
|Name|Description
|:--|:--|
|[Lyft Mobile Podcast](https://podcasts.apple.com/us/podcast/lyft-mobile/id1453587931)|
|[Square Developer YouTube Channel](https://www.youtube.com/squaredev)|
|[Swift is like Kotlin](http://nilhcem.com/swift-is-like-kotlin/)|Side-by-side comparison between Swift and Kotlin syntax|
|[The Polyglot Developer Podcast](https://podcasts.apple.com/us/podcast/the-polyglot-developer-podcast/id1070975158)|

#### Tools
|Name|Description|
|:--|:--|
|[fastlane](https://fastlane.tools)|Build and release automation tool for mobile apps|
|[Postman](https://www.getpostman.com)|GUI client for simulating API requests independent of code|
|[Postwoman](https://postwoman.io)|Web client that with the same functionality that Postman provides|

#### Version Control
|Name|Description|
|:--|:--|
|[GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html)|
|[Learn Git Branching](https://learngitbranching.js.org/?locale=en_US)|Helpful interactive GUI to practice Git|
|Git GUIs|[Fork](https://git-fork.com)<br>[GitKraken](https://www.gitkraken.com/git-client)<br>[Sourcetree](https://www.sourcetreeapp.com)|
