# Freddie’s Health Record

A single-file health record for Freddie, a male Groodle F1 (50% Golden Retriever, 50% Standard Poodle), born 19 July 2022.

Open `index.html` in any browser. There is nothing to install and no external dependencies.

If this repository is published with GitHub Pages from the `main` branch root, the page will be at:

https://bobbyboy14.github.io/freddie-health/

## Updating the record

1. Open `index.html`.
2. Edit the `RECORD` object in the first `<script>` block at the top of the file.
3. A comment above that object explains how to add a log entry: paste a new object at the **top** of the `log` array (newest first), fill in `date`, `sortDate`, `category`, `title`, and `details`, then save and refresh.

If a due item was completed, update or remove it in `upcoming` as well.

## What’s on the page

- Upcoming / due items (monthly wormer, 3-monthly wormer, annual C5 vaccination, dental clean, anal glands visit, grooming)
- Profile, breeder, parents, food, worming schedule, and emergency vet
- Weight history
- Recurring issues
- Chronological health log (newest first)
- Grooming visits and a short to-do list

Dates follow the notes as written. Where a year was unclear, the page marks that rather than guessing.
