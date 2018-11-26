# v1 API data model
     
## user's properties

| property  | data type  | required       | example       |
| ---       | ---        | -------------  | ------------  |
| user id   | int        |   auto gen     | `0123456789`  |
| name      | string     |   yes          | `Marco Polo`  |
| email      | string     |   yes          | `marcopolo@protonmail.com`  |
| number      | string     |   optional          | `800-232-0488`  |
| username      | string     |   optional          | `@marco.polo`  |
| age       | int        |   yes          | `25`          |
| location  | string     |   yes          | `Chicago`     |
| sex       | enum       |   yes          | `Male or Female or Other`  |
| seeking   | enum       |   optional     | `Male or Female or Other`  |
| eth address | string   |   auto gen     | `0xBbf6cEAc1827A6B03D2385097494F0CeF859615f`  |
| pub key | string   |   auto gen     | `0xabc12498skfh....`  |
| priv key | string   |   auto gen     | `a8919f63625ec4ef62557b1faed1fef6d676d254a69e28fa1f041d946eec8cd6`  |
| qr code | string   |   auto gen     | `qr image or qr string`  |
| usd balance | double   |   auto gen     | `USDT/DAI: 10.00`  |
| eth balance | double   |   auto gen     | `ËTH: 2.68`  |
| mojo balance | double   |   auto gen     | `MOJO: 1,000,000.99`  |



### user model 
```
uudi - int  - 00000001
name - string - frank smith
age - int - 25
location - string - 
sex - int
...
```
