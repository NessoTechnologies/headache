# Headache Data

## Introduction

This file ([`data/HeadacheDataCompilation.zip`](data/HeadacheDataCompilation.zip)) contains a compilation of headache data from multiple sources.  Each row in the dataset contains a "Source" column that shows you where it came from.  Please see [`SOURCES.md`](SOURCES.md) for the full list.

These files are maintained by [Nesso Technologies, Inc.](https://nesso.io).  If you have any questions or issues with these files, please [create a GitHub issue](https://github.com/NessoTechnologies/headache/issues).  We'd love to hear from you!


## File Format

The dataset is formatted as follows.  Please note that specific datasets may place special meaning on certain fields, and the values may deviate from what is described here.  Please see the [`SOURCES.md`](SOURCES.md) file for those source-specific details:

Field | Datatype | Description
----- | -------- | -----------
Year | integer | The survey year.
HeadacheType | nvarchar(200) |
Country | nvarchar(200) | The country where the study was conducted.
StateProvince | nvarchar(200) | The state/province where the study was conducted, if applicable.  This will be "N/A" if it does not apply.
AgeRangeLower | integer | The lower end of the range that describes the age of the study respondent.
AgeRangeUpper | integer | The upper end of the range that describes the age of the study respondent.
Ethnicity | nvarchar(200) | Please see the "Reference Values Mapping.xlsx" spreadsheet included in [`data/HeadacheDataCompilation.zip`](data/HeadacheDataCompilation.zip) for the possible values for this field.
Gender | nvarchar(200) | Please see the "Reference Values Mapping.xlsx" spreadsheet included in [`data/HeadacheDataCompilation.zip`](data/HeadacheDataCompilation.zip) for the possible values for this field.
Race | nvarchar(200) | Please see the "Reference Values Mapping.xlsx" spreadsheet included in [`data/HeadacheDataCompilation.zip`](data/HeadacheDataCompilation.zip) for the possible values for this field.
ParticipantResponse | nvarchar(200) | Please see the "Reference Values Mapping.xlsx" spreadsheet included in [`data/HeadacheDataCompilation.zip`](data/HeadacheDataCompilation.zip) for the possible values for this field.
AffectedCount | integer | The number of people that fall into this bucket (data is grouped by Year, AgeRangeLower, AgeRangeUpper, Ethnicity, Gender, Race, and Source).
AffectedMarginOfError | decimal | The margin of error for the Affected value.  Not used at this time.
SoughtHelpCount | integer | The number of Affected people that also sought help for their condition.
Source | nvarchar(4000) | The source for this data row.

Changes to the file contents and/or format (especially breaking changes) are documented in [`Releases`](../../releases).
