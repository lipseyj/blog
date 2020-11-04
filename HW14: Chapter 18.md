<h3>18.4: Define an interface specification for the Currency Converter and Check credit rating services shown in Figure 18.7.</h3>

<table>
  <tr>
    <th>Operation</th>
    <th>Input</th>
    <th>Output</th>
    <th>Exceptions</th>
  </tr>
    <tr>
    <td>Currency Converter</td>
    <td>amount<br>startCurrency<br>endCurrency</td>
    <td>convAmount<br>converted amount of money</td>
    <td>ConversionFault<br>invalid type<br>invalid amount</td>
  </tr>
    <tr>
    <td>Currency Transaction History</td>
    <td>cthin<br>startCurrency</td>
    <td>cltOut<br>total number of conversions of this starting currency</td>
    <td>TransactionHistoryFault<br>invalid type</td>
  </tr>
</table>
