# Belly Button Biodiversity Dashboard

## Introduction
Welcome to the Belly Button Biodiversity Dashboard, a project developed by Hanns Peter Princivil as part of the UTOR-VIRT-DATA-PT-08-2023-U-LOLC-MTTH(B) Bootcamp. This project is a submission for the Module 14 Challenge, focusing on building an interactive web application to visualize and analyze the Belly Button Biodiversity dataset.

## Overview
The Belly Button Biodiversity Dashboard is an interactive tool that allows users to explore the biodiversity of microorganisms in human navels. It showcases the diversity of microbial species (operational taxonomic units, or OTUs) found in human belly buttons. Users can select different test subjects to view the top 10 OTUs, represented through dynamic bar and bubble charts.

## File Structure
The project consists of the following files and directories:

- `index.html`: The main HTML file that provides the structure of the dashboard.
- `static/js/main.js`: Contains the JavaScript code that powers the interactive elements of the dashboard. This includes data fetching, processing, and visualization.
- `static/css/`: (If applicable) This directory contains custom CSS files for styling the dashboard.
- `samples.json`: The dataset used in this project. It includes information about OTUs found in different individuals.

## Functionality
The dashboard offers several interactive features:

- **Dropdown Menu**: Users can select different test subjects to view their microbial data.
- **Bar Chart**: Displays the top 10 OTUs found in the selected individual.
- **Bubble Chart**: Represents each sample with OTU IDs for the x-values and sample values for the y-values.
- **Metadata Display**: Shows demographic information of the selected individual.
- **Gauge Chart**: (Optional Advanced Feature) Illustrates the weekly washing frequency of the individual.

## Development Process
The development involved several key steps:

1. **Data Reading with D3**: Utilized D3.js to read in `samples.json` for data processing and visualization.
2. **Interactive Visualizations**: Implemented bar and bubble charts using Plotly.js, dynamically updating based on the selected sample ID.
3. **Dashboard Design**: Employed Bootstrap for responsive design, ensuring a clean and accessible user interface.
4. **JavaScript for Interactivity**: The `main.js` file contains the logic for event handling, data processing, and rendering the visualizations.
5. **Testing and Debugging**: Rigorous testing was conducted to ensure accuracy and responsiveness of the dashboard across different browsers and devices.

## Conclusion
This project highlights the use of modern web technologies like D3.js and Plotly.js to create interactive data visualizations. It serves as an excellent example of how data can be made more accessible and engaging to a wider audience.

---

Developed by Hanns Peter Princivil as part of the UTOR-VIRT-DATA-PT-08-2023-U-LOLC-MTTH(B) Bootcamp, Module 14 Challenge.