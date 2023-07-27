# Jest-React-Currency-Comparison
Project from CodeCademy

Here’s an explanation of how Currency Comparison works:

The CurrencyComparison class is designed for transforming currency from USD to any specified foreign currency. It incorporates an asynchronous method, fetchCurrentExchange(), to retrieve exchange rates.
The class leverages two additional methods to convert an annual salary into an hourly wage, and subsequently, into the desired foreign currency.
The response() method compiles this data into a comparison object, combining the initial salary, its corresponding hourly wage in USD, and its equivalent hourly wage in the selected foreign currency.
The output of this method is processed through a callback function named useData(), returning an object that allows users to compare currencies.
