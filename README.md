# Genome Pattern Lab

An interactive, responsive educational website for the Introduction to Computational Biology CLA-2 assignment: **Predict the Genome Pattern**.

## Features
- DNA sequence analyzer (accepts A, T, G, C)
- Six feature calculations: A, T, G, C counts, sequence length, GC content
- Assignment dataset table
- CSV export of the feature table
- Browser-based CART-style decision tree trained on the four supplied examples
- Prediction for `ATGCGCGATC`
- Training-set accuracy display with a clear warning about the tiny dataset
- Downloadable plain-text project summary
- Responsive layout for desktop and mobile

## Run locally
This is a static website. No installation or build step is required.

1. Extract the ZIP.
2. Open `index.html` in a browser.

Optional local server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `README.md`, and `vercel.json`.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

## Deploy to Vercel
1. Push the project to GitHub.
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the repository.
4. Choose **Other** as the framework preset (or leave it as a static site if detected).
5. Leave the build command empty and the output directory as `.`.
6. Click **Deploy**.

## Important academic note
The assignment's four labelled DNA sequences are extremely small training data. The displayed accuracy is measured on the same four examples used to train the model; it is not an independent test score and does not establish real-world performance. The unknown sequence has no supplied true label, so its prediction cannot be independently verified.

This browser implementation is a learning demonstration. If your instructor supplied a specific Python/Google Colab program, run that program too and use its output in the formal assignment report.
