# Bottom Line

A phone-only personal finance app (Riseup-style): know what's free to spend this month.

**Open it:** https://yopro1100p.github.io/bottom-line/

Install it on your phone once, then it works offline:

* **iPhone (Safari):** Share → **Add to Home Screen**
* **Android (Chrome):** ⋮ → **Install app**

**Automatic payments:** card and bank SMS (Google Pay charges included) can be logged automatically on Android with a free MacroDroid macro – see **Settings → Automatic payments** in the app. Past months come in from the Excel/CSV files your bank and card company let you download: **Activity → Import**.

Everything runs on the device. Your transactions, budgets and goals are stored only in your phone's browser storage and are never uploaded anywhere. Use **Settings → Your data → Download backup** now and then.

This repository holds only the built app. The source code (React + an on-device engine, plus an optional FastAPI server version) is in [Dekel23/Biological-Computation](https://github.com/Dekel23/Biological-Computation/tree/ccr-2b0ca827-exxqh5/riseup-clone), branch `ccr-2b0ca827-exxqh5`. To update this site, run `npm run build:phone` in `riseup-clone/frontend` there and copy the `docs/` output here.
