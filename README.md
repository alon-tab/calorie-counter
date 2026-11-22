# calorie-counter

## v10

- Personal library with searchable products and reusable multi-ingredient meals.
- Manual products accept label calories, protein, carbs and fat. Values can be entered for any positive gram or ml base and are normalized to 100. Optional unit size.
- Create, edit and delete personal products; old calorie-only products are marked as missing macros until completed.
- Create and edit meal templates directly in the library. Add a separate editable copy to the selected diary date. Adjust component quantities, add or remove components, then save once.
- Product edits and deletions never rewrite existing diary or template snapshots. Template edits never rewrite past diary meals.
- The existing per-day diary, workout tracking, water, reports, settings and food database remain in place.
- Same local-storage key and v1 backup schema. Existing backups remain compatible. v10 backups include personal products and meal templates, including their new optional metadata.

All personal records stay on the device. Browser and home-screen installations may use separate storage. Use backup and restore to move data between them. No account, cross-device sync or external nutrition service is introduced.

## Earlier release

## v9

- A daily workout diary, with time or distance entry, saved estimates and deletion.
- A simple activity chooser with no hiking and at most three options per category.
- Food, estimated activity and food-minus-activity shown separately. The food goal is unchanged. This is not a full energy balance.
- Meals start collapsed under their original names; expand them for products, amounts and editing.
- A more compact daily summary.
- Water cups are 200 ml, with up to 15 cups (3 liters) for tracking. This is not a personal hydration recommendation.
- Local storage and v1 backup schema are preserved. v7/v8 backups still restore; v9 backups also include daily workouts. Older water counts above 15 are retained until reduced.

All personal records stay in the device's local storage. Browser and home-screen installations may use separate storage. Use backup and restore to move data between them.
