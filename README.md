# United States Historical City Populations, 1790-2010

This dataset is a compilation of United States historical city populations decennially between 1790 and 2010. We are putting all of the data into a single repository so it can be accessible and improved upon by other researchers.

Erik Steiner, [Spatial History Project][], [Center for Spatial and Textual Analysis][], Stanford University  
Jason A. Heppler, [Department of History][] and [UNO Libraries][], University of Nebraska at Omaha

## Description of the Data

The primary source for this data was a US Census Bureau dataset of ~7500 incorporated cities whose populations surpassed 2500 people at some point in their existence. Additional cities were added from a variety of sources including State Data Centers (Oregon, California, and Iowa) and Jan Lahmeyer (http://www.populstat.info/). We welcome additional contributions from local sources and other state data centers we did not consult. Please see list of state-based sources for possible additions to this data (https://github.com/cestastanford/historical-us-city-populations/blob/master/potential-sources.md).

Cities were first noted in the US Census Bureau dataset when they passed the 2500 person threshold; additional cities below that threshold have been added on an spotty basis from State Data Centers or Populstat (Jan Lahmeyer). Those sources also provide populations for cities before they reached the 2500 threshold and for dates when they dropped below it later, but the coverage for these is uneven.

Disagreements between population values from different sources were reconciled in an rational but ad-hoc manner, giving preference to the US Census Bureau data unless a finer precision number was available from an alternative source, the general population trend indicated otherwise, or the Census data appeared inaccurate in another way (e.g. typos).

Populstat data (Jan Lahmeyer) includes roughly 300 CDPs, MCDs, Townships and historical places not noted in the US Census dataset. Special care should be taken when using these as they are incomplete and may double count populations noted in incorporated cities in the Census data.

Census-derived entity names are those as of Census 2010.   It should be noted that some entities had name changes, so may have multiple records to cover different time spans.  If a place had a substantial population in early decades and then no longer has data, it may be due to a name change, disincorporation, annexation by another city, or change in universe criteria between 1940 and 1950, i.e., focus on incorporated places rather than all large urban places.

Census Bureau Data for 1790-1940 include places of 2500+, regardless of incorporation status.  From 1950 on, the US Census focused on incorporated cities (except for the inclusion of CDPs in Hawaii since the state does not allow incorporation). Determination of incorporation status is based on the GARM and may vary between states.

Historical CDP populations are not rolled into adjacent incorporated places, with the exception of CDPs that were eventually incorporated.

VA independent cities:  data are shown in the independent city record for the years prior to independent city status.  In the original volumes, city populations were listed under the county in which they were located.

County information retained in the file is for general reference only, to differentiate between entities in the same state that have the same name.  County information is incomplete.  For cities located in multiple counties, only one county name is included (generally the larger part). Some duplicate city listings show different counties and still need to be resolved as to whether these are parts, errors, or historical county names.

Honolulu data for 2010 represents the data for Urban Honolulu and East Honolulu CDPs.  

Data for 7 consolidated cities shows the *balance* record only.  Cities are:   Indianapolis, Louisville/Jefferson County, Nashville-Davidson, Augusta-Richmond County, Athens-Clarke County, Milford (CT), Butte-Silver Bow. For those cities their historical populations have been checked against Census volumes, from 1940 forward.

San Francisco data for 1850 is based on an estimate in Michael Haines database; Census returns for Contra Costa, San Francisco, and Santa Clara counties for 1850 were lost. 

Latitude/Longitude data are provided are unofficial approximations. US Census Bureau coordinates are the same as those published in the Census' Gazetteer, intended for regional mapping. "Bing" coordinates were derived from the Bing geocoding service.

## Citation

If you use this data in your research or teaching, please use this suggested citation:

> U.S. Census Bureau and Erik Steiner, Spatial History Project, Center for Spatial and Textual Analysis, Stanford University

If you have questions about the data, please contact [Erik Steiner][] or [Jason Heppler][].

## Contributions

Contributions are more than welcome. Please submit a pull request or e-mail us.

## License

Any code or scripts that appear here are available under the MIT License. Scripts will indicate their license. The data compiled here is public domain and falls within fair use. 

  [Spatial History Project]: http://spatialhistory.stanford.edu
  [Center for Spatial and Textual Analysis]: http://cesta.stanford.edu
  [Department of History]: http://history.unomaha.edu
  [Erik Steiner]: mailto:ebs110@stanford.edu
  [Jason Heppler]: mailto:jheppler@unomaha.edu
