# Roadcress 1.0 TEST
Native Android Bosnian Road spacing puzzle. Android 8+ (min26), target35. Package com.gg007.roadcress. Twelve original unique boards on a compact 5x4 grid.

## Rules
Bosnian Road on a 5x4 grid. Shade one closed one-cell-wide loop travelling horizontally and vertically. Every shaded cell has exactly two side-neighbors on the loop. No branches, separate loops or filled 2x2 blocks. Nonconsecutive parts cannot touch, even diagonally; the two arms of an ordinary bend may meet diagonally at that bend. Gold number cells stay unshaded and count ALL shaded cells among their eight surrounding neighbors, including diagonals. Other cells may stay empty. Tap cells to toggle, undo/reset and next/levels; saved palette and optional road-cell marks. No timer or score. Known Bosnian Road adaptation.

## Download and status
https://mega.co.nz/#!hMUlmYxD!ektzcAdB5meOy6UJDH0oaUfw0RUq3KJs9Y7ioUictzg
APK SHA256 0f667e56e324b23f511cb84732e338b520e98b7aedab44438894b70dd28161a1; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
The portable seed-681109 generator enumerates 38 spaced loops by vertex-path search and reduces clues while retaining one solution per board. An independent ordered-cycle traversal checks all 1,048,576 shadings, traces the cycle, and rejects nonconsecutive near-contacts. It agrees with production degree, diagonal, 2x2 and bit-flood checks on all shapes. All 12,582,912 full-board comparisons also agree on eight-neighbor clue counts and clue exclusion. Twelve unique clue boards and twelve different solutions. Clue locks, bounds, undo/reset and solved lock pass. Actual drawing-adapter taps solve all twelve and check undo/replay, next, levels, menu, privacy and saved palette/road marks. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 199 current live studio descriptions and byte-current 803 web registry entries using functional terms. No Bosnian Road or eight-neighbor shaded-loop match in this partial corpus. Coilcress makes an open snake with fixed ends and row/column totals. Roadcress instead closes a spaced loop and uses local eight-neighbor clues on unshaded cells. Known Bosnian Road adaptation; original generated layouts, code and visuals. No copied layouts/code/art or global invention claim. Six fetched rule pages across six sites agree on core rules. No history claim.
Rules https://wiki.logic-masters.de/index.php/Bosnian_Road/en ; independent rules https://prasannaseshadri.wordpress.com/2012/09/08/puzzle-208-210-bosnian-road-diagonal-neighbors-tapa-domino-loop/ .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/roadcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.roadcress.RoadBoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Roadcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, road-cell marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 200-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/i3v3cqlzu0m7-roadcress-source-archive . Repository https://github.com/iLanis-agent/roadcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
