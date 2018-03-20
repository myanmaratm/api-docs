# Myanmar ATM Api

Myanmar atm api to fetch the atm location from the major cities of Myanmar.
The API is [REST API](http://en.wikipedia.org/wiki/Representational_State_Transfer "RESTful") and currently, return format for all endpoints is [JSON](http://json.org/ "JSON").


## Variable cheat sheet
| Variable | DataType |Format|
|--|--|--|
| `bank_code` | `CHAR(3)` |`AYA`,`CB`,`AGD`,`UAB`,`KBZ`|
| `latidude` | `float` |`16.775816`|
| `longitude` | `float` |`2.775816`|
| `distance_radius` | `INT` |`1`|


# Endpoint List

    https://atm.winhtaikaung.com
**Getting nearest ATM locations by radius**
 -   **[`GET`  /api/v1/atm/`:bank_code`/?lat=`:latitude`&lon=`:longitude`&distance=`:distance_radius`&limit=100&page=1](https://atm.winhtaikaung.com/api/v1/atm/`:bank_code`/?lat=`:latitude`&lon=`:longitude`&distance=`:distance_radius`&limit=100&page=1)**

 
## FAQ

### What do I need to know before I start using the API?

Got any language on your skills? No worries. Here are the docs you might need to get started:

-   HTTPS protocol
-   [REST software pattern](http://en.wikipedia.org/wiki/Representational_State_Transfer)
-   Data serialization with  [JSON](http://json.org/)  (or see a  [quick tutorial](http://www.webmonkey.com/2010/02/get_started_with_json/))


### What return formats do you support?

Myanmar ATM API currently returns data in  [JSON](http://json.org/ "JSON")  format.

### What kind of authentication is required?

Nope

