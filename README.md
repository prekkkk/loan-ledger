# Loan Ledger

A free, no-signup EMI and loan-affordability calculator. Enter a loan amount,
interest rate, and tenure, and instantly see:

- Monthly EMI
- Total interest vs. total payment (donut chart)
- A full year-by-year payoff ledger (stacked bar chart + table)

**Live:** [Vercel](https://loan-ledger-jade.vercel.app/)
**Repo:** [GitHub](https://github.com/prekkkk/loan-ledger)

Built with plain HTML, CSS, and JavaScript, plus [Chart.js](https://www.chartjs.org/)
loaded from a CDN — no build step, no framework, no backend, no data ever
leaves the browser.

## Why I built this

I built this because I had to compare EMI options for a car/home/education loan myself and most calculators
online are cluttered with ads or push you toward a specific bank. I wanted a
clean version that also showed the full year-by-year breakdown, not just the
monthly number.

## Run locally

No install needed — it's a single static file.

```bash
# from this folder
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just double-click `index.html` to open it directly in a browser.

## Deploy (free, Vercel)

1. Push this folder to a new public GitHub repo.
2. Go to https://vercel.com → **Add New... → Project** → import the repo.
3. Framework preset: **Other** (it's a static site — no build command, no
   output directory needed).
4. Click **Deploy**. Vercel's free Hobby plan is enough.

## License

MIT — free to reuse.
