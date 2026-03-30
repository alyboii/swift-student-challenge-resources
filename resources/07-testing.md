# Testing (07)

Unit tests, UI tests, and Xcode test workflow — with practical examples for SSC projects.

---

## Official (Apple)

- **[XCTest overview (Apple)](https://developer.apple.com/documentation/xctest)** — Type: `Doc` | Level: `I`
  - The standard testing framework for Swift — no additional libraries needed
- **[XCTestCase API (Apple)](https://developer.apple.com/documentation/xctest/xctestcase)** — Type: `Doc` | Level: `I`
  - Reference for writing test cases and assertions
- **[WWDC25: UI automation with XCTest](https://developer.apple.com/videos/play/wwdc2025/344/)** — Type: `Video` | Level: `I`
  - Modern approach to UI testing

---

## Open Source / Reference

- **[swiftlang/swift-corelibs-xctest](https://github.com/swiftlang/swift-corelibs-xctest)** — Type: `Repo` | Level: `A`
  - Open source implementation of XCTest — useful for understanding how it works internally

---

## Practical Guides

- **[Bugfender – Swift Unit Testing with XCTest](https://bugfender.com/blog/swift-unit-testing-xctest-framework/)** — Type: `Article` | Level: `I`
  - Clear walkthrough of writing your first XCTest unit tests
- **[Hacking with Swift – Unit testing SwiftUI](https://www.hackingwithswift.com/quick-start/swiftui/how-to-add-testing-to-a-swiftui-app)** — Type: `Article` | Level: `I`
  - How to structure SwiftUI apps to be testable

---

## Swift Student Challenge minimum testing guide

You don't need full coverage — but a few tests signal that you write professional code.

**Recommended minimum:**
- 3–5 unit tests covering core business logic (pure functions, state transitions)
- 1 UI test: app launches, reaches the main screen, performs the key user action
- Test names should be readable: `test_whenUserTapsButton_thenScoreIncreases()`

**What to test:**
- [ ] Score calculations, game logic, or data transformations
- [ ] Data model mutations (that the right fields update)
- [ ] Edge cases: empty input, zero, negative values

**What not to worry about:**
- Testing SwiftUI views directly (hard, low value for SSC)
- 100% coverage (unrealistic for a competition project)
