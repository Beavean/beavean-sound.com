# One‑Page Business Site — Royalty (Payoneer) — Implementation Spec (v2.0)

## 0) Goal & Outcome
Public one‑page site for **Anton Petrov** that satisfies Payoneer's "business web page" check and reflects the **Royalty** line of business. Result: live page on a **custom domain**, with clear identity, concise description, and a public link proving work with Reveal Sound.

---

## 1) Line of Business
- **Royalty mode only:** independent sound designer; digital soundbanks (Spire) **distributed by Reveal Sound**; monthly **author royalties**.
- Keep wording **consistent** across site, Payoneer profile, invoices, and any correspondence.

---

## 2) Payoneer Must‑Haves (on the page)
- Show ≥ **two identifiers** (preferably three): full name; **email matching Payoneer**; city & country (match profile); headshot/photo; phone (optional).
- Concise **business description** stating royalty model with Reveal Sound.
- **Work proof link(s):** at least "Reveal Sound — Store"; add 1–2 release links if available.
- **Custom domain**, public access (no login), HTTPS.

---

## 3) Page Structure (Current Implementation)
1) **Top Bar:** Name "Anton Petrov" and email link (sticky navigation)
2) **Hero Section:** Name, role "Sound Designer", tagline, email button, Reveal Sound store link
3) **About Section:** Independent sound designer description with royalty model explanation
4) **Selected Contributions:** Grid of 6 soundbank releases with images and links
5) **Work / Links:** Primary Reveal Sound store link + specific release links
6) **Contact:** Email, Location (Gdańsk, Poland), Phone with contact info card
7) **Footer:** Legal notes, copyright, and payment method information

---

## 4) Visual, UX, Accessibility (Current Implementation)
- **Dark theme:** Background #111316, text #F2F4F7, accent #5EB1FF
- **Typography:** System font stack; 18px body, 36px H1, strong contrast (WCAG AA compliant)
- **Layout:** Responsive grid system; single column mobile, multi-column desktop
- **Images:** Placeholder images from Picsum for soundbank covers (200px height)
- **Accessibility:** Focus states, semantic HTML, descriptive alt texts
- **No animations:** Clean, professional appearance without distracting effects

---

## 5) Technical Implementation
- **Single HTML file:** `index.html` with embedded CSS (no external dependencies)
- **Responsive design:** Mobile-first approach with breakpoints at 768px and 1024px
- **Color scheme:** Dark theme with blue accent (#5EB1FF) for links and CTAs
- **Grid system:** CSS Grid for contributions section, Flexbox for other layouts
- **External links:** All Reveal Sound links open in new tabs with proper rel attributes

---

## 6) Content Details (Current Implementation)
- **Name:** Anton Petrov (appears in top bar, hero, and footer)
- **Email:** anton.petrov@example.com (placeholder - needs real email)
- **Location:** Gdańsk, Poland
- **Phone:** +48 [NUMBER] (placeholder - needs real number)
- **Soundbanks:** 6 featured releases (The Sight, Your Beast, The Void, Into The Deep Vol.2, Spire 90s Dance Essentials, Spire EDM Essentials Vol.3)
- **Primary CTA:** Reveal Sound Spire Store link

---

## 7) Hosting Requirements
- **Static hosting:** Any static host (Netlify/Vercel/Hostinger) with single HTML file
- **Custom domain:** Required for Payoneer verification
- **HTTPS:** Must be enabled
- **No backend:** Pure client-side implementation

---

## 8) Payoneer Verification Checklist
- Site live at `https://yourdomain.tld` (HTTPS) ✓
- Page shows **Name** + **Email** + **Location** ✓
- About section states **royalty** relationship with Reveal Sound ✓
- "Reveal Sound — Store" link present and working ✓
- Content matches Payoneer profile (email/location need verification)
- Full desktop screenshot captured per requirements

---

## 9) Next Steps for Production
1. **Replace placeholder content:**
   - Update email from `anton.petrov@example.com` to real Payoneer email
   - Update phone number from `+48 [NUMBER]` to real number
   - Replace Picsum placeholder images with actual soundbank covers
2. **Deploy to hosting:**
   - Upload `index.html` to chosen static host
   - Configure custom domain with HTTPS
   - Test all links and responsive design
3. **Payoneer verification:**
   - Capture full-page desktop screenshot
   - Submit for business verification
   - Prepare royalty invoice documentation

