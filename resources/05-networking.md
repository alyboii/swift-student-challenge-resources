# Networking (05)

URLSession, REST API calls, JSON decoding, error handling, and offline-first patterns.

---

## Official

- **[URLSession (Apple documentation)](https://developer.apple.com/documentation/foundation/urlsession)** — Type: `Doc` | Level: `I`
  - The primary Apple networking API — no third-party library needed for most SSC projects
- **[Fetching website data into memory (Apple)](https://developer.apple.com/documentation/foundation/url_loading_system/fetching_website_data_into_memory)** — Type: `Doc` | Level: `I`
  - Practical guide for making HTTP requests
- **[WWDC21: Use async/await with URLSession](https://developer.apple.com/videos/play/wwdc2021/10095/)** — Type: `Video` | Level: `I`
  - Modern async networking — replaces completion handlers entirely

---

## JSON Decoding

- **[Encoding and Decoding Custom Types (Apple)](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types)** — Type: `Doc` | Level: `I`
  - The `Codable` protocol — how to parse JSON into Swift structs
- **[Using JSON with Custom Types (Apple)](https://developer.apple.com/documentation/foundation/archives_and_serialization/using_json_with_custom_types)** — Type: `Doc` | Level: `I`
  - Handling nested structures, custom keys, and optional fields

---

## Practical Guides

- **[Swift by Sundell – Networking tag](https://www.swiftbysundell.com/tags/networking)** — Type: `Article` | Level: `I`
  - Well-explained networking articles with real-world patterns
- **[Hacking with Swift – URLSession tutorial](https://www.hackingwithswift.com/books/ios-swiftui/sending-and-receiving-codable-data-with-urlsession-and-swiftui)** — Type: `Article` | Level: `I`
  - URLSession + Codable + SwiftUI in one practical walkthrough

---

## Swift Student Challenge checklist

- [ ] All network calls use `async/await` — no callback pyramids
- [ ] Errors are handled and shown to the user — no silent failures
- [ ] API keys (if any) are not hardcoded in source — use a config file excluded from the submission or a public API that doesn't require keys
- [ ] App handles offline state gracefully — at minimum, shows a clear error message
