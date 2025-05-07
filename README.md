## App Category Insights - Time-Gated Visualization 

This project visualizes a **grouped bar chart** comparing the **average rating** and **total review count** for the **Top 10 app categories by installs**, using **Jupyter Notebook**.

The chart appears **only between 3 PM and 5 PM IST** and applies specific data filters for relevance and quality.

## Features

- **Grouped Bar Chart** using Plotly/Matplotlib
- Top 10 app categories by number of installs
- Filters applied:
  - Average Rating ≥ 4.0
  - Size ≥ 10 MB
  - Last Update Month = January
- Chart display is limited to time between **3:00 PM and 5:00 PM IST**

## Visualization Logic

- X-axis: App Categories
- Y-axis: 
  - Left bar: Average Rating
  - Right bar: Total Review Count
- Display only within the valid time window using `datetime` and `pytz`

## Use Cases

- App analytics and trend visualization
- Time-controlled dashboards for demos or meetings
- Filtering high-quality app categories for performance analysis
- Educational purposes for teaching data filtering and visualization

## Troubleshooting
-Chart not showing?
Ensure your system time is within the 3–5 PM IST range. You can temporarily override the time check for debugging by commenting the time logic.

-Timezone issues?
This project uses pytz to convert UTC to IST. Make sure pytz is installed.

-Empty chart?
Make sure the dataset has categories that meet all filtering criteria.

##  Requirements
Jupyter

Python

pandas

matplotlib or plotly

pytz
datetime

## License
This project is licensed under the MIT License.

