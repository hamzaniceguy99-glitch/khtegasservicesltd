# KHTE Gas Services — khte gas services ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `khtegasservicesltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/khtegasservicesltd.mjs`).
> To change the content, edit that file and run `node build.mjs khtegasservicesltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@khtegasservicesltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per visit / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
KHTE Gas Services Ltd carries out plumbing, heating and air conditioning work in London, trading since 2020. We install and service boilers and heating systems, issue landlord gas safety records, do general plumbing, and handle air conditioning. Here is the thing to ask any gas engineer, including us. Being on the Gas Safe Register is a legal requirement, but it is not the whole answer: the back of the ID card lists the specific appliance categories that engineer is qualified for. Someone perfectly qualified on domestic boilers may not be qualified on a commercial appliance, a gas fire, or LPG. So ask for the card and read the back, because an engineer working outside their categories is working unlawfully on the most dangerous thing in your building. We show ours before starting. Site: khtegasservicesltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
