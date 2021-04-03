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
    * Local
        * SharedPreferences/NSUserDefaults
        * Local device database
        * On-device file storage
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