# countries

## Starting

In the project directory, you can run:

```bash
npm start
```

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

After  10 seconds on the back end will be triggered function 'sendCountryByName' witch will fetch data from [https://restcountries.eu](https://restcountries.eu), for the country Malta and send it to the browser on localhost:3000. On the first line in the browser, 'Loading...' will be replaced with 'Country: Malta - Capital: Valletta' (in response is all data).

In the second line is an input text field in which can be added country names (or part of the name) separated with commas. After submit, on the Node js back end (function reqCountriesByNames) text will be split to an array, fetched data and send it to the front end. Then will be displayed names in the same line.

In the third line is a drop-down which fetches all countries names from [https://restcountries.eu](https://restcountries.eu) and after selecting one it will be displayed in the same line.

The fourth line is reserved for a Slot machine. When button 'Spin' is clicked, the App calls the function 'slotMachine' on the back end, which gets fruit names from the next iteration of given Arrays and calculates user coins. Implemented a 'closure' to store the number of coins, which is suitable in this local uses.<br />
Fruits then will be displayed on the left side of the button and coins on the right side.

## Testing

In the project directory, open terminal:

```bash
cd client
```
```bash
npm test
```

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

Currently, CSS and tests are only partially done.
