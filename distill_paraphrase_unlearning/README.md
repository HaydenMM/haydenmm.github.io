# Distillation + Paraphrasing Further Robustifies Unlearning

Static GitHub Pages report for the benign trigger-transfer experiment comparing raw distillation, UNDO, and strict paraphrase-distillation.

## Files

- `index.html` — the GitHub Pages landing page.
- `assets/` — plots and the metrics CSV.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and the `assets/` folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose `main` and `/root`, then save.
6. GitHub will provide the public Pages URL after deployment.

## Main result

Raw distillation transfers the benign trigger behavior at 56.2% ASR. UNDO final retains 21.2% ASR. Strict paraphrase-distillation reduces final ASR to 1.3%.
