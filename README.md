# LTA Train Station Passenger Volume Analysis

A simple Streamlit app for exploring **Singapore LTA train station passenger volume data** from the DataMall API.

The app fetches recent train passenger volume datasets, lets users filter by station, day type, and hour window, and visualizes **monthly average tap-in volume per day** for selected MRT stations.

## Features

- Fetches **LTA DataMall PV/Train** data for the most recent completed months
- Supports a selectable **date range**
- Filters to the **last 3 completed months** supported by the API logic
- Lets users compare selected stations:
  - Tanjong Pagar
  - Raffles Place
  - City Hall
  - Woodlands
- Lets users filter by:
  - **day type** (`WEEKDAY`, `WEEKENDS/HOLIDAY`)
  - **hour window** (for example, 7–9am)
- Displays:
  - a data table of monthly aggregated results
  - a line chart of average tap-in volume trends by station
