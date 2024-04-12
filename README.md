# HOTEL BOOKING Analysis

This project focuses on analyzing hotel booking data using Python and Jupyter Notebook. 

The dataset used for this analysis is the Hotel Booking Demand dataset from Kaggle. 

The goal is to explore various aspects related to hotel reservations and provide insights for effective management.

## Project Features
### 1.Handling Null Values:
The dataset contains missing values (NaN) in columns such as ‘country,’ ‘agent,’ and ‘company.’

For ‘country,’ NaN values are replaced with ‘PRT’ (Portugal) based on the most common country associated with a specific lead time.

For ‘agent,’ NaN values are replaced with 0, considering that these bookings were not made through a travel agency.

The ‘company’ feature, with approximately 96% NaN values, is dropped due to its limited usefulness.
### 2.Reservation Status Count:
The project calculates the count of reservations based on the reservation status (canceled or not-canceled).
### 3.Reservation Status by Hotel Type:
The analysis distinguishes between city hotels and resort hotels.

Reservation status (canceled or not-canceled) is examined separately for each hotel type.
### 4.Average Daily Rate (ADR):
The ADR is computed for both city hotels and resort hotels.

ADR provides insights into pricing trends and revenue generation.
### 5.Reservation Status per Month:
The project investigates the reservation status (canceled or not-canceled) across different months.

This helps identify seasonal patterns and potential areas for improvement.
### 6.Average Daily Rate per Month:
ADR is analyzed on a monthly basis to understand pricing variations over time.
### 7.Top 10 Countries with Reservation Cancellations:
The countries with the highest number of reservation cancellations are identified.

This information can guide marketing strategies and customer service efforts.
## Repository Structure
data/: Contains the dataset files.

notebooks/: Jupyter Notebook files for data exploration, cleaning, and analysis.

results/: Output files, visualizations, and summary reports.
## Getting Started
Clone this repository to your local machine.

Install the required Python libraries (e.g., pandas, matplotlib, seaborn).

Explore the Jupyter Notebook files in the notebooks/ directory.

Run the notebooks sequentially to reproduce the analysis.


Feel free to customize and expand upon this project as needed. Happy analyzing! 📊🏨
