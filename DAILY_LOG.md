### Date: Monday, August 3, 2026
- **Today's Goal:** Load a time-series CSV file into Google Colab and plot a hydrograph.
- **What I Actually Completed:** Successfully imported Pandas and plotted a 500-row rainfall dataset.
- **Where I Got Stuck / Bug I Hit:** `KeyError: 'Date'` because the CSV column had a trailing space. Fixed by using `.strip()`.
- **Tomorrow's Exact Task:** Normalize the streamflow column so all numbers are between 0 and 1.
