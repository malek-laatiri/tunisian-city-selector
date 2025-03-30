# Tunisian City Selector

This project provides a simple web interface to select Tunisian cities and display corresponding governorates dynamically using jQuery and AJAX.

## Features
- Fetches city-governorate data from a JSON file (`governorates.json`).
- Updates the second dropdown dynamically based on the selected city. 

## Data Source
The data was scraped from Wikipedia and compiled into a structured dataset, which is available on Kaggle:
[Tunisia Population by City](https://www.kaggle.com/datasets/maleklaatiri/tunisia-population-by-city).

## Technologies Used
- HTML
- CSS
- JavaScript (jQuery)

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/malek-laatiri/tunisian-city-selector
   ```
2. Open `index.html` in a browser.
3. Select a Tunisian city from the dropdown.
4. The corresponding governorate options will be populated dynamically.

## File Structure
```
├── index.html  # Main HTML file
├── governorates.json  # JSON file containing city-governorate data
├── README.md  # Project documentation
```

## Notes
- Ensure `governorates.json` is correctly formatted and placed in the same directory.
- jQuery is loaded via CDN, so an internet connection is required.

## License
This project is licensed under the MIT License.

---
**Author:** Malek LAATIRI Vinci  
**Contact:** [maleklaatiri.tn](https://maleklaatiri.tn/)

