###Currency Convertor
<p>A basic Currency Convertor app to demonstrate the working of API's in JS</p>
<p>It provides the Excahnge rates of currencies of over 150 countries across the globe</p>

<h4>Currency Exchange API used:</h4>
<a href="https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies">https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies</a>

<p>For finding the exchange rate:</p>
<p>json = fetchJSON(`/currencies/{fromCurrency}`) <br>
rate = json[fromCurrency][toCurrency]</p>
