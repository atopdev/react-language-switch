react-locale-hot-switch
=======================

This small React web app let the user change the UI language without reloading the page. 

The localized strings are loaded only when the user switches the language

* Implements [react-intl](https://github.com/yahoo/react-intl)
* Loads the required [intl](https://www.npmjs.com/package/intl) polyfills on Safari and IE < 10
* Uses [webpack](http://webpack.github.io) for splitting the localized data in chunks

```bash
npm install

# Run the app
npm start
```

Then visit [http://localhost:8080/](http://localhost:8080/)
