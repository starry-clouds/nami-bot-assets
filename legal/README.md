# Nami Bot Legal Pages Setup

This folder contains the legal pages required for Discord app verification.

## Files
- TERMS_OF_SERVICE.md
- PRIVACY_POLICY.md

## Fastest Option (No GitHub Pages)
Use direct GitHub HTTPS URLs after pushing this folder to the public `main` branch:

- Terms URL:
  https://github.com/starry-clouds/nami-bot-assets/blob/main/legal/TERMS_OF_SERVICE.md
- Privacy URL:
  https://github.com/starry-clouds/nami-bot-assets/blob/main/legal/PRIVACY_POLICY.md

These links are public and HTTPS, which satisfies Discord URL requirements.

## Cleaner Option (GitHub Pages, still free)
1. In repository settings, open Pages.
2. Set source to `Deploy from a branch`.
3. Select branch `main` and folder `/(root)`.
4. Save and wait for Pages deployment.

Then use these URLs:
- Terms URL:
  https://starry-clouds.github.io/nami-bot-assets/legal/TERMS_OF_SERVICE
- Privacy URL:
  https://starry-clouds.github.io/nami-bot-assets/legal/PRIVACY_POLICY

## Required Edits Before Use
Update these placeholders in both files:
- `REPLACE_WITH_CONTACT_EMAIL_OR_SUPPORT_LINK`
- `PRIVACY_POLICY_URL_PLACEHOLDER` (in Terms only)
