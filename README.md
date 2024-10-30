# Flight Booking Data Analysis

## Introduction
This project analyzes a flight booking dataset obtained from the "Ease My Trip" website. The objective is to conduct various statistical hypothesis tests and derive meaningful insights that could be valuable for passengers. The project primarily uses Microsoft Excel for data analysis, including visualizations and statistical testing.

## Dataset
The dataset contains information on flight bookings, including:
- Airlines
- Ticket prices
- Departure and arrival times
- Days before departure when the ticket was booked
- Travel class (Economy/Business)
- Source and destination cities

## Research Questions
The aim of the study is to answer the following research questions:
1. Does the price vary with airlines?
2. How is the price affected when tickets are bought just 1 or 2 days before departure?
3. Does ticket price change based on departure and arrival times?
4. How does the price change with different sources and destinations?
5. How does the ticket price vary between Economy and Business classes?

## Methods
### Data Analysis
- **Pivot Tables**: Used to summarize and aggregate data to answer specific research questions.
- **Charts and Visualizations**: Line charts, column charts, and histograms created to visualize trends and patterns in the data.
- **Slicers**: Added to the dashboard for interactive data filtering.

### Statistical Tests
- **T-Test**: Conducted to compare ticket prices for different timeframes (e.g., 1-2 days before departure vs. other days).
- **ANOVA**: Performed to assess the impact of departure and arrival times on ticket prices.
- **Linear Regression**: Used to predict ticket prices based on various factors, including departure and arrival times.

## Key Findings
1. **Airlines**: Ticket prices vary significantly across different airlines.
2. **Booking Time**: Prices tend to increase significantly when tickets are bought just 1 or 2 days before departure.
3. **Departure and Arrival Times**: The time of departure and arrival has an impact on ticket prices, with notable differences during peak and off-peak hours.
4. **Source and Destination**: Prices fluctuate based on the source and destination cities.
5. **Travel Class**: Business class tickets are priced higher than economy class tickets, as expected.

## Dashboard
An interactive dashboard has been created using Microsoft Excel to showcase the findings. The dashboard includes various charts and slicers for dynamic data analysis.

## How to Use
1. Download the Excel file from this repository.
2. Open the file in Microsoft Excel.
3. Use the slicers to filter data based on your interests.
4. Explore the different charts to gain insights into the flight booking trends.

## Conclusion
This project demonstrates the power of data analysis in uncovering trends and insights from flight booking data. The findings can help passengers make informed decisions and optimize their travel plans.

## Repository Structure

├── data
│   └── flight_booking_dataset.csv
├── analysis
│   ├── pivot_tables.xlsx
│   ├── charts.xlsx
│   ├── statistical_tests.xlsx
│   └── dashboard.xlsx
├── README.md
└── LICENSE

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Thanks to "Ease My Trip" for providing the dataset.
- Special thanks to the contributors and the data analysis community for their valuable insights and tools.


