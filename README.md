# AI//UNBOUND NYC.

Event information for AI//UNBOUND NYC., hosted by PEN Ventures.

## Published page

https://penventures.github.io/ai-unbound/

## Updating the digital pamphlet

Keep the repository name and published URL fixed after printing the QR.
Update `pamphlet.json` to contain the publicly accessible Google Drive sharing URL:

```json
{"pamphletUrl":"https://drive.google.com/file/d/FILE_ID/view"}
```

When pamphletUrl is null, the event information is displayed. With a valid Google Drive or Google Docs HTTPS URL, the page opens the pamphlet automatically and shows a fallback link.

## Publishing

GitHub Pages: deploy from main branch, root directory. `.nojekyll` keeps the files static.

All event content and branding are supplied by PEN Ventures.
