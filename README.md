# Garden Soil Planner

A free web app that reads your soil test and tells you what your soil is missing, what to buy, and how much to spread. Targets follow Michael Astera's *The Ideal Soil* (base-saturation approach).

**Use it:** https://slightlybrandon-web.github.io/garden-soil-planner/

## How to use it
1. **Soil tests → Submit a test:** upload a PDF or photo of your lab report, type the values in, or import a file. Check the numbers before saving.
2. **Needs:** see which minerals are short, per garden and bed.
3. **Mix:** pick the products you have and get suggested mix options.
4. **Plan:** print or copy the shopping list and recipe.

## Your data
- Without an account, data stays in your browser only.
- With a free account, it is saved to your account so you can pick up on any device. You can export a backup or delete your account any time. See the in-app Privacy policy.

## Notes
- Guidance only, not professional agronomic advice. Check amounts against your lab report and local rules.
- Not modelled yet: nitrogen and chlorine.

## Maintainers
Single-file static site (`index.html`) on GitHub Pages. Accounts use a Supabase project (email sign-in, one row per user with row-level security, and a `delete_my_account()` function). In Supabase, turn off "Confirm email" and set the Site URL to the Pages address above.

## Credit
Based on the ideas in *The Ideal Soil* by Michael Astera. Not affiliated with or endorsed by the author.
