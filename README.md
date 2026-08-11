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

1. Choose **Add rosters…** and select one or more team roster files.
2. Choose **Add PDFs…** and select one or more meet heat sheets.
3. Review the roster colors and output location. Leave **Exact** selected
   for your first run.
4. Choose **3. Highlight PDFs** and wait for the run to finish. Turn on
   **Scanned PDF (Slower)** first when any heat-sheet page is scanned or
   image-only.
5. Review the results, then open each completed highlighted copy or its folder.

## Files you can use

Rosters can be Excel workbooks, comma-separated files, plain-text lists, or
PDF documents with selectable text. Spreadsheet and comma-separated rosters
need a header containing `Name`. Use either one full-name column, or separate
`First Name` and `Last Name` columns. `Nick Name` and `Preferred Name` columns
can supply additional matching choices. A text roster can list one swimmer per
line or separate names with semicolons.

Heat sheets must be PDF documents. Ordinary digital heat sheets with selectable
text use the fastest and most reliable path. For a scanned or image-only heat
sheet, turn on **Scanned PDF (Slower)**. Scanned-page recognition is English
only and can take longer.

## Helpful options

- **Exact match** is the most conservative choice. **Fuzzy** matching can catch
  small spelling differences; turn on fuzzy-match review when you want to
  approve uncertain matches before saving.
- Each roster has its own highlight color, and you can change the color and
  opacity. If the same swimmer appears on more than one roster, the first
  roster's color is used.
- You can add a missing-names summary to the result.
- Optional USA Swimming Standards can be shown with the meet events or added
  as summary pages. Check whether the meet uses SCY, SCM, or LCM before running.
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

- **No swimmers were found:** Check that the roster contains names, confirm
  the first and last names are on the same row, and try fuzzy matching if the
  heat sheet uses slightly different spellings or nicknames.
- **A scanned heat sheet has no selectable text:** Turn on **Scanned PDF
  (Slower)** and run it again.
- **A fuzzy match looks wrong:** Use exact matching, or enable fuzzy-match
  review so you can reject uncertain matches before the result is saved.
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
