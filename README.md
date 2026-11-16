# About the author

I first built **AbCS** (Audiobook Collector Scanner) in Microsoft Access about two years ago. After I retired, I decided to learn Python more seriously. I had started dabbling just before retirement, partly because Microsoft Excel now includes Python.

I spent a couple of months learning Python and experimenting with it, and I quickly found that many graphical interfaces were not very accessible. I wanted to know why. PySide6’s Qt widgets do support screen readers when they are used carefully, so I rewrote the Access version of AbCS in Python with PySide6. Throughout that work I wrote down coding rules and workarounds that improved screen reader access. Those notes became a separate open reference, [pyside6-screen-reader-accessibility](https://github.com/cfdrakeNS/pyside6-screen-reader-accessibility): practical patterns for dialogs, focus, tables, status announcements, and date fields, with a small runnable demo.

At the start I used an AI coding agent to convert about 15,000 lines of VBA and queries into SQLite and Python. The queries converted cleanly; the VBA-derived logic only partly worked, and I spent a lot of time fixing the conversion. The agents were still useful and saved a lot of time. They remind me of years when I wrote pseudocode for other programmers: they rarely make syntax errors, but they need clear instructions. If you let them, they will also take you down deep rabbit holes.

Before AbCS, I worked on screen reader accessibility for terminal applications, including [Talk3270](https://talk3270.auroraaccessibility.com/) (JAWS scripts for IBM 3270/5250 screens).

## Links

- [AbCS product page](https://abcs.auroraaccessibility.com/)
- [AbCS source on GitHub](https://github.com/cfdrakeNS/AbCS_Audiobook_Collector_Scanner)
- [PySide6 screen reader patterns](https://github.com/cfdrakeNS/pyside6-screen-reader-accessibility)
- [Talk3270](https://talk3270.auroraaccessibility.com/)
