
# 7‑3‑1‑Fixer JS


A lightweight JavaScript/HTML port of the original 731‑Check tool, which was initially developed as a component for an embedded C project.
The tool calculates 7‑3‑1 check digits, validates serial numbers, and can repair incomplete sequences by reconstructing missing digits using the 7‑3‑1 algorithm.


## Why?
The 7-3-1 checksum is used in various applications, including animal identification numbers.
Before a workflow begins, however,the preliminary information available for planning may be incomplete.
Some digits may not yet be known, or only part of a sequence may have been provided.

I regularly use this method to double-check preliminary number information, and make sure the workflow is as predictable and reliable as possible.

Being able to calculate check digits, reconstruct missing digits, and verify preliminary information against the expected results helps ensure that everything is consistent before the actual work begins.
I originally developed 731-Check as a component for an embedded RFID project in C, but decided to bring the algorithm to a lightweight, standalone web application that runs directly on any device.


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