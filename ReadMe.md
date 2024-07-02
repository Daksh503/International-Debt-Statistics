# International Debt Statistics - PPG Bilateral Debt

## Objective

If you have been following the news recently, you may have come across various headlines like "South Asia in Chinese Debt Trap", "Economic crisis in Sri Lanka", "Failing economy of Pakistan", etc. These news articles made me curious to look into bilateral lendings between two countries. Using Python, I developed a script to download PPG Bilateral Debt data between two countries using the World Bank API.

My project collects data of PPG bilateral lending between India and its neighboring countries, which include Bangladesh, Bhutan, Sri Lanka, Nepal, Maldives, and Myanmar. I have wrangled and analyzed data from the last 20 years of each country individually and visualized the data in the form of an Excel dashboard for easy understanding of the lending trend. Check out the [project report](https://github.com/Daksh503/International-Debt-Statistics/blob/main/Project%20Report.pdf).

## About the Dataset

The dataset includes details of PPG Bilateral debt data between India and Bangladesh/Bhutan/Sri Lanka/Maldives/Myanmar/Nepal obtained using the World Bank API. Each dataset contains four columns:
- `Year`: Year of debt
- `Debtor`: Debtor country code
- `Debt in US$`: Amount of debt in US$
- `YoY Growth %`: Year on year growth percentage of bilateral debt

All six datasets are combined, cleaned, wrangled, and analyzed [here](https://github.com/Daksh503/International-Debt-Statistics/blob/main/Bilateral%20Debt%20Analysis.xlsx). The data is gathered from the World Bank website and considered as primary data.

## Guidelines to Use the Script

1. Check the code of the Debtor Country by using this [script](https://github.com/Daksh503/International-Debt-Statistics/blob/main/Python%20Scripts/Debtor%20Country%20Code%20Script.py) or directly download the Excel file containing 'Debtor Country Code' [here](https://github.com/Daksh503/International-Debt-Statistics/raw/main/Country%20Code%20Data/Debtor%20Country%20Code.xlsx).
2. Check the code of the Creditor Country by using this [script](https://github.com/Daksh503/International-Debt-Statistics/blob/main/Python%20Scripts/Creditor%20Country%20Code%20Script.py) or directly download the Excel file containing 'Creditor Country Code' [here](https://github.com/Daksh503/International-Debt-Statistics/raw/main/Country%20Code%20Data/Creditor%20Country%20Code.xlsx).
3. Use the [PPG Bilateral Debt Script](https://github.com/Daksh503/International-Debt-Statistics/blob/main/Python%20Scripts/PPG%20Bilateral%20Debt%20Script.ipynb) to save the required data in an Excel file.

## Project Structure

- **Bilateral Debt Analysis Presentation.pptx**: A PowerPoint presentation summarizing the analysis.
- **Bilateral Debt Analysis.xlsx**: An Excel file containing the combined and analyzed data.
- **Bilateral Debt Data**: Directory containing raw bilateral debt data.
- **Country Code Data**: Directory containing country code data for debtor and creditor countries.
- **Project Report.pdf**: Detailed project report.
- **Python Scripts**: Directory containing the Python scripts used for data extraction and analysis.

## Conclusion of the Project

1. Total PPG Bilateral Lending has increased from less than 500 million USD in 2000 to about 45 billion USD in 2020.
2. Bhutan has been the biggest debtor country, receiving almost 18 billion USD over the period of 20 years.
3. Nepal has received the least bilateral lending, amounting to less than 1 billion USD.
4. Total bilateral lending shows a positive growth rate over the last 20 years.
5. Total bilateral lending to neighboring countries is approximately 1.2% of the overall GDP of India.
6. In the event of default by any neighboring country in the future, its impact on India’s financial sector will be minimal (considering only the above data).

## How to Contribute

Contributions are welcome! Please fork this repository and submit a pull request with your changes. Ensure that your contributions align with the project's objectives and guidelines.

## Acknowledgments

- The World Bank for providing the data used in this project.
- Contributors and supporters of this project.