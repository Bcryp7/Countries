### Countries of the World - JSON Format

#### A list of all countries with their information.

##### info:

- Country Code
- Native Name
- Phone Code
- Continent
- Capital
- Currency
- Languages

##### Format:

```
"data": {

    "Andorra": {
        "code": "AD",
        "native": "Andorra",
        "phone": "376",
        "continent": "EU",
        "capital": "Andorra la Vella",
        "currency": "EUR",
        "languages": [
          "ca"
        ]
      }
}
```

#### Contributions

Feel free to send a PR suggesting changes, updates, corrections or anything necessary to improve this repo and thank you.

#### Credits to [Annexare Repository!](https://github.com/annexare/Countries)

The only difference is that the ```key: value``` of annexare repository is ``` "AD": {data} ```, using the Country code as key, which didn't work for the use case I'm working on.
