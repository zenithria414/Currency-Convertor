<h2>Currency Convertor</h2>
<br>
<p>A basic Currency Convertor app to demonstrate the working of API's in JS.</p>
<p>It provides the Exchange rates of currencies of over 150 countries across the globe.</p>
<hr>
<h4>Currency Exchange API used:</h4>
<a href="https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies">https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies</a>
<br>
<p><b>For finding the exchange rate:</b></p>
<p>json = fetchJSON(`/currencies/{fromCurrency}`) <br>
rate = json[fromCurrency][toCurrency]</p>
