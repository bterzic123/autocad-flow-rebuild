# Growth Audit — AutoCAD

**Live:** https://bterzic123.github.io/autocad-flow-rebuild/

Five ideas to unlock more revenue from the traffic the AutoCAD mobile app already has, plus a clickable prototype of its onboarding and paywall rebuilt in AutoCAD's own design. Only the order of screens changed. Prepared by Adapty, October 2026.

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Make closing the paywall a second chance, not a sign-out | Offer on close | ARPU +10–15% |
| 02 | Let people in before you ask for an account | Welcome → Account | CR +8% · ARPU +17% |
| 03 | Name their work on the paywall and show both plans up top | Paywall | CR +15–20% |
| 04 | Ask three questions, then show the setup they unlock | Your work → Payoff | CR +10–15% |
| 05 | Put your 4.4 and the trial dates beside the button | Paywall | CR +10–15% |

The prototype opens in English, German and Japanese, in dark (AutoCAD's own) and light mode, and has a 30-second self-playing walkthrough. Add `?open=proto` to the link to land straight on the prototype.

**Grounding.** Every price, rating and feature line comes from Autodesk's own published material: the AutoCAD App Store listing (4.4 from 6.3K ratings, 30-day trial, view-only after the trial, the feature list and storage services), the AutoCAD Web product page, and the in-app paywall (EUR 11.68 monthly, EUR 116.79 yearly). Screen text in German and Japanese is our translation; store prices stay as published.

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for AutoCAD.*

## Run locally

```bash
python3 -m http.server 8921
```

Then open http://localhost:8921/.
