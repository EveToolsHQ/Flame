Changelog: <https://flame.evetools.app/en/changelog>

## 0.8.1 - 2026-04-11

- **Firestore**:
  - Fix string values containing `/` being mistaken for document references
  - Fix timestamp editing and date picker
  - Fix boolean type conversion
  - Fix rerenders during column resizing

## 0.8.0 - 2026-04-10

- **App**:
  - Same version but **now available on Linux!**

## 0.8.0 - 2026-04-01

- **App**:
  - Same version but **now available on Windows!**
  - And no this is not an April fools 😉

## 0.8.0 - 2026-03-15

- **Firestore**:
  - Multiple databases support, identifying default database from `firebase.json`
  - Cache data by project/database to avoid full refresh when switching
  - For so new documents show up immediately when added to a new collection
- **App**:
  - Fix app icon
  - Fix tabs overflow
  - Fix lag in bug report text field

## 0.7.1 - 2026-02-13

- **Firestore**:
  - Improve the JSON editor
  - Fix constant redirecting issue
  - Allow to change the bug report screenshot
  - Improve filtering and sorting

## 0.7.0 - 2026-02-06

- **Firestore**:
  - Fix cache staleness issues in Firestore data
  - Improve document selection UX
  - Better performance with long document lists

## 0.6.4 - 2026-02-03

- **Firestore**: Improve requests view

## 0.6.3 - 2026-02-01

- **Firestore**:
  - Add, remove, delete, and change type of array items
  - Reflect that Firestore doesn't allow nested arrays
  - Fix blur after changing field type

## 0.6.2 - 2026-01-31

- **App**: Cleanup bug report screenshots

## 0.6.1 - 2026-01-29

- Minor bug fixes and improvements

## 0.6.0 - 2026-01-29

- **Firestore**:
  - Map and array inline editing
  - Filtering
  - Refresh collections on focus
- **Settings**: Fix infinite rerender

## 0.5.0 - 2026-01-23

- **Auth**: Email verified in main table
- **Firestore**: Sort collections
- **Storage**:
  - Fix drag-to-parent bug
  - Preserve content type when moving files
  - Fix copy to clipboard and path navigation

## 0.4.0 - 2026-01-21

- **Performance**: Optimize rerenders and disk access
- **Firestore**: Nested fields, geopoints, references
- **App**:
  - Auto-discover emulators on boot
  - Translations

## 0.3.x - 2026-01-19

- **Firestore**:
  - JSON editor full height
  - Copy ID
  - Delete collection cache fix
- **Storage**:
  - Editable breadcrumb path
- **App**:
  - Footer with project switcher and system versions

## 0.2.x - 2026-01-15

- **Firestore**:
  - Fix timestamp issues
  - Allow to turn off denied requests badge
- **App**:
  - Auto update
