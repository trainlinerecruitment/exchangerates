If you are here it's probably because you applied for a Software Engineering role at Trainline. To complete the technical exercise you may need to fetch the foreign exchange rates from a public API and this is where this repository comes handy.

## Endpoints

You can find the exchange rates starting from a base currency in JSON format. The URL must indicate the three-letter ISO currency code:
`/exchangerates/api/latest/{CURRENCY-CODE}.json`

For example, the following request will return the exchange rates for the base currency GBP:
```
GET /exchangerates/api/latest/GBP.json HTTP/1.1
Host: trainlinerecruitment.github.io
Accept: application/json
```

## Supported currencies

|Code|Currency|
|---|---------|
|EUR|Euro|
|GBP|Pound sterling|
|USD|United States dollar|
