# Sources

## Data
This dataset combines data from the following sources:

Source | Year | . | Notes about original source file 
------ | ---- | - | --------------------------------
NHIS<sup>1</sup> | 1996 | [Link](https://www.cdc.gov/nchs/nhis/pre1997.htm#1996) |Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 1997 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#1997) |Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 1998 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#1998) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 1999 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#1999) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 2000 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#2000) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 2001 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#2001) | Mostly fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.  Many of the data lines had several blanks missing at the ends of the rows.  A "blank" was a valid response, but it looks like they were trimmed off at some point.  I had to pad those lines out to the proper length before I could import them.
NHIS<sup>1</sup> | 2002 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#2002) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 2003 | [Link](https://www.cdc.gov/nchs/nhis/1997-2018.htm#2003) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.  This year's data was split between the Adult Sample file and the Person file.
NHIS<sup>1</sup> | 2004 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2004_data_release.htm) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 2005 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2005_data_release.htm) | Fixed-length file in a self-extracting ZIP requiring DOS. A note on the NHIS site explains that renaming the .exe to .zip will allow Windows users to extract the contents.
NHIS<sup>1</sup> | 2006 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2006_data_release.htm) | Fixed-length file in a Windows compatible self-extracting ZIP
NHIS<sup>1</sup> | 2007 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2007_data_release.htm) | Fixed-length file in a Windows compatible self-extracting ZIP
NHIS<sup>1</sup> | 2008 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2008_data_release.htm) | Fixed-length file in a Windows compatible self-extracting ZIP
NHIS<sup>1</sup> | 2009 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2009_data_release.htm) | Fixed-length file in a Windows compatible self-extracting ZIP
NHIS<sup>1</sup> | 2010 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2010_data_release.htm) | Fixed-length file in a ZIP
NHIS<sup>1</sup> | 2011 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2011_data_release.htm) | Fixed-length file in a ZIP
NHIS<sup>1</sup> | 2012 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2012_data_release.htm) | Fixed-length file in a ZIP
NHIS<sup>1</sup> | 2013 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2013_data_release.htm) | Fixed-length file in a ZIP
NHIS<sup>1</sup> | 2014 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2014_data_release.htm) | Fixed-length file in a ZIP
NHIS<sup>1</sup> | 2015 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2015_data_release.htm) | CSV in a ZIP
NHIS<sup>1</sup> | 2016 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2016_data_release.htm) | CSV in a ZIP
NHIS<sup>1</sup> | 2017 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2017_data_release.htm) | CSV in a ZIP
NHIS<sup>1</sup> | 2018 | [Link](https://www.cdc.gov/nchs/nhis/nhis_2018_data_release.htm) | CSV in a ZIP
NHIS<sup>1</sup> | 2019 | [Link](https://www.cdc.gov/nchs/nhis/2019nhis.htm) | CSV in a ZIP

<sup>1</sup>National Health Interview Survey, Centers for Disease Control and Prevention.  Adult surveys only.

## Reference Values

The "reference" values, such as those for Gender, Race, and Ethnicity, were normalized across the data sets.  Please see the "Reference Values Mapping.xlsx" spreadsheet included in [`data/HeadacheDataCompilation.zip`](data/HeadacheDataCompilation.zip) for the full set of possible source values, and how they map to those included in the Headache Data Compilation.
