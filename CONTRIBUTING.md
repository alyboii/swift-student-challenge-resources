# Contributing to Swift Student Challenge Resource Library

Thank you for helping make this list better for every SSC applicant.

## What belongs here

A resource is a good fit if it:
- Is directly relevant to building a Swift Playground for SSC
- Covers SwiftUI, UIKit, concurrency, networking, persistence, testing, accessibility, or submission strategy
- Is publicly available (free or freemium — link to the free portion)
- Has been useful to at least one person preparing for SSC

A resource does **not** belong if it:
- Requires a paid subscription with no free preview
- Is outdated and covers deprecated APIs (Swift 4 or earlier, UIKit-only patterns that SwiftUI now handles better)
- Is a generic programming tutorial with no iOS/Swift angle

## How to add a resource

1. **Fork** this repository
2. Open the relevant file in `resources/` (e.g., `resources/02-swiftui.md`)
3. Add your entry using the standard format (see below)
4. **Open a Pull Request** with a short title like `add: [Resource Name] to swiftui`

## Resource format

```
- **[Title](URL)** — Type: `Video/Doc/Article/Repo/Tool` | Topic: `SwiftUI/Concurrency/...` | Level: `B/I/A`
  - Notes: one or two sentences on why it's useful and what makes it different
```

**Type values:**
| Value | Meaning |
|---|---|
| `Video` | YouTube, WWDC session, course video |
| `Doc` | Official documentation, language reference |
| `Article` | Blog post, Medium article, newsletter |
| `Repo` | GitHub repository, example project |
| `Tool` | App, CLI, library, framework |

**Level values:**
| Value | Meaning |
|---|---|
| `B` | Beginner — new to Swift or iOS |
| `I` | Intermediate — comfortable with Swift, building real features |
| `A` | Advanced — architecture, performance, advanced APIs |

**Non-English resources:** Add a language tag at the end of the title — e.g., `(TR)`, `(JA)`, `(ES)`.

## Adding yourself to the Winners table

If you were accepted to SSC and found this repo useful:

1. Open `README.md`
2. Add a row to the Winners & Inspiration table:
   ```
   | 2025 | [@yourusername](https://github.com/yourusername) | App Name (optional) | 🇺🇸 US |
   ```
3. Open a PR with title `winners: add @yourusername (2025)`

No proof required — we trust you.

## Pull Request guidelines

- Keep PRs focused: one resource or one topic per PR (easier to review)
- Verify that your link is live before submitting
- Write a short description of why you're adding the resource
- If you're adding more than 3 resources at once, group them by topic

## Questions?

Open an [issue](https://github.com/alyboii/swift-student-challenge-resources/issues/new) and tag it `question`.
