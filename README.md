# Privacy Policy — GitHub Pages

This folder hosts the **public privacy policy** for **Color Tap Challenge** by **B47 Tech**.

Play Store requires a URL that:

- Is publicly accessible (no login)
- Opens in a browser
- Names the app
- Explains data handling (including AdMob / UMP)
- Includes a contact method

---

## Before you publish

1. Open `docs/index.html`
2. Replace **both** occurrences of:
   ```text
   privacy@YOUR-EMAIL-DOMAIN.com
   ```
   with your real privacy/support email.
3. Update the **Effective date** if needed.
4. Commit and push to GitHub.

---

## Enable GitHub Pages

1. Push this repository to GitHub (public repo recommended for free Pages).
2. On GitHub: **Repository → Settings → Pages**
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/docs`
4. Click **Save**.
5. Wait 1–5 minutes. GitHub shows your site URL, for example:
   ```text
   https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME/
   ```

Your privacy policy URL for Google Play Console is that URL (it serves `docs/index.html` automatically).

**Example:** If your username is `b47tech` and repo is `colortapchallenge`:
```text
https://b47tech.github.io/colortapchallenge/
```

---

## Use in Google Play Console

1. **App content → Privacy policy**
2. Paste your GitHub Pages URL
3. Ensure the page loads without login in an incognito/private browser window

---

## Optional: link from the app

After Pages is live, you can add the URL to the in-app Privacy screen in a future update.
Play Console only requires the public URL — the in-app screen can remain a summary.

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full privacy policy page |
| `.nojekyll` | Prevents Jekyll processing on GitHub Pages |
| `README.md` | This setup guide |

---

## Security note

Do **not** put keystore passwords, AdMob secrets, or signing keys in this folder.
This folder is public when GitHub Pages is enabled.
