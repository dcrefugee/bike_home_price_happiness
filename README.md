# Project Narrative: Analyzing Bikeability, Median Home Prices, and Happiness Scores

## 1. Introduction to the Project

### Concept and Motivation
- This project was inspired by my interest in urban planning and quality of life metrics. I aimed to explore how factors like bikeability and home prices might correlate with happiness scores across various U.S. cities.
- The goal was to create an interactive webpage that visually presents these relationships, making the data accessible and engaging for analysis.

## 2. Initial Setup and Planning

### Choosing the Tools
- I selected **HTML5** and **CSS3** for structuring and styling the webpage due to their versatility and widespread use.
- For data visualization, I chose **Chart.js** because of its simplicity and robust capabilities for creating interactive charts.
- To ensure a polished and modern look, I decided to use **Google Fonts** for custom typography, opting for the Montserrat font family.

### Data Collection
- The bikeability scores were sourced from the Redfin Blog's article titled "The 10 Most Bikeable Cities in the U.S." (2024) .
- Median home prices for each city were obtained from the same Redfin Blog article .
- Happiness scores were gathered from WalletHub's "Happiest Cities in America 2024" report .
- I ensured the data was up-to-date and relevant for a meaningful analysis.

## 3. Building the Webpage

### Structuring with HTML
- I began by creating a clean and semantic HTML structure. The main content is centered within a `<div>` element to focus the user’s attention.
- Meta tags were included to set the viewport for responsive design and to define the webpage’s title.

### Styling with CSS
- I emphasized a modern, minimalist design, choosing a light grey background to create a soft contrast with the main content area.
- The content is displayed on a white card with subtle shadows, enhancing readability and visual appeal.
- The table presenting the data was styled using consistent shades of grey to create a clear visual hierarchy, making it easy to differentiate between headers and data.

## 4. Creating the Interactive Visualizations

### Chart.js Integration
- I implemented two scatter plots using Chart.js to explore the relationships between:
  - **Bikeability vs. Median Sales Price**
  - **Bikeability vs. Happiness Score**
- The charts are fully interactive, with tooltips that provide additional context when hovering over a data point, making the data more engaging and informative.

### Customization of Charts
- I customized the axes and tooltips to ensure the data is clearly presented and easy to interpret. For example, I formatted the y-axis on the price chart to display dollar values with commas for readability.
- The color scheme was carefully chosen to differentiate between the two charts while maintaining a cohesive visual theme across the page.

## 5. Finalizing and Enhancing the Presentation

### Responsive Design
- To ensure accessibility across different devices, I focused on responsive design principles. The layout adapts well to various screen sizes, providing a consistent user experience on both desktops and mobile devices.

### Adding Citations
- To maintain transparency and give credit to the original data sources, I included citations at the bottom of the page. This approach not only reinforces the reliability of the analysis but also adheres to ethical standards in data usage.

## 6. Reflection and Next Steps

### Challenges and Learning
- One of the key challenges was ensuring the visualizations were both informative and aesthetically pleasing. Balancing these aspects required fine-tuning the CSS and Chart.js settings, which was a valuable learning experience in frontend development.

### Potential Enhancements
- In the future, I plan to expand the dataset to include more cities or additional metrics such as public transit availability or environmental quality scores. This would provide deeper insights into how various urban factors influence quality of life.

## 7. Conclusion

### Summary
- This project effectively combines data analysis with web development, resulting in a visually engaging and informative presentation of how bikeability, home prices, and happiness scores intersect in urban environments.
- It serves as a solid example of how data-driven narratives can be made accessible to a broad audience through interactive, web-based tools.

## 8. Sources

1. **Bikeability Scores and Median Home Prices**: Redfin Blog, ["The 10 Most Bikeable Cities in the U.S."](https://www.redfin.com/blog/most-bikeable-cities-2024) (2024).
2. **Happiness Scores**: WalletHub, ["Happiest Cities in America 2024"](https://wallethub.com/edu/happiest-places-to-live/32619) (2024).
