# Internship_IIML
Volatility based short strangle trading strategy
This project is about volatility based short strangle trading startegies. The volatility is modelled using different methodologies(Average True Range(ATR), IV of ATM options, IVIX, and few other models) and compared to the standard IVIX model.
The trades are executed on the first day of the monthly contract and held till the expiry to determine whether the options expire in the money or out of the money.
The python codes roughly summarize all the data pulled from NSEpy library and from January 2017 till June 2021. The R code is used for calculating ATM vol of options based on Black Scholes Merton model.
The Excel sheets are where the actual summary of the analysis can be found. The analysis was done on BankNifty & Nifty Option series, although the stocks data was also downloaded but that part of project is left to explore as of now.
