# covid-19-malaysia
Malaysia COVID-19 dataset by country, states, districts and confirmed cases types, updated frequently.

## Contributing
You can help by completing some of the dataset left or checking the values/names so that they are correct (especially for districts cases). You can search for the data in the sources below or with other methods.

Fork the project, make the modification and submit a pull request. You **must include a source** in your pull request to verify its credibility. If you don't know how to make modification, feel free to create a new issue.

The currently maintained data are [covid-19-malaysia.csv](covid-19-malaysia.csv) and [covid-19-my-states-cases.csv](covid-19-my-states-cases.csv).

## Source
Currently MOH does not provide a platform that provides full comprehensive dataset on the COVID-19 cases in Malaysia.

Data are retrieved mainly from [Desk of DG](https://kpkesihatan.com/). While other data or data in the early stage are retrieved form multiple sources including:
* [MOH Facebook Page](https://www.facebook.com/kementeriankesihatanmalaysia/)
* [CPRC KKM Telegram Channel](https://t.me/cprckkm)
* [KKM Portal MyHealth Twitter](https://twitter.com/MyHEALTHKKM)
* [Twitter of DG](https://twitter.com/DGHisham)
* [Info Sihat](https://www.infosihat.gov.my/index.php/wabak-novel-coronavirus-atau-2019ncov)

Full accuracy of the data cannot be guaranteed.

## Notes
Please read the notes before using the data or contributing to the data!
* I do not include new cases / deaths in the dataset because it can be calculated easily and to include only essential information in it.
* The 'icu' column represents the current number of patients under the intensive care unit **at that date**.
* Blank spaces means that the values are not available while dashes means not applicable (roughly).

### States case
* The data on 14/3/2020 that provide the increase in cases by states are not consistent with the data given the day before. Ex: MOH provided 105 cases but only 92 cases in the next day. As such, numbers of cases on 13/3/2020 is calculated from the data the day before.
* On 16-18/3/2020, data of WP Kuala Lumpur is combined with WP Putrajaya.

### Other
* The 'pending' column represents the current number of pending cases **at that date**.
* On 10/4/2020 - now, data of PUI cases and close contact cases are combined together.

## TODO
* Daily negative cases from [MOH](http://www.moh.gov.my/index.php/pages/view/2019-ncov-wuhan)
### Misc
* Update states' districts cases
* Deaths cases - type of chronic diseases of patients
* Daily MCO violation
* Cases by states' cities

## License
This covid-19-malaysia data is made available under the Public Domain Dedication and License v1.0 whose full text can be found at: http://www.opendatacommons.org/licenses/pddl/1.0/
If you use this data, it would be helpful to credit this repo in your projects so others can find it easily!
