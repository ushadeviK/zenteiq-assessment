 Dashboard Fixes

- Fixed application loading and rendering issues.
- Corrected sidebar navigation between Dashboard, Assignments, and Announcements.
- Improved student search to support case-insensitive matching and trimmed whitespace.
- Fixed department filtering logic.
- Corrected project progress calculations and display.
- Fixed Open Assignments section to show only incomplete assignments.
- Corrected average project progress calculation.
- Fixed student details modal opening behavior.

Assignment Planner Fixes

- Fixed assignment creation form state handling.
- Prevented form fields from overwriting each other while typing.
- Corrected required field validation.
- Reset form after successful assignment creation.
- Fixed assignment completion toggle to update UI immediately.
- Improved assignment sorting behavior.

Theme & Persistence

- Fixed light/dark theme switching.
- Added theme persistence using localStorage.
- Restored saved theme after page refresh.

Responsive UI Improvements

- Fixed mobile sidebar open/close behavior.
- Improved responsiveness for mobile, tablet, and desktop screens.
- Reduced layout overflow issues in tables and cards.

Code Quality Improvements

- Removed unused imports and unnecessary console logs.
- Avoided direct state mutation.
- Improved React key usage.
- Added accessibility improvements for forms and modal interactions.

Bonus Improvements

- Added keyboard support to close the student modal using Escape.
- Improved empty states across dashboard sections.
