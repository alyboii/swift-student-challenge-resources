
# Testing (07)

Unit test, UI test, Xcode test workflow, pratik örnekler.

---

## Resmi (Apple)
- **XCTest (overview)**  
  https://developer.apple.com/documentation/xctest
- **XCTestCase (API)**  
  https://developer.apple.com/documentation/xctest/xctestcase
- **WWDC25: UI automation with Xcode / XCTest**  
  https://developer.apple.com/videos/play/wwdc2025/344/

---

## Open-source / referans
- **swiftlang/swift-corelibs-xctest** — XCTest’in open-source versiyonu (Swift packages vb.)  
  https://github.com/swiftlang/swift-corelibs-xctest

---

## Pratik rehber (kolay anlatım)
- **Bugfender – Swift Unit Testing with XCTest**  
  https://bugfender.com/blog/swift-unit-testing-xctest-framework/

---

## Swift Student Challenge için “minimum testing” önerisi
- En az 3-5 kritik fonksiyon için unit test yaz (pure logic).
- UI çok kompleksse: en az 1 UI test (launch + 1 kritik akış).
- Test isimleri okunur olsun: `test_whenX_thenY()`.
