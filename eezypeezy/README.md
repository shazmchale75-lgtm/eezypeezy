# 🫛 EezyPeezy — Deployment Package

**Snap what's in your fridge. Eat well tonight.**

---

## What's in this folder

| File | What it is | URL when live |
|---|---|---|
| `index.html` | Landing page | eezypeezy.app |
| `app/index.html` | The working app (camera → recipes) | eezypeezy.app/app |
| `brand/index.html` | Brand identity reference | eezypeezy.app/brand |

---

## How to deploy on Vercel (free, ~5 minutes)

1. Go to **vercel.com** and sign up free
2. Click **"Add New Project"**
3. Upload this entire folder (drag & drop)
4. Vercel gives you a preview URL instantly — test it on your phone
5. When happy, connect your domain (eezypeezy.app or eezypeezy.ie)

---

## Before you go live — checklist

- [ ] Check eezypeezy.app is available on Namecheap
- [ ] Register eezypeezy.ie on Blacknight.ie (~€15/yr)
- [ ] Search "EezyPeezy" at ipoi.gov.ie (Irish trademark)
- [ ] Search "EezyPeezy" at euipo.europa.eu (EU trademark)
- [ ] Register EezyPeezy Limited at cro.ie (€50)
- [ ] Replace placeholder testimonials with real user quotes
- [ ] Add your real email to the contact link in footer

---

## The app requires an Anthropic API key

The app (app/index.html) calls the Claude AI to generate recipes.
When deploying properly, move the API call to a backend so your
key is never exposed. For testing, it works as-is.

---

*EezyPeezy — Built March 2026*
*Total cost to launch: ~€324 (domain + trademark + company registration)*
