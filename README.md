# TradingView

This repository is organized as a collection of TradingView Pine Script projects. Each indicator or strategy has its own folder with the Pine Script file and any notes for that specific tool.

## Repository structure

```text
.
├── indicators/
│   ├── README.md
│   └── date-time-vertical-line-indicator/
│       ├── date-time-vertical-line.pine
│       └── README.md
├── strategies/
│   ├── README.md
│   └── strategy-x/
│       ├── strategy-x.pine
│       └── README.md
├── libraries/
├── scripts/
└── templates/
```

## Indicators

- [Date/Time Vertical Line Indicator](indicators/date-time-vertical-line-indicator/) lets you enter a target date and time, then draws a vertical line at that timestamp on the chart.

## Strategies

- [Strategy X](strategies/strategy-x/) is a starter folder for the next strategy.

## How to use Pine Script files

1. Open TradingView.
2. Open **Pine Editor**.
3. Open the folder for the indicator or strategy you want.
4. Copy the contents of its `.pine` file.
5. Paste it into Pine Editor.
6. Click **Save** and then **Add to chart**.

## Project pattern

Each new TradingView tool should use this folder pattern:

```text
indicators/
└── tool-name/
    ├── tool-name.pine
    └── README.md
```

For strategies, use the same pattern under `strategies/`:

```text
strategies/
└── strategy-name/
    ├── strategy-name.pine
    └── README.md
```

## Naming conventions

- Use lowercase folder and file names with hyphens, for example `date-time-vertical-line-indicator`.
- Keep one indicator, strategy, or library per project folder.
- Keep the script README inside the same folder as the Pine Script file.
