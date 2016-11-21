# sg-benefits-claimants
Percentage of working age claimants of key benefits by age.

Statistics provided by Scottish Government:  http://statistics.gov.scot/data/working-age-claimants-of-benefits-key

Source: DWP Information Directorate. Data are subject to Crown Copyright and may only be reproduced where the source is fully acknowledged.

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/sg-benefits-claimants.git
```

Install npm dependencies

```
cd sg-benefits-claimants
npm install
```

Run the API (from the sg-benefits-claimants directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
