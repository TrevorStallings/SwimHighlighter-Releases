# Swim Highlighter Downloads

This repository is the official download page for signed Swim Highlighter
Windows installers.

Swim Highlighter helps coaches turn a busy meet heat sheet into an
easier-to-scan copy. Add one or more team rosters and heat sheets, and the app
highlights rostered swimmers with a different color for each roster. Your
original files are left unchanged.

## Download and install

1. Open the [latest Swim Highlighter release](https://github.com/TrevorStallings/SwimHighlighter-Releases/releases/latest).
2. Under **Assets**, download the file whose name ends in `Setup.exe`. The
   source-code downloads offered by GitHub contain only this guide and will not
   install the app.
3. Run the setup file. When Windows shows the publisher, make sure it says
   **Trevor Stallings**. Cancel the installation if a different or unknown
   publisher is shown.
4. Setup installs for your Windows account, so administrator access is not
   required. Finish setup, then open **Swim Highlighter** from the Start menu.

## Quick start

1. Under **1. Roster files**, choose **Add Rosters** and select one or more
   team roster files.
2. Under **2. Heat-sheet PDFs**, choose **Add Heat Sheets** and select one or
   more meet heat sheets.
3. Review file-check status. Use **Advanced** in Roster files for colors,
   optional spelling-match review, and team presets. Use **Advanced** in
   Heat-sheet PDFs for output location, opening finished PDFs, and missing-name
   delivery. Matching and scanned-page recognition run automatically.
4. Choose **Highlight Heat Sheet** when the file checks are ready.
5. Use **Processing Results** to open each completed highlighted copy and any
   available Missing Names, Coach Planning, or Swimmer Meet Summary report.
   **Start Next Meet** keeps the selected rosters and preferences while clearing
   the previous meet's heat sheets and results.

## Files you can use

Rosters can be Excel workbooks, comma-separated files, plain-text lists, or
PDF documents with selectable text. Spreadsheet and comma-separated rosters
need a supported full-name column or a clear first-name/last-name pair, such as
`First Name` and `Last Name`. `Nick Name` and `Preferred Name` columns can add
matching choices. A text roster can list one swimmer per line or separate names
with semicolons.

Heat sheets must be PDF documents. Ordinary digital heat sheets with usable
selectable text take the fast path. Scanned or image-only pages use automatic,
local English OCR when needed, which can take longer. Scanned roster PDFs still
need to be exported as searchable PDFs before adding them.

## Helpful options

- **Name matching** checks strict names first, then uniquely supported spelling
  variations. Optional spelling-match review lets you accept or reject pairs
  before saving; **Review Possible Matches** is a separate opt-in check for
  normally unmatched names and never confirms one automatically.
- Each roster has its own highlight color, and you can change the color and
  opacity. If the same swimmer appears on more than one roster, the first
  roster's color is used.
- You can view a missing-names summary in the app, attach it to the highlighted
  PDF, do both, or suppress the detailed list.
- Optional USA Swimming Standards can be shown with the meet events or added
  as summary pages. Check whether the meet uses SCY, SCM, or LCM before running.
- Optional Coach Planning creates session-only Busy Heats and Competition Gaps
  summaries for highlighted swimmers. Swimmer Meet Summary can compare a
  selected swimmer's seed position, standards progress, and recovery context
  within loaded heat sheets.
- Team presets can remember frequently used roster locations, colors, and
  common options on your computer. They never load automatically.

## Privacy

Roster and heat-sheet documents are processed on your computer. They are not
uploaded, and the original files are not changed. Highlighted results are saved
as new documents in the location you choose.

Highlighted results still contain swimmer information. Handle them with the
same care as the original heat sheet.

The app saves your preferences locally. Its update check requests only public
release information; it does not send roster, heat-sheet, swimmer, output, or
settings data.

## Troubleshooting

- **No swimmers were found:** Check the roster's name columns, the file-check
  results, and whether the heat sheet uses different spellings or nicknames.
- **A scanned heat sheet has no selectable text:** The app checks the page with
  local OCR automatically. If recognition fails, follow the page-specific error
  guidance; scanned roster PDFs must be exported as searchable PDFs first.
- **A spelling match looks wrong:** Enable spelling-match review in Advanced
  Roster Options to reject the pair before the result is saved.
- **The result cannot be saved:** Choose a location where you can save files,
  close an older result if it is open in another program, and try again. The
  app does not overwrite an input heat sheet.
- **Windows shows the wrong publisher:** Cancel setup. Install only the latest
  release that Windows identifies as published by **Trevor Stallings**.

## Updates and platform support

Windows is the only supported platform. There is no supported macOS version or
installer.

Use **Check for updates now** inside Swim Highlighter, or return to the
[latest release page](https://github.com/TrevorStallings/SwimHighlighter-Releases/releases/latest).
The app does not download or install updates automatically; it asks before
opening the installer download or release page.
