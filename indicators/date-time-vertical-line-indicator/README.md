# Date/Time Vertical Line Indicator

`date-time-vertical-line.pine` is a TradingView Pine Script indicator that draws one vertical line at a user-selected date and time.

## Files

- `date-time-vertical-line.pine` - indicator source code

## Features

- Select the target date and time with TradingView's interactive time input.
- Draw a vertical line that extends through the full chart pane.
- Optionally snap the marker to the bar containing the selected timestamp.
- Customize line color, width, style, and extension behavior.
- Show a configurable timestamp label.
- Show an on-chart info panel with the selected time, marker mode, and bar distance.
- Create an alert when the selected time is reached.

## Installation

1. Open TradingView and go to **Pine Editor**.
2. Copy the contents of `date-time-vertical-line.pine`.
3. Paste the code into Pine Editor.
4. Click **Save**.
5. Click **Add to chart**.

## Usage

1. Add the indicator to your chart.
2. When TradingView asks for the input point, click the chart time you want to mark.
3. To move the marker later, select the indicator and move the built-in time marker, or use **Reset points** from the indicator menu and click a new chart point.
4. Adjust the visual options from the indicator settings if needed.

TradingView interprets the selected timestamp using the chart/exchange timezone displayed in the platform.

## Note about on-chart editing

Pine Script does not allow scripts to create custom editable text boxes directly on the chart. This indicator uses TradingView's built-in interactive time input instead, which is the closest supported workflow for changing the marker without editing the source code.
