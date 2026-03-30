# Design & Accessibility (08)

An app that works well and feels right — and can be used by everyone — stands out from one that just runs.

---

## Human Interface Guidelines

- **[Human Interface Guidelines (Apple)](https://developer.apple.com/design/human-interface-guidelines)** — Type: `Doc` | Level: `B/I`
  - Apple's design principles, components, and platform conventions — read before finalizing your UI
- **[HIG – Layout](https://developer.apple.com/design/human-interface-guidelines/layout)** — Type: `Doc` | Level: `I`
  - Spacing, margins, safe areas, and adaptive layouts

---

## Accessibility — Official

- **[Apple Accessibility documentation](https://developer.apple.com/documentation/accessibility)** — Type: `Doc` | Level: `I`
  - Full reference for accessibility APIs
- **[SwiftUI Accessibility fundamentals](https://developer.apple.com/documentation/SwiftUI/Accessibility-fundamentals)** — Type: `Doc` | Level: `I`
  - SwiftUI-specific accessibility modifiers — `.accessibilityLabel`, `.accessibilityHint`, etc.
- **[Accessibility & Inclusion videos (Apple)](https://developer.apple.com/videos/accessibility-inclusion)** — Type: `Video` | Level: `I`
  - Curated WWDC sessions on accessibility and inclusive design
- **[WWDC21: The practice of inclusive design](https://developer.apple.com/videos/play/wwdc2021/10275/)** — Type: `Video` | Level: `I`
  - How to think about inclusion beyond just VoiceOver

---

## Practical Guides

- **[Hacking with Swift – Accessibility in SwiftUI](https://www.hackingwithswift.com/books/ios-swiftui/accessibility-introduction)** — Type: `Article` | Level: `I`
  - Practical introduction to adding accessibility to a SwiftUI app
- **[A11y with Swift (swiftbysundell.com)](https://www.swiftbysundell.com/tags/accessibility/)** — Type: `Article` | Level: `I`
  - Tagged accessibility articles on Swift by Sundell

---

## Swift Student Challenge accessibility checklist

Judges are explicitly told to evaluate accessibility. These take 30 minutes and make a real difference:

- [ ] **VoiceOver** — Every interactive element has `.accessibilityLabel` and `.accessibilityHint`
- [ ] **Dynamic Type** — Text scales correctly; no truncation or overflow at large sizes
- [ ] **Color contrast** — Text is readable without relying on color alone
- [ ] **Color blindness** — No information conveyed by color alone (add shape, icon, or label)
- [ ] **Tap targets** — Buttons are at least 44×44 pt
- [ ] **Reduce Motion** — Animations respect `@Environment(\.accessibilityReduceMotion)`
