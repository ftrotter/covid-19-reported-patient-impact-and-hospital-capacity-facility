## COVID-19 Reported Patient Impact and Hospital Capacity by Facility | HHS

The source code outlining how this product gathers, transforms, revises and publishes its datasets is available at [https://github.com/rearc-data/covid-19-reported-patient-impact-and-hospital-capacity-facility](https://github.com/rearc-data/covid-19-reported-patient-impact-and-hospital-capacity-facility).

### Main Overview
The dataset file included with this product is provided in CSV format. README files are also included to offer context on data fields used throughout the dataset files. The specific files included with each revisions may vary.

This dataset contains temporal data of facility-level hospital utilization aggregated on a weekly basis (Friday to Thursday). These are derived from reports with facility-level granularity across two main sources: (1) HHS TeleTracking, and (2) reporting provided directly to HHS Protect by state/territorial health departments on behalf of their healthcare facilities.

The hospital population includes all hospitals registered with Centers for Medicare & Medicaid Services (CMS) as of June 1, 2020. It includes non-CMS hospitals that have reported since July 15, 2020. It does not include psychiatric, rehabilitation, Indian Health Service (IHS) facilities, U.S. Department of Veterans Affairs (VA) facilities, Defense Health Agency (DHA) facilities, and religious non-medical facilities.

For a given entry, the term “collection_week” signifies the start of the period that is aggregated. 

Reported elements include an append of either “_coverage”, “_sum”, or “_avg”.

A “_coverage” append denotes how many times the facility reported that element during that collection week.
A “_sum” append denotes the sum of the reports provided for that facility for that element during that collection week.
A “_avg” append is the average of the reports provided for that facility for that element during that collection week.

The file will be updated weekly. No statistical analysis is applied to impute non-response. For averages, calculations are based on the number of values collected for a given hospital in that collection week. Suppression is applied to the file for sums and averages less than four (4). In these cases, the field will be replaced with “-999,999”.

This data is preliminary and subject to change as more data become available. For the most up to date information about the dataset please refer to the [dataset webpage](https://healthdata.gov/dataset/covid-19-reported-patient-impact-and-hospital-capacity-facility).

### Data Source
This dataset is provided by the [The United States Department of Health and Human Services (HHS)](https://healthdata.gov/agencies/department-health-human-services).

### More Information
- Source: [COVID-19 Reported Patient Impact and Hospital Capacity by Facility](https://healthdata.gov/dataset/covid-19-reported-patient-impact-and-hospital-capacity-facility)
- License: [Open Data Commons Attribution License](https://opendatacommons.org/licenses/by/1.0/)
- Frequency: Weekly
- Format: CSV

### Contact Details
- If you find any issues with or have enhancement ideas for this product, open up a GitHub [issue](https://github.com/rearc-data/covid-19-reported-patient-impact-and-hospital-capacity-facility/issues) and we will gladly take a look at it. Better yet, submit a pull request. Any contributions you make are greatly appreciated :heart:.
- If you are looking for specific open datasets currently not available on ADX, please submit a request on our project board [here](https://github.com/orgs/rearc-data/projects/1).
- If you have questions about the source data, please post your quastion in the comment section of the [dataset webpage](https://healthdata.gov/dataset/covid-19-reported-patient-impact-and-hospital-capacity-facility).
- If you have any other questions or feedback, send us an email at data@rearc.io.

### About Rearc
Rearc is a cloud, software and services company. We believe that empowering engineers drives innovation. Cloud-native architectures, modern software and data practices, and the ability to safely experiment can enable engineers to realize their full potential. We have partnered with several enterprises and startups to help them achieve agility. Our approach is simple — empower engineers with the best tools possible to make an impact within their industry.
