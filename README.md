# Akili Risk Intelligence Website

Static HTML/CSS/JS website for Akili Risk Intelligence.

## Pages
- `index.html` — Home
- `services.html` — Services and pricing
- `about.html` — Our Approach
- `contact.html` — Contact

## Cloudflare Pages
This is a plain static site. No framework or package installation is required.

Recommended settings:
- Production branch: `main`
- Build command: leave blank (or use `exit 0`)
- Build output directory: `/` (repository root)

## Before launch
1. Confirm the public email address after domain email is configured.
2. Replace the contact-page placeholder with the final Tally questionnaire URL.
3. Add the final POPIA Privacy Notice page/link.
4. Review service pricing and wording.
5. Add final logo assets if desired.
6. Test desktop and mobile layouts.


## Questionnaire routing update
The Tally questionnaire is embedded only on assessment.html and is reached from the AI Risk Assessment service. Other services route to the general contact page and do not expose the questionnaire. Existing clients are directed to contact Akili for ongoing services and do not need to repeat the initial questionnaire.
