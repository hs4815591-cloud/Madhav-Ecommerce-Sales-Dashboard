# Madhav Ecommerce Sales Dashboard

A Power BI dashboard project for exploring e-commerce sales, profit, quantity, customers, categories, and state-wise performance.

## Project overview

This project uses the supplied `Orders.csv` and `Details.csv` datasets to build an interactive sales dashboard in Microsoft Power BI.

## Dashboard highlights

- KPI cards for total amount, profit, quantity, and average order value (AOV)
- Sales amount by state
- Quantity distribution by category
- Monthly profit analysis
- Sales amount by customer
- Profit by sub-category
- Quarter and state filters

## Tools used

- Microsoft Power BI Desktop
- CSV datasets
- Data modelling and visualisation

## Files in this repository

| File | Description |
|---|---|
| `Madhav Ecommerce Dashboard.pbix` | Power BI dashboard file |
| `Orders.csv` | Order date, customer, state, city, and order ID data |
| `Details.csv` | Order amount, profit, quantity, category, sub-category, and payment mode data |
| `README.md` | Project documentation |

## How to open the dashboard

1. Install Microsoft Power BI Desktop.
2. Download or clone this repository.
3. Open `Madhav Ecommerce Dashboard.pbix` in Power BI Desktop.
4. If Power BI asks for the CSV locations, point it to `Orders.csv` and `Details.csv` in this project folder, then refresh the data.

## Dataset columns

### `Orders.csv`
- `Order ID`
- `Order Date`
- `CustomerName`
- `State`
- `City`

### `Details.csv`
- `Order ID`
- `Amount`
- `Profit`
- `Quantity`
- `Category`
- `Sub-Category`
- `PaymentMode`

The two datasets share `Order ID`, which can be used to relate the tables in Power BI.

## Notes before publishing

- Confirm that you have permission to redistribute the datasets.
- Remove any personal, confidential, or licensed information before making the repository public.
- Add a dashboard screenshot to this README if you want the repository page to show a visual preview.
