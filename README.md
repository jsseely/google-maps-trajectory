# google-maps-trajectory
Your Google Maps Timeline data visualized as a trajectory.

![image](https://github.com/jsseely/google-maps-trajectory/assets/7425776/720d855c-f19f-4bd1-be57-236c63cf6c76)

Google Maps offers a Timeline tool to visualize your location history. But the visualization is limited. Instead we can download the location history data and plot it ourselves.

# Use cases
- Visualize your trajectory from a memorable vacation or road trip.
- Document all the streets you've walked in your city.
- Etc.

# Notebook Instructions
1. Download your Google Maps timeline data
    - Go to [maps.google.com](https://maps.google.com/)
    - Navigate to `Your data in Maps`
    - Download `Location History`
2. In the notebook, replace `file_name` with the filepath to `records.json` file.
3. In the notebook, replace `state_date`, `end_date`, `center`.
4. Run the notebook and open your `maps.html` file in a browser.
