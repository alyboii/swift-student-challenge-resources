# UIKit Resources (03)

Most SSC submissions use SwiftUI, but UIKit is still relevant for certain interactions, integrating third-party libraries, or hybrid approaches.

---

## When to use UIKit in an SSC project

- You need a custom gesture recognizer that SwiftUI doesn't expose cleanly
- You're wrapping a UIKit-based library with `UIViewRepresentable`
- You're building a complex collection view layout
- You prefer UIKit from prior experience and have limited time to switch

---

## Official

- **[UIKit documentation (Apple)](https://developer.apple.com/documentation/uikit)** — Type: `Doc` | Level: `I`
  - Complete UIKit API reference
- **[UIViewRepresentable (Apple)](https://developer.apple.com/documentation/swiftui/uiviewrepresentable)** — Type: `Doc` | Level: `I`
  - How to wrap a UIKit view for use in SwiftUI — key for hybrid apps

---

## Courses & Videos

- **[100 Days of Swift (Hacking with Swift)](https://www.hackingwithswift.com/100/swift)** — Type: `Video` | Level: `B/I`
  - UIKit-focused counterpart to 100 Days of SwiftUI
- **[HackingWithSwift source code repo](https://github.com/twostraws/HackingWithSwift)** — Type: `Repo` | Level: `B/I`
  - Contains both UIKit and SwiftUI example projects

---

## Bridging UIKit and SwiftUI

- **[Interfacing with UIKit (Apple tutorial)](https://developer.apple.com/tutorials/swiftui/interfacing-with-uikit)** — Type: `Doc` | Level: `I`
  - Official guide for integrating UIKit views and view controllers into SwiftUI
- **[UIHostingController (Apple)](https://developer.apple.com/documentation/swiftui/uihostingcontroller)** — Type: `Doc` | Level: `I`
  - Embed SwiftUI views inside a UIKit app

---

## Recommendation for SSC

Use SwiftUI as your primary framework. Drop into UIKit only when you hit a specific limitation. Judges are familiar with both — what matters is that the result feels polished and intentional.
