# Persistence (06)

SwiftData, CoreData, UserDefaults, and file-based storage — how to save and restore state in your SSC app.

---

## Which option to use?

| Use case | Recommended |
|---|---|
| Simple settings / preferences | `UserDefaults` |
| Small structured data (to-do items, scores, etc.) | `SwiftData` |
| Large datasets, complex relationships | `CoreData` |
| Files, images, exported data | `FileManager` |

For most SSC projects, `SwiftData` or `UserDefaults` is enough.

---

## SwiftData (modern, recommended)

- **[SwiftData documentation (Apple)](https://developer.apple.com/documentation/swiftdata)** — Type: `Doc` | Level: `I`
  - Apple's modern persistence framework, introduced in iOS 17 / macOS 14
- **[WWDC23: Meet SwiftData](https://developer.apple.com/videos/play/wwdc2023/10187/)** — Type: `Video` | Level: `I`
  - The introduction session — covers the core model
- **[WWDC23: Model your schema with SwiftData](https://developer.apple.com/videos/play/wwdc2023/10195/)** — Type: `Video` | Level: `I`
  - Relationships, migrations, and schema design
- **[Hacking with Swift – SwiftData tutorial](https://www.hackingwithswift.com/quick-start/swiftdata)** — Type: `Article` | Level: `I`
  - Practical guide with SwiftUI integration examples

---

## UserDefaults

- **[UserDefaults (Apple documentation)](https://developer.apple.com/documentation/foundation/userdefaults)** — Type: `Doc` | Level: `B`
  - Simple key-value storage — ideal for settings and small state
- **[@AppStorage in SwiftUI (Hacking with Swift)](https://www.hackingwithswift.com/quick-start/swiftui/what-is-the-appstorage-property-wrapper)** — Type: `Article` | Level: `B`
  - SwiftUI wrapper for UserDefaults — one-line persistence

---

## CoreData (for complex data)

- **[CoreData documentation (Apple)](https://developer.apple.com/documentation/coredata)** — Type: `Doc` | Level: `A`
  - Full reference — only needed for complex, relational data models
- **[Core Data by Tutorials (Kodeco)](https://www.kodeco.com/books/core-data-by-tutorials)** — Type: `Article` | Level: `I/A`
  - Comprehensive paid book, but free sample chapters available

---

## Swift Student Challenge checklist

- [ ] App state is preserved when the playground is closed and reopened
- [ ] No data is lost on unexpected termination — save early, save often
- [ ] SwiftData/CoreData models are simple — SSC judges aren't grading your schema
