### Overview of Essential iOS Concepts
This page includes brief overviews of common concepts in iOS development that are foundationally essential. Each section is not intended to be an elaborate explanation into the concept, but for a deeper understanding, read the documentation attached.

#### Automatic Reference Counting (ARC)
Understanding Automatic Reference Counting is critical to handling memory leaks. Before ARC was implemented, developers would handle proper memory allocation using the ```init```/```alloc``` and ```deinit```/```dealloc``` methods.

In ARC, the reference count of an object is increased by one every time there is a reference to it. However, we can use different modifiers to specify what behavior that object will take on.

**Types of Modifiers**:
|```strong``` (default)|Increases the reference count for every reference|
|```weak```|Does not increase the reference count|
|```unowned```|Does not increase the reference count|

In a ```weak``` reference, the object is optional and must be unwrapped before using. Using ```unowned``` is equivalent to force-unwrapping.

#### Callback Patterns
##### Closures
In functional languages like Swift, it is common to pass functions around as arguments or return types. Specifically for Swift, we call these closures.

To read more about closures, the Swift documentation has a [detailed guide](https://docs.swift.org/swift-book/LanguageGuide/Closures.html).

##### Delegation
The delegate pattern is a cornerstone in iOS development. It employs separation of concerns

Delegation typically involves three primary components:
* The protocol that lists the delegate's expected properties and methods
* The class that implements the delegate
* The class that depends on the delegate

**Common examples of delegation in Apple's native libraries:**
* [UIApplicationDelegate](https://developer.apple.com/documentation/uikit/uiapplicationdelegate)
* [UISceneDelegate](https://developer.apple.com/documentation/uikit/uiscenedelegate)
* [UITextFieldDelegate](https://developer.apple.com/documentation/uikit/uitextfielddelegate)
* [UITableViewDelegate](https://developer.apple.com/documentation/uikit/uitableviewdelegate)

##### Key-Value Observing (KVO)

##### NotificationCenter/NSNotificationCenter

### Grand Central Dispatch