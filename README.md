# TradingView Scripts and Indicators

This repository is organized for building and maintaining TradingView Pine Script indicators, strategies, and shared helpers.

## Repository structure

```text
.
├── indicators/   # TradingView indicators written in Pine Script
├── strategies/   # TradingView strategies written in Pine Script
├── libraries/    # Shared Pine Script libraries/helpers
├── scripts/      # Utility scripts for development or publishing workflows
├── templates/    # Starter Pine Script templates
└── docs/         # Usage notes and documentation
```

## First indicator

- [`indicators/date-time-vertical-line.pine`](indicators/date-time-vertical-line.pine) lets you enter a target date and time, then draws a vertical line at that timestamp on the chart.

## How to use Pine Script files

1. Open TradingView.
2. Open **Pine Editor**.
3. Copy the contents of a `.pine` file from this repository.
4. Paste it into Pine Editor.
5. Click **Save** and then **Add to chart**.

## Naming conventions

- Use lowercase file names with hyphens, for example `date-time-vertical-line.pine`.
- Keep one indicator, strategy, or library per file.
- Add a short usage document in `docs/` for each finished script when helpful.
