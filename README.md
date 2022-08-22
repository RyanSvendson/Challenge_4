# Risk Return analysis

This project seeks to analyze the risk and the return of four fund managers for possible inclusion into firm offerings. For risk, the managers were judged against against the S&P 500. 

---

## Technologies

The project was built with Python 3.9

---

## Imports and Dependencies 

Pandas
Numpy
Matplotlib

---

## Usage

The analysis can be used by creating a Path to any other csv file with daily return information. Additional updates needed are anywhere a specific fund managers name is referenced and will need to be replaced with the funds represented in the 'new' csv. 

> Path to update: 
    ```csv_path = Path('../Starter_Code/Resources/whale_navs.csv')```
    
> Plot daily returns: 
![Daily returns chart](daily_return.png)

> 21 Day Rolling Standard Deviation Plot:
![Rolling 21 day std dev plot](21_day_std_dev.png)

> Sharpe Ratio Bar Chart
![Sharpe ratio bar chart](sharpe_ratio_bar_chart.png)

---

## Contributors

Ryan Svendson
rsvensdon@gmail.com
 
---

## License

MIT