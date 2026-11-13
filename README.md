
# 7‑3‑1‑Fixer JS


A lightweight JavaScript/HTML port of the original 731‑Check tool, which was initially developed as a component for an embedded C project.
The tool calculates 7‑3‑1 check digits, validates serial numbers, and can repair incomplete sequences by reconstructing missing digits using the 7‑3‑1 algorithm.


## Why?
The 7-3-1 checksum appears in many places, including animal ID numbers.
The information available before the work starts is not always complete; digits can be missing from pre-received numbers, sequences cut off.
This is a tool I use myself to double-check such numbers and predict how a workflow will take shape before all the data is in place.
Doing that by hand is slow and error-prone, and the original 731-Check was a C component tied to an RFID embedded project.
So I ported the algorithm itself into a single page that runs in any browser.


## Features
 - Check‑digit calculation (7‑3‑1 method)
 - Serial‑number validation
 - Repair mode for missing digits (Placeholder "?")
 - Multi‑language UI (EN / SV / FI)
 - 100% client‑side, no dependencies


## Usage
Open the page in any browser, enter a serial number, and choose whether to calculate, validate, or repair it.


## Live Demo
https://framstu.github.io/7-3-1-Fixer_JS/


## Files
 - index.html — full app (HTML, CSS, JS)
 - README.md — project description


## License
MIT


## Author
Matias Back
https://github.com/framstu