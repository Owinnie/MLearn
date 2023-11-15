# Nairobi AirQuality data

## References
OpenAfrica. (2023). Nairobi Archives. https://openafrica.net/dataset/44359020-b2b0-4b66-af09-3de18d6519dc/resource/86b95085-9da6-40b6-980b-d3e0448da9ec/download/tmp_t64nkoo.csv

### tr ';' '\t' < data/NairobiAirQuality.csv | mongoimport --host "localhost" --db airquality --collection Nairobi --type tsv --headerline
