# Swift Concurrency (04)

async/await, Task, actors, structured concurrency, and URLSession with async — with practical examples.

---

## Official (most reliable)

- **[Swift Concurrency (Swift.org book chapter)](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/concurrency/)** — Type: `Doc` | Level: `I`
  - The authoritative reference for Swift's concurrency model
- **[Managing structured concurrency (Apple tutorial)](https://developer.apple.com/tutorials/app-dev-training/managing-structured-concurrency)** — Type: `Doc` | Level: `I`
  - Hands-on tutorial with real code
- **[WWDC21: Meet async/await in Swift](https://developer.apple.com/videos/play/wwdc2021/10132/)** — Type: `Video` | Level: `I`
  - The session that introduced async/await — still the clearest explanation
  - YouTube mirror: https://www.youtube.com/watch?v=r_clm92NI1s
- **[WWDC21: Explore structured concurrency in Swift](https://developer.apple.com/videos/play/wwdc2021/10134/)** — Type: `Video` | Level: `I`
  - Task groups, child tasks, cancellation
- **[WWDC21: Use async/await with URLSession](https://developer.apple.com/videos/play/wwdc2021/10095/)** — Type: `Video` | Level: `I`
  - How to modernize your networking code with async/await

---

## Practical Guides (easier reading)

- **[Swift by Sundell – Concurrency hub](https://www.swiftbysundell.com/discover/concurrency)** — Type: `Article` | Level: `I`
  - Curated collection of concurrency articles with clear examples
- **[Swift by Sundell – Concurrency tag](https://www.swiftbysundell.com/tags/concurrency)** — Type: `Article` | Level: `I/A`
  - All concurrency-related articles, including advanced topics

---

## Example Repos

- **[CollectionConcurrencyKit (John Sundell)](https://github.com/JohnSundell/CollectionConcurrencyKit)** — Type: `Repo` | Level: `I`
  - Adds async/concurrent map, filter, and forEach to Swift collections — useful reference

---

## Swift Student Challenge checklist

Before submitting, verify:
- [ ] UI updates happen on `@MainActor` — not calling them from a background task
- [ ] Network calls use `async/await` with URLSession — no callback nesting
- [ ] Long-running tasks use `Task {}` with a cancellation path
- [ ] Shared mutable state is protected with `actor` — no data races
