# Award Trip Itinerary Template

A private-by-default, mobile-friendly trip dashboard for award travelers coordinating flights, hotels, lounges, booking accounts, points, fees, and family contributions.

Everything runs from one `index.html` file. There is no database, build step, framework, analytics, or external dependency.

## Customize it

1. Open `index.html` in a text editor.
2. Find the `TRIP_DATA` block near the bottom.
3. Replace the sample trip, travelers, bookings, lounges, notes, balances, metrics, and accounts.
4. Keep booking dates in `YYYY-MM-DD` format so chronological sorting works.
5. Open `index.html` in a browser to preview it.

Each traveler needs a short unique `id`. Use those same IDs in every booking's `people` list and every lounge's `people` list. Monetary totals and CPP statistics are intentionally entered manually because award-trip valuations often involve credits, certificates, foreign currencies, and subjective cash comparisons.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder so `index.html` is at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then save.

GitHub will display the public URL after the deployment completes.

## Privacy checklist

Before publishing publicly, check for confirmation numbers, loyalty-account numbers, exact hotel room details, private family notes, or anything else you would not want indexed by a search engine. This sample intentionally contains no real booking information.

## Included features

- Responsive single-file design
- Overview filtering by traveler
- Separate and combined chronological sorting
- CPP and cash-value sorting
- Compact itinerary view
- Lounge list with traveler filters
- Booking-status and attention tracking
- Collapsible family balance snapshot
- Booking-account ledger
- Trip and account statistics
- Print-friendly styling
