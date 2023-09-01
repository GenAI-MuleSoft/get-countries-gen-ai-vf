# get-countries-gen-ai-vf
Test project for gen-ai

Project Description

Project is developed for retrieving information about countries. It extending existing functionality for https://restcountries.com/v3.1/all endpoint. Endpoint can receive up to 5 query parameters. country_name filtering country names that contains country_name query paramether. population query paramether filtering countries by their population and returns only those records that have less population. sort_type is sorting countries by country name in alphabethical order. Limit and offset query params may be used for pagination purposes.

Application can be runned in Apypoint Studio. No additional configuration needed.

Request examples
http://localhost:8081/api/countries?country_name=ma&population=150&sort_type=descend&limit=2&offset=1
http://localhost:8081/api/countries?population=2&sort_type=descend
http://localhost:8081/api/countries?country_name=m&population=1&sort_type=ascend&limit=20&offset=2
http://localhost:8081/api/countries?country_name=m&population=1&sort_type=ascend&limit=-5&offset=-2
http://localhost:8081/api/countries?country_name=Ukr
http://localhost:8081/api/countries?population=1&sort_type=ascend&limit=5&offset=4
http://localhost:8081/api/countries?population=-5
http://localhost:8081/api/countries?country_name=Al&sort_type=ascend
http://localhost:8081/api/countries?sort_type=ascend
http://localhost:8081/api/countries?sort_type=descend