# iOS Device Specs Reference

Quick-reference tables for designing iOS apps. All dimensions in **points (pt)** unless noted — points are what you design in, pixels are what you export at.

---

## iPhone 17 Series (Current — Sept 2025)

| Device | Display | Points (portrait) | Pixels (portrait) | Scale |
|---|---|---|---|---|
| iPhone 17 | 6.3" | 402 × 874 pt | 1206 × 2622 px | @3x |
| iPhone 17 Air | 6.5" | 420 × 912 pt | 1260 × 2736 px | @3x |
| iPhone 17 Pro | 6.3" | 402 × 874 pt | 1206 × 2622 px | @3x |
| iPhone 17 Pro Max | 6.9" | 440 × 956 pt | 1320 × 2868 px | @3x |

## iPhone 16 Series (Sept 2024 — still widely in use)

| Device | Display | Points (portrait) | Pixels (portrait) | Scale |
|---|---|---|---|---|
| iPhone 16 | 6.1" | 390 × 844 pt | 1170 × 2532 px | @3x |
| iPhone 16 Plus | 6.7" | 430 × 932 pt | 1290 × 2796 px | @3x |
| iPhone 16 Pro | 6.3" | 402 × 874 pt | 1206 × 2622 px | @3x |
| iPhone 16 Pro Max | 6.9" | 440 × 956 pt | 1320 × 2868 px | @3x |

## iPhone SE — Home Button

| Device | Display | Points (portrait) | Pixels (portrait) | Scale |
|---|---|---|---|---|
| iPhone SE (3rd gen) | 4.7" | 375 × 667 pt | 750 × 1334 px | @2x |

---

## iPad (Current Lineup)

| Device | Display | Points (portrait) | Pixels (portrait) | Scale |
|---|---|---|---|---|
| iPad mini (8.3") | 8.3" | 744 × 1133 pt | 1488 × 2266 px | @2x |
| iPad (11") | 11" | 820 × 1180 pt | 1640 × 2360 px | @2x |
| iPad Air (11") | 11" | 820 × 1180 pt | 1640 × 2360 px | @2x |
| iPad Air (13") | 13" | 1024 × 1366 pt | 2048 × 2732 px | @2x |
| iPad Pro (11") | 11" | 834 × 1194 pt | 1668 × 2388 px | @2x |
| iPad Pro (13") | 13" | 1032 × 1376 pt | 2064 × 2752 px | @2x |

---

## Safe Areas

Safe areas define where it's safe to place interactive content — away from the Dynamic Island, home indicator, and rounded corners.

### Face ID iPhones (Dynamic Island)

| Orientation | Top | Bottom | Left | Right |
|---|---|---|---|---|
| Portrait | 59 pt | 34 pt | 0 | 0 |
| Landscape | 0 | 21 pt | 59 pt | 59 pt |

### Home Button iPhones (iPhone SE)

| Orientation | Top | Bottom | Left | Right |
|---|---|---|---|---|
| Portrait | 20 pt | 0 | 0 | 0 |
| Landscape | 0 | 0 | 0 | 0 |

---

## Key Constants

| Item | Value |
|---|---|
| Minimum touch target | 44 × 44 pt |
| Status bar height (Dynamic Island) | 59 pt |
| Home indicator height | 34 pt |
| Navigation bar height | 44 pt |
| Tab bar height | 49 pt |
| Tab bar height with home indicator | 83 pt |
| Standard margin | 16 pt |
| Large title margin | 20 pt |

---

## App Store Screenshot Sizes

Apple uses your largest submission and scales down automatically. Only two sizes are required.

| Device | Required size (portrait) | Required size (landscape) |
|---|---|---|
| iPhone (6.9") | 1320 × 2868 px | 2868 × 1320 px |
| iPad (13") | 2064 × 2752 px | 2752 × 2064 px |

### App Preview Video
- Duration: 15–30 seconds
- File size: max 500 MB
- Resolution: same as required screenshot size for that device
- Max 3 videos per localization

---

## Resources

- [iosref.com](https://iosref.com/res) — Complete up-to-date iOS resolution reference for every device ever made
- [iOS Safe Area Guide for Figma](https://www.figma.com/community/file/1425591247196745890/ios-safe-area-guide-iphone-17-and-older) — Safe area frames for all iPhone models including iPhone 17
