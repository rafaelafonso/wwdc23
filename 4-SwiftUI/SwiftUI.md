# 4. SwiftUI

### 4.1. What’s new in SwiftUI (34m)
- Spatial computing brings SwiftUI into a bold new future with all new 3D capabilities like volumes, rich experiences with immersive spaces, new 3D gestures, effects and layout. And deep integration with RealityKit.
- New `@Observable` macro. Observable models let you use familiar SwiftUI patterns for data flow, while also making your code more concise and performant. 
- Unlike ObservableObject, there’s no need to mark properties as Published. Observable models easily integrate into the existing SwiftUI mechanisms for data flow.
- SwiftUI includes several tools for defining your state and its relationship to your views (@State, @StateObject, @ObservedObject, @Environment, @EnvironmentObject). When using Observable, this becomes even simpler since it’s designed to work directly with the State and Environment dynamic properties.
- In addition to modelling read-only values, Observables are also a natural fit to represent mutable state.
- Lastly, Observable types integrate seamlessly into the environment.
- **SwiftData** is an all-new framework for data modelling and management. It’s fast and scalable and works great with SwiftUI. SwiftData models are represented entirely by their code, making them a natural fit for any SwiftUI app.
- SwiftData models are represented entirely by their code, making them a natural fit for any SwiftUI app. Using @Model macro instead of @Observable would be the only change needed
- In addition to the persistence provided by SwiftData, models also receive all the benefits of using Observable.
- **Inspector** is a new modifier for displaying details about the current selection or context. It’s presented as a distinct section in your interface.
- Animations.

#wwdc23 #swiftui
