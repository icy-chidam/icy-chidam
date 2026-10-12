# Profile README setup

This package contains:

- `README.md` — your GitHub profile landing page.
- `assets/asic-layout-animation.gif` — the custom looping chip-layout animation embedded in the README.
- `.github/workflows/generate-snake.yml` — a workflow that generates your contribution-snake SVGs/GIF and publishes them to an `output` branch.

## Publish it

1. Create or open the **public** repository named `icy-chidam` (exactly your GitHub username).
2. Upload `README.md` to the repository root.
3. Upload the entire `assets` folder so the repository path `assets/asic-layout-animation.gif` exists.
4. Upload `.github/workflows/generate-snake.yml` to that exact path.
5. In the repository, open **Settings → Actions → General** and make sure workflows are allowed to run. Under **Workflow permissions**, enable **Read and write permissions** if the workflow is blocked from publishing the `output` branch.
6. Open **Actions → Generate contribution snake → Run workflow** to create the first snake assets. After the run succeeds, the snake appears in the README; it will be refreshed daily by schedule.
7. Visit `https://github.com/icy-chidam` and refresh.

## Uploading through the GitHub website

Use **Add file → Upload files** to upload `README.md` and the `assets` folder. To add the workflow, create `.github/workflows/generate-snake.yml` using **Add file → Create new file** and paste in the workflow contents, or upload it while preserving the folder structure.

The animated chip-layout graphic is an illustrative visual created for this profile, not a claim that it is a real GDSII screenshot. The external statistics, typing, and activity cards rely on third-party services and can occasionally load slowly or be rate-limited.
