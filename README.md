# Belly Button Biodiversity Dashboard

This is an interactive data visualization dashboard built using **D3.js** and **Plotly.js**. The dashboard displays information about bacterial species found in human belly buttons, based on data from a JSON file.

## Features

- **Dropdown Menu** to select test subject IDs  
- **Bar Chart** showing the Top 10 OTUs (Operational Taxonomic Units) for each subject  
- **Bubble Chart** displaying all OTU samples for the selected subject  
- **Metadata Panel** displaying demographic information (e.g., age, gender, location)  
- **Responsive Layout** using Bootstrap for clean styling

## Live Demo

🔗 [Belly Button Biodiversity Dashboard](https://dagimg16.github.io/belly-button-challenge/)  

## Technologies Used

- HTML   
- Bootstrap  
- D3.js
- Plotly.js  
- JavaScript (ES6)

## Project Structure
```
   belly-button-challenge/
   |   ├── index.html         # Main HTML structure
   |   ├── static/
   |   │   └── js/
   |   │       └── app.js     # Core JavaScript logic (charts + interactivity)
   |   ├── README.md          # This file
   |   ├── samples.json       # data source sample
```
## 📥 Data Source

All visualizations are built from `samples.json`, which is hosted externally:

[samples.json](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)

## How It Works

1. The page loads and fetches sample data using D3.
2. The dropdown menu is populated with subject IDs.
3. When a new ID is selected:
   - The **bar chart** and **bubble chart** update using Plotly.
   - The **metadata panel** updates with demographic info.

## Getting Started Locally

To run the app locally:

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/belly-button-dashboard.git

2. Open ``index.html`` in your browser

## License
  - Feel free to use and modify this script for your own learning.
