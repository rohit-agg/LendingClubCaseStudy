# Lending Club Case Study
> Company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

## Table of Contents
* [General Information](#general-information)
* [Approach](#approach)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)

## General Information
Like most other lending companies, lending loans to *risky* applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.

#### Objective

The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

#### Dataset

Complete loan data for all loans issued through the time period 2007 to 2011

## Approach

Following is the step-by-step approach followed to solve the given problem statement:
1. Data Understanding
1. Data Cleaning
1. Data Fixing
1. Univariate Analysis
1. Segmented Univariate Analysis
1. Bivariate Analysis
1. Derived Metrics
1. Conclusions

## Conclusions
- Loans should be provided to borrowers with higher annual income
- When providing loans to borrowers with lower annual income, verification of income should be made mandatory
- Is for some reason verification can't be done, loan should not be provided for debt consolidation, small business or credit card. It should not also be provided if the purpose is not clearly specified
- Loans should be provided to borrowers with more than 2 years and less than 10 years of employment length
- For borrower’s with more than 10 years employment, avoid loans for Debt Consolidation
- Short term loans should be avoided in California (CA), Florida (FL), New York (NY), NJ (New Jersey) and Texas (TX)
- Loan should be provided to borrowers owning their own house, for others Low Revolving Credit Utilization should be considered

## Technologies Used
- Python (ver 3.11.7)
- NumPy (ver 1.26.4)
- Pandas (ver 2.1.4)
- MatplotLib (ver 3.8.0)
- Seaborn (ver 0.13.2)

## Acknowledgements
- Session on EDA through Data Visualisation conducted by Shivam Garg on 21st July 2024
- [Seaborn Documentation](https://seaborn.pydata.org/api.html)

## Contact
Created by [@rohit-agg](https://github.com/rohit-agg) and [@]() - feel free to contact us!

## License
This project is open source and available under the [MIT License](LICENSE.md)
