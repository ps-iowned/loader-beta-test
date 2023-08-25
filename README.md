Private beta rules
-
Beta is private because probably many bugs to fix with custom menu.
- No troll, no flame, no insult. Bug reports with details only. If troll, banned.
- Bugs with custom menu only. Emulation bugs for ARM firmware, not custom menu.
- If game work with original menu but not custom menu, report bug.
- If game not work with original menu, don't report bug.
- Make github issue to report bugs. No feature request.
- Can share screenshots and video of custom loader outside. Beta only private for quality bug reports.

Instructions
-
- Change PSIO settings with original MENU.SYS.
- Backup original MENU.SYS file.
- Replace MENU.SYS with one download here.
- Power on.
- Select game from list with up/down.
- Press X to boot game.
- If problem, open github issue here, with:
   - Version of PSIO.
   - Version of ARM firmware.
   - Version of PS1 console.
   - Picture or video of bug.

Status
-
- Only 512 games. Need more testing for more than 512 games.
- No CDDA/XA. Kernel patch is dangerous. Coming soon.
- No game list sort. Coming soon.
- PAL offcentered. Issues: https://github.com/ps-iowned/loader-beta-test/issues/2, https://github.com/grumpycoders/pcsx-redux/issues/1405

ARM Firmware | Status | Issue
-------------|--------|----
2.5.4        | Menu boot, games boot |
2.6.1        | Menu boot, games boot | https://github.com/ps-iowned/loader-beta-test/issues/2
2.7.14       | Menu not boot | https://github.com/ps-iowned/loader-beta-test/issues/1

Downloads
-
Downloads are [here](versions). Sorted by date. Possible to downgrade and test multiple versions.
- [2023-08-25-01 @ PAL fix, iso fix](versions/2023-08-24-01-012bbfd6)
- [2023-08-24-01 @ same version, different iso build](versions/2023-08-24-01-012bbfd6)
- [2023-08-23-01 @ first version](versions/2023-08-23-01-012bbfd6)
