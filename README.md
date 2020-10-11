# 🍲 Foodish 🍛
![Logo](https://github.com/surhud004/Foodish/blob/master/public/logo.ico "Samosa")

A Node.js/Express.js REST API to GET a random picture of food dishes.

![](https://img.shields.io/badge/contributions-welcome-34cdfa)

## Demo
Visit https://foodish-api.herokuapp.com/

## API Documentation
Base URL for all endpoints https://foodish-api.herokuapp.com/

_The response time will likely be a few seconds long on the first request, because this app is running on a free Heroku dyno. Subsequent requests will behave as normal._

## Endpoints
Routes | Description
------------ | -------------
`GET /api/` | Random food dish from random category.

Example Request-

`GET /api/`

Example Response-
```
{"image":"https://foodish-api.herokuapp.com/images/burger/burger101.jpg"}
```
----------------------------
Routes | Description
------------ | -------------
`GET /api/images/:food` | Random picture from `food` category.

Example Request-

`GET /api/images/biryani`

Example Response-
```
{"image":"https://foodish-api.herokuapp.com/images/biryani/biryani32.jpg"}
```
----------------------------
## Authors
* [Surhud Bhagali](https://github.com/surhud004)
* Special thanks to [Rajaraman Ekambaram](https://github.com/Rtech2014) for providing the initial Foodish image database via [Kaggle](https://www.kaggle.com/datasets).

## Support
Please [create a new issue](https://github.com/surhud004/Foodish/issues/new) for support and issues.

## Contributing
Please read the [CONTRIBUTING](https://github.com/surhud004/Foodish/blob/master/CONTRIBUTING.md) for details on adding images to the Foodish Database.

## License
This project is licensed under [MIT](https://opensource.org/licenses/MIT). Please read the [LICENSE](https://github.com/surhud004/Foodish/blob/master/LICENSE) for details.

----------------------------
###### [Foodish API](https://github.com/surhud004/Foodish) is maintained by [surhud004](https://github.com/surhud004).
