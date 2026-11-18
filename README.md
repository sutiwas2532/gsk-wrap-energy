# GSK Three Rockets v8 (realtime + TH/EN)

LED page: `/mc-cinizax0a8.html` · Phone page: `/` (same as `/mobile.html`)

v8 adds:
- TH/EN language switch on the phone (top-right TH | EN, remembered per phone) and on the LED
  (operator bar button 🌐 or key L; `?lang=en` also works). INNOVATE / EXECUTE / ACCELERATE stay English.
- LED operator bar is hidden by default and much smaller. It appears only when the mouse goes to the
  bottom edge of the screen, or with key H. All keys (→/Space, R, F, S, L, [ ]) work while it is hidden.

Deploy: `npx wrangler deploy` in this folder, or push to the branch Cloudflare builds from.
