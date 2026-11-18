# When does Kalshi overtake the polls? (2026 midterms)

Interactive research page: https://lawrencelu0904.github.io/kalshi_midterm_prediction/

For every 2026 Senate, Governor and House race with a Kalshi market, three forecasts of the chance that the Democrat wins, every day: from the polls alone, from Kalshi's price alone, and from both combined. Each is scored against who actually won.

- **Kalshi vs polls**: from when Kalshi's forecast was at least as close to the result as the polls', across all polled races and the competitive ones.
- **Compare models**: every candidate model for each source, scored the same way.
- **Lead time (λ)**: for each race, how many days before the election polls + prices beat polls alone for good. A map and a race chart run together on a time slider from Jan 1, 2025 to Election Day; also error by day, robustness settings and null tests.

Models use only what was public on each day, and each race's state is left out when fitting. Data: Kalshi public market data (bid/ask midpoints), public head-to-head polls by release date, and certified results. The TimesFM 3 forecasts on the Compare tab use model weights licensed for non-commercial research use.

This repository holds the built, self-contained page (`index.html`); it is generated from the team's analysis code.
