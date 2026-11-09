# Genome Pattern Lab — Version 2.0

An educational, responsive static website for the Computational Biology assignment.

## Files
- `index.html` — complete website (HTML, CSS and JavaScript in one file)
- `README.md` — this guide
- `vercel.json` — static deployment configuration

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge or Firefox.
3. No installation or server is required.

## Deploy with GitHub and Vercel
1. Create a new GitHub repository.
2. Upload the three files in this folder (not the ZIP file).
3. Open Vercel and sign in with GitHub.
4. Import the repository.
5. Keep Framework Preset as `Other`; leave build command and output directory empty/default.
6. Click Deploy.

## Features
- DNA sequence validation and composition analysis
- Six assignment features: A, T, G, C, length and GC content
- Original four-row assignment dataset and CSV export
- Educational CART-style decision tree, prediction path and training-set accuracy
- Reverse complement, motif finder, equal-length sequence comparison
- Single-base mutation simulator and simple FASTA reader
- Downloadable project summary report
- Responsive dark dashboard

## Academic note
The assignment's dataset contains only four labelled samples. Training-set accuracy is not independent test accuracy. The unknown sequence has no supplied true label, so its predicted group cannot be verified from the assignment data. This JavaScript demonstration does not replace a Python/Google Colab program if the instructor requires one.
