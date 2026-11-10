# Expected Value & Median · Матожидание и медиана · Математикалық үміт және медиана

An interactive study page for **Section 3.5 "Expected Values"** of *Larsen & Marx, An Introduction to Mathematical Statistics and Its Applications (5th ed.)*.

One self-contained `index.html` file, three languages: **Русский / English / Қазақша**.

## What is inside

| Section | Content |
|---|---|
| TL;DR | The whole section in six points |
| Formulas F1–F14 | Definition of E(X), binomial `np`, hypergeometric `nr/(r+w)`, E[g(X)], linearity, median, exponential, uniform, series, gamma integral, tail-sum formula |
| In plain words | A step-by-step algorithm (ASD-STE100 style) and a Feynman-style explanation |
| Book examples | Examples 3.5.1–3.5.14, one line each |
| Problems | All questions 3.5.1–3.5.36: statement → formulas used (links) → solution → answer → why → trap |
| Cheat sheet | "Signal in the problem → formula → problems" |
| Common mistakes | 13 typical student errors with links to problems |
| Live models | Balance point, binomial `np`, blood pooling, capped St. Petersburg, mean vs median |

## Features

- Language switch **RU / EN / KZ** (bottom-right button). The choice is remembered in the browser.
- Decimal separator follows the language (`0,5` in RU/KZ, `0.5` in EN), including inside formulas.
- Formulas rendered with **MathJax 3** (loaded from cdnjs).
- Light and dark theme follow the system setting.
- Works on phones (single column, no horizontal scroll).

## Terminology

| RU | EN | KZ |
|---|---|---|
| математическое ожидание | expected value | математикалық үміт |
| случайная величина | random variable | кездейсоқ шама |
| плотность вероятности | probability density function (pdf) | ықтималдық тығыздығы |
| функция распределения | cumulative distribution function (cdf) | үлестірім функциясы |
| биномиальное распределение | binomial distribution | биномдық үлестірім |
| гипергеометрическое распределение | hypergeometric distribution | гипергеометриялық үлестірім |
| показательное распределение | exponential distribution | көрсеткіштік үлестірім |
| равномерное распределение | uniform distribution | бірқалыпты үлестірім |
| медиана | median | медиана |
| дисперсия | variance | дисперсия |
| ряд сходится / расходится | series converges / diverges | қатар жинақталады / жинақталмайды |
| без возвращения | without replacement | қайтарусыз |
| сочетания | combinations | терулер |
| линейность | linearity | сызықтылық |
| справедливая игра | fair game | әділ ойын |

## Run locally

Open `index.html` in any modern browser. An internet connection is needed for MathJax and Google Fonts.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `expected-value-3-5`.
2. Upload `index.html`, `README.md` and `.nojekyll` to the root of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. After about a minute the site is live at `https://<your-username>.github.io/expected-value-3-5/`.

Or from the command line:

```bash
git init
git add index.html README.md .nojekyll
git commit -m "Add expected value study page"
git branch -M main
git remote add origin https://github.com/<your-username>/expected-value-3-5.git
git push -u origin main
```

## Notes

- Problem statements are short paraphrases. All solutions and explanations are original.
- Problem 3.5.3 uses the distribution from Example 3.3.7 (Table 3.3.4).
- Problem 3.5.15 assumes every birth month is equally likely (p = 1/12).

## Source

Richard J. Larsen, Morris L. Marx. *An Introduction to Mathematical Statistics and Its Applications*, 5th edition, Section 3.5.
