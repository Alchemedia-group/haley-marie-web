# Haley Marie Makeup Artist — website redesign

A fast, modern static site (HTML, CSS and a little JavaScript, no build step). Open `index.html` in a browser to preview, or host the folder anywhere (Vercel, Netlify, GitHub Pages, standard web hosting).

## Pages

`index`, `bridal`, `services`, `gift-vouchers`, `kind-words`, `gallery`, `contact`, `terms`, `privacy`

## Before launch

1. **Photos** – every image is currently a soft placeholder. To swap one, put your photo in `images/` and replace the placeholder, for example:
   ```html
   <div class="photo photo--tall" data-label="Bridal makeup" role="img" aria-label="Bridal makeup"></div>
   ```
   with
   ```html
   <div class="photo photo--tall"><img src="images/bridal-1.jpg" alt="Bride with soft, natural makeup" loading="lazy"></div>
   ```
   Credit Emily Robinson Photography (and any other photographers) where appropriate.
2. **Terms & conditions** – `terms.html` is a placeholder. Carry the text across from the old site.
3. **Privacy policy** – `privacy.html` is a short draft. Check it against your current policy.
4. **Prices** – none were on the old home page, so pages say "get in touch for a quote". Add them if you'd like to show them.
5. **Testimonials** – only Sarah Thompson's quote was available. Add more on `kind-words.html`.
6. **Forms** – the enquiry form and newsletter box currently open the visitor's email app. For a proper form, connect a service such as Formspree or Netlify Forms.
7. **Eye enhancements** – copy is deliberately general. Add specifics (what's offered) on `services.html`.
8. **Content added by the redesign** – the "How it works" steps, bridal journey, FAQs and gift voucher steps are suggested copy. Edit them so they match how Haley actually works.
