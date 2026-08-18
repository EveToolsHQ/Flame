Changelog: <https://useflame.app/en/changelog>

## 1.6.0 - 2026-08-17

- **Firestore**:
  - Faster table view for large collections
  - Expand/collapse nested fields
  - Inline edit improvements

## 1.5.0 - 2026-07-25

- **App**:
  - More performant tables across the whole app
  - Resizable table columns
  - Mutation history window to browse and inspect past changes with diffs
  - Settings redesign with clearer connection management
- **Auth**: Inline editing matches Firestore experience
- **Firestore**:
  - Table view mode 🎉
  - Display settings for timestamps, geopoints, and numbers
  - Better inline field editing
  - Batch delete collections via multiselect
  - More context in delete confirmation modals
  - Index watcher now supports collection group indexes that belong in `fieldOverrides`
- **Storage**: Better file details panel including new text file preview

## 1.4.0 - 2026-07-17

- **App**: More context menu options (copy ID, value, path, open in Firebase Console, etc.)
- **Firestore**:
  - Highlight changes when document changes externally
  - Type-colored field values
  - Column headers redesign

## 1.3.0 - 2026-07-16

- **App**:
  - Connect to live Firebase projects 🔥 (beta)
  - Read-only mode (default for live projects)
  - Settings redesign
- **Auth**:
  - Reworked add/create user UX
  - Click a row to edit
  - Copy field value in any table field
- **Firestore**:
  - Field-level undo/redo
  - Improved handling of document references
  - Keep a journal of changes for any mutation

## 1.2.0 - 2026-06-30

- **App**:
  - Resizable left sidebar with snapping 🧈
  - Improved project switching, untangle port vs. project name
  - macOS: simplified menu bar behavior on close
- **Firestore**:
  - Horizontal scroll in narrow document columns
  - Allow to clear requests and indexes tables
- **Storage**:
  - Improved navigation
  - Fix drag and drop
  - Put aside empty buckets in the bucket selector
  - Switching project now picks proper bucket

## 1.1.0 - 2026-06-18

- **App**: Subscription support with free trial

## 1.0.0 - 2026-06-11 🎉

- **App**:
  - Left sidebar instead of top tabs and general redesign
  - Full-size settings and Firestore requests
  - Menu bar / tray support, run in the background to watch for indexes (see below)
- **Firestore**:
  - Firestore indexes watching, find out requests that will need an index in prod and add to `firestore.indexes.json`!
  - Improved request details view

## 0.10.0 - 2026-05-13

- Global design system update

## 0.9.1 - 2026-05-11

- **App**: Add a reload menu item and shortcut
- **Auth**: Fix disabling users
- **Firestore**: More robust syncing and caching with self-heal
- **Queues**: Fix double-encoding in queue messages

## 0.9.0 - 2026-04-29

- **Logs**: Redesigned logs tab with better JSON and multiline text handling

## 0.8.2 - 2026-04-19

- **App**: Faster ⌘K performance and support for jumping to a Firestore path
- **Firestore**:
  - Better performance when viewing large collections and when resizing the window
  - Better column and subcollection navigation UX

## 0.8.1 - 2026-04-11

- **Firestore**:
  - Fix string values containing `/` being mistaken for document references
  - Fix timestamp editing and date picker
  - Fix boolean type conversion
  - Fix rerenders during column resizing

## 0.8.0 - 2026-04-10

- **App**: Same version but **now available on Linux!**

## 0.8.0 - 2026-04-01

- **App**:
  - Same version but **now available on Windows!**
  - And no this is not an April fools 😉

## 0.8.0 - 2026-03-15

- **App**:
  - Fix app icon
  - Fix tabs overflow
  - Fix lag in bug report text field
- **Firestore**:
  - Multiple databases support, identifying default database from `firebase.json`
  - Cache data by project/database to avoid full refresh when switching
  - For so new documents show up immediately when added to a new collection

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

- **App**:
  - Optimize rerenders and disk access
  - Auto-discover emulators on boot
  - Translations
- **Firestore**: Nested fields, geopoints, references

## 0.3.x - 2026-01-19

- **App**: Footer with project switcher and system versions
- **Firestore**:
  - JSON editor full height
  - Copy ID
  - Delete collection cache fix
- **Storage**: Editable breadcrumb path

## 0.2.x - 2026-01-15

- **App**: Auto update
- **Firestore**:
  - Fix timestamp issues
  - Allow to turn off denied requests badge
