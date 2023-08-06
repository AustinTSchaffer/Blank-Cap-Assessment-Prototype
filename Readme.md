# Blank-Cap Assessment Prototype

This single page HTML/CSS/VanillaJS application contains a rough proof-of-concept.

Please note that the application is missing many quality of life features:

- The entire application clearly needs a designer.
- Selecting specific parameters should invalidate others
  - Selecting "spongebath" bathing type should automatically score 0 for transfer-in and transfer-out
  - Selecting "bedside commode" toileting type should disallow setting "access and transfer to toilet" score to 4.
- No output. Currently the app is display-only. Does not allow you to download results.
- All code is inline with markup. There is no interface layer between the form and the
- Templating. This document contains a lot of duplication, which could make future changes more difficult.
- The total max section scores (the "of X" parts of the form) are hard-coded.
