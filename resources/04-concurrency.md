# Swift Concurrency (04)

async/await, Task, actors, structured concurrency, URLSession async, pratik örnekler.

---

## Resmi (en güvenilir)
- **Swift Concurrency (Swift.org book chapter)**  
  https://docs.swift.org/swift-book/documentation/the-swift-programming-language/concurrency/
- **Apple: Managing structured concurrency (tutorial)**  
  https://developer.apple.com/tutorials/app-dev-training/managing-structured-concurrency
- **WWDC21: Meet async/await in Swift**  
  https://developer.apple.com/videos/play/wwdc2021/10132/
  - YouTube mirror: https://www.youtube.com/watch?v=r_clm92NI1s
- **WWDC21: Explore structured concurrency in Swift**  
  https://developer.apple.com/videos/play/wwdc2021/10134/
- **WWDC21: Use async/await with URLSession**  
  https://developer.apple.com/la/videos/play/wwdc2021/10095/

---

## Pratik rehberler (okuması kolay)
- **Swift by Sundell – Concurrency hub**  
  https://www.swiftbysundell.com/discover/concurrency
- **Swift by Sundell – Concurrency tag**  
  https://www.swiftbysundell.com/tags/concurrency

---

## Örnek repo / paket
- **CollectionConcurrencyKit (John Sundell)** — koleksiyonlarda async/concurrent map vb.  
  https://github.com/JohnSundell/CollectionConcurrencyKit

---

## Hızlı check-list (Swift Student Challenge için)
- UI thread: `@MainActor` nerede gerekli?
- Networking: URLSession async/await ile sadeleşiyor mu?
- Uzun işler: `Task {}` + iptal senaryosu var mı?
- Data yarışları: actor ile korunuyor mu?
