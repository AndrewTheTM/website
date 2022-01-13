---
title: 'Geocoding of Survey Data'
categories:
  - Survey Manual
---
### Chapter-14

I have transfered this text in document "(L) Survey Coding and Data Entry (FHWA 6.10)**" -Martin Trépanier 08/09/08 14:30**
===========================================================================================================================

PLEASE EDIT DOCUMENT (L) Survey Coding and Data Entry (FHWA 6.10), NOT THIS ONE! THANKS! -Martin Trépanier 08/09/08 14:32 -Martin Trépanier 08/09/08 14:33
==========================================================================================================================================================

14.0 Geocoding of Survey Data
=============================

Common socioeconomic indicators (e.g., household income levels, auto­mobile ownership rates), employment requirements (e.g., work shift times), or life-style characteristics (e.g., children in daycare) all contribute to our insight into how and why people travel. In much of the analysis of survey data, such as the number of trips per household in each income range, a trip is a single event and is counted as one unit. However, the fundamental factor which underlies the use of transportation systems is geography. Origin-destination patterns define how many people are trav­eling in individual corridors, and how many people are in the market to use individual highway facilities or transit services, and how many people converge on downtowns or suburban activity centers. Therefore, travel survey data must be linked geographically.

One of the reasons transportation information is so expensive is because data gathered from surveys on trip origins and destinations must be re­lated to specific geographic locations. This process is commonly referred to as geocoding. Geocoding is the process of identifying the geographic location of a trip end and coding a number, such as traffic analysis zone (TAZ), or Census definition, like a Tract or Block, or X Y coordinate, to repre­sent that location. Geocoding is often a tedious and time-con­sum­ing manual process, but the recent advent of geographic information sys­tems (GIS) has led to greater efficiency and accuracy in the geocoding process.

Geographic Information Systems (GIS) are changing the way survey data are collected, analyzed, and displayed. They are designed to capture, store, retrieve, analyze, and display data files referenced to detailed geo­graphic locations, e.g., latitude and longitude, state plane coordinates, census tracts or blocks, or locally developed geographic schemes such as TAZs. GIS organizes and provides access to geographically coded and referenced data, allowing the user to overlay and analyze it using a com­mon frame of reference (either address or block specific), and display it in an easily understood format.  


### 14.1 Purpose of Geocoding

The travel surveys described in this manual are just some of the examples of data collection efforts which are routinely undertaken in transportation modeling studies to deepen our understanding of the overall demand for travel. Descriptions of locations reported by survey respondents have to be identified in some organized way so that they can be analyzed. Analy­sis and processing of data collected from these survey efforts inevitably involve geocoding.

Geocoding trip data supports analysis by allowing information collected in the survey (or from the Census) to be graphically displayed and mapped. For instance, the mapping of trip interchanges between zones provides a summary picture of travel in the region by showing the density of movement in particular corridors. A map of the volume of trips over the roadway system overlaid on the top of the capacity of the links making up the system can quickly show the locations where travel is constrained by inadequate transportation infrastructure. 

Origin and destination data can also be error checked through the geocod­ing process. For example, information about the zone, such as the number of households or employees by type in the zone, is gathered to verify the trip ends to that area. If after the data are geocoded, the analyst identifies a significant amount of shopping trips destined to an industrial or empty zone, then error checks on these trip ends can be performed. 

### 14.1.1 Manual Geocoding

Transportation information can be geocoded manually. This effort entails teams of geocoders locating address information obtained from surveys on area roadway/street maps in order to identify the actual geographic area (traffic analysis zone, census tract or block) associated with surveyed trip ends. This information is then keypunched into the data file and linked with the appropriate survey record. Appendix J shows a recent manual geocoding instruction book provided to survey staff workers on the Pima Association of Governments Household Travel Survey.

Historically, manually geocoding travel information has been an expen­sive and unreliable process. While the information provides great insight into transportation research, it can also dominate planning project re­sources and budgets. The problems associated with this approach include:

* At best, geographic representation is approximate;

* The process is tedious, time-consuming, of questionable accuracy and reliability;

* It is difficult to geocode manually to points; usually manual geocoding has been done to areas such as zones or census tracts. The problems with geocoding to areas are discussed in Section 14.2.

### 14.1.2 Geocoding with GIS

Many GIS applications include a geocoding capability that automates this process, allowing a street address, place name, or intersection to be geo­graphically referenced to latitude and longitude, census tract, or traffic analysis zone. Computer-aided geocoding within GIS, such as TIGER/Line Files and Commercial Files described in Section 14.3, offer numerous advantages over manual techniques including:

* First and foremost, GIS, with a good database, can offer *precise* results. Locations can be geocoded to exact X Y coordinates (expressed accord­ing to any desired coordinate system or projection, whether it be State Plane Coordinates, Latitude-Longitude, Universal Transverse Mercator, etc.).

* Native GIS capabilities to perform *point-in-polygon* analysis, i.e., geo­graphic data can be routinely summarized according to any zone sys­tem, multiple zone systems, or TIGER File geographic representations. The integrity of the data is also maintained even if zone systems change over time. Data from surveys can be readily analyzed with respect to other socioeconomic data expressed according to other zone systems (e.g., census block groups).

* Automated geocoding with GIS offers significant improvements in geocoding accuracy. While errors can undoubtedly occur through ambiguous address information associated with individual survey rec­ords or through errors associated with the address database itself, re­sults will be consistent and will not be subject to judgment errors, fatigue, low skill levels, or other potential problems associated with manual geocoding.

* Automated geocoding is comparatively fast and efficient, and conse­quently far more economical than manual geocoding. Batch runs can geocode large portions of entire survey databases without user inter­vention. Rejects, that is those records which can not be resolved by automated geocoding methods, can either be batched out for correction or be inspected interactively. Misspelled words, vague address refer­ences, or other problems which can be corrected or interpreted by operators, can also be modified interactively.

* Since many GISs are programmable, high skill levels are not required for geocoders (which has traditionally been low anyway). Geocoders need to be trained in the operation of the program, not in the geogra­phy of the region. With application programs, geocoders do not neces­sarily have to know how to operate the GIS itself.

GIS graphical displays can also be used to compensate for the missing, in­accurate, and incorrect address matches that are likely to occur once the initial rounds of geocoding have been conducted. For example, “Heads-Up Digitizing” can be used to visually locate trip destination paths identi­fied from collected surveys on a digitized road map. This technique identifies the approximate locations of geographic destinations for missing address information. This same technique can be used to identify the likely travel paths of origin and destination zone pairs having identical roadway names in more than one City/Town being surveyed.[1](http://docs.google.com/Doc?id=ddc43dqc_57dbghhfd7&hl=en#sdfootnote1sym)  


14.2 Geographic Unit
--------------------

Historically, the unit of geography used for analyzing travel data has been zone systems because regions are divided into geographic units (such as census tracts), and travel patterns can be described in terms of origins in one zone connected to destinations in another zone. Census blocks and census tracts both have been used as a geographic zone system in which travel data can be expressed. More often than not, planners define their own zone system (e.g., traffic analysis zones) to describe travel patterns. 

### 14.2.1 Traffic Analysis Zones

Zones are geographic sections dividing the planning area into relatively similar areas of land-use and land activity. Most often, survey data are geocoded to zones that represent the origins and destinations of travel activity within the region. Since typical travel model systems are not powerful enough to represent every household, place of employment, shopping center, and other activity as a separate origin and destination, these land uses are aggregated into zonal representations.

There are serious limitations to geocoding to areas, such as zones, rather than points. These include:

* Surveys geocoded to one zone system can not easily be translated to a different zone system without repeating the entire process;

* Information collected at one point in time may become obsolete because of subsequent zone system revisions; and

* Surveys geocoded to one zone system can not be easily summarized and analyzed with respect to other geographic and data sources.

### 14.2.2 Census Unit

Zone systems should (and typically do) follow available census data boundaries, either tracts, block groups, or blocks, so that data collected in the decennial census can be used for analysis purposes with minimal manipulation. To implement an efficient data collection and maintenance method, equivalency tables are typically developed to correlate census tracts and census blocks to traffic analysis zones. This table will enable immediate cross reference and database aggregation to traffic analysis zones and various planning areas or other study areas contiguous with Census geography.

The problems previously cited with geocoding to areas rather than points apply to geocoding to census units.

### 14.2.3 X Y Coordinates

Much of the current bias in transportation models, such as trip generation and path assignment, are due to the crudeness of zone specification (as well as network definition). Using an X Y coordinate can generate a pre­cise location for each trip end. The X Y standard allows the greatest flexi­bility in terms of redefining geography, such as adjusting zone sizes or recoding to specifications of other zone systems. 

The use of X Y coordinate coding does have a drawback. X Y coordinates must be designated through a GIS and not manually coded. Therefore, addresses which cannot be automatically matched to a digitized file (which often happens in rural areas) cannot be manually approximated to a particular zone. Although the future of geographic coding will be using the X Y standard, the decision to use these coordinates must be made on a area by area (travel model by travel model) basis. The travel data may be­come less representative, for example, if a disproportionate number of trip ends that cannot be coded are from a specific area type, such as a rural area.

Many transportation professionals believe that as *global positioning system* (GPS) equipment becomes cheaper and more accurate, a universal location system based on latitude and longitude will be developed and potentially be used to define geographic systems within travel models. GPS is a fed­eral system of satellites which allow the user to pinpoint any location using triangulation. Equipment for civilian use may be subject to “selective availability,” which means that the accuracy is deliberately reduced for national security reasons, but this accuracy level can likely be improved with additional equipment called differential GPS which removes most of the selective availability errors.  


14.3 Sources of Base Maps and Address Databases
-----------------------------------------------

The availability and cost of the various base map data sources is a primary criterion in determining the suitability for use as the master database for geographic coding and analysis. Another important selection criterion is the accuracy and ability to periodically update the database. Using these two criteria, the following data sources should be evaluated.

### 14.3.1 TIGER/Line Files

TIGER is a Census Bureau acronym for the digital map database which contains the following digital data for every county in the United States as well as Puerto Rico, the Virgin Islands, Guam, American Samoa, and the Northern Mariana Islands:

* All census map features such as roads, railroads, and rivers;

* Associated collection geography such as census tracts and blocks;

* Political areas such as cities and townships;

* Feature names and classification codes;

* FIPS (Federal Information Processing Standard) codes; and

* Within metropolitan areas originally covered by the 1980 GBF/DIME files, address ranges and zip codes for streets.

The TIGER files replaced the 1980 Census GBF/DIME files. A TIGER/Line is prepared for each county, and the Census Bureau provides files for a State, and all files for the whole nation. The average file sizes are 400 megabytes for a state, and six megabytes for a county. These files are available on CD-ROM in ASCII format.

Typically, significant effort is required to extract street centerline and address information from TIGER files in a format suitable for address-matching. In addition, users should be aware that TIGER files have a reputation for inaccuracies because:

* TIGER files were digitized from 1:100,000 scale maps including actual street locations, and consequently, X Y coordinates for addresses, which can be inaccurate by as much as 500-feet. This potential error is usually relatively unimportant provided that other GIS layers (e.g., the zone system) conforms to the same TIGER base map.

* TIGER files can also be out-of-date. For example, new subdivisions, roadways, transit systems, and other attributes may not be represented in the database.

In many regions, local governments such as MPOs, counties, cities, and emergency dispatch (E911) agencies, are making commitments to maintain accurate and updated address databases using TIGER files as a base. The newest version of TIGER/Line 1994 includes additional address range and nine-digit zip code information.

### 14.3.2 Commercial Files

Commercial files are produced and offered by a number of organizations; a source for locating such files is the *American Demographics* magazine. The commercial files usually are based on TIGER files, which are corrected and augmented in ways to match specific markets such as road maps or voting districts. The files specifically augmented and corrected for address matching can be used to save time in geocoding by increasing the cover­age of the address ranges provided by TIGER. It is important to check to ensure that these files are as up to date as advertised and to realize that even up to date commercial files may have errors.

So, while a commitment to creating and maintaining regional address databases certainly improves geocoding accuracy and precision, it is by no means required. Address databases can be acquired and installed as part of transportation planning and travel demand modeling projects.

Users should note that successful geocoding through address matching requires, at a minimum, an underlying address system. This element is sometimes forgotten. Typically, most metropolitan areas cover some communities which are rural in character, so references to *Rural Route 1* may not be geocoded efficiently with a GIS. Also, most metropolitan areas encompass significant numbers of respondents who report *post office box numbers* as their official mailing address. These too, cannot be geocoded. Telephone interview surveys can help to ameliorate these problems with careful instructions to field personnel to probe for actual street addresses. However, location data drawn from other sources, such as from self-administered surveys or enrollment files, will present these kinds of problems.

Geocoding inaccuracies due to missing post office box numbers and rural addresses may create a biased dataset. This is an important issue consid­ering the nature of this missing information. For example, inaccuracies would be insignificant if such instances were uniformly distributed throughout a region. However, they typically are not because these issues are much more prevalent in some parts of the region (the rural parts) than in others. Methods can be devised to account for these types of problems, 

although with less accuracy. For example, survey records can be geo­coded according to zip code and possibly allocated to traffic analysis zones based on some type of per capita apportionment, “round-robin,” or other random technique. The suitability of these methods depends en­tirely on how the data are to be used.  


14.4 Address Matching and Geocoding
-----------------------------------

Although trip-end data questions are often designed to ask for the struc­tured address response (street address and number, city, state, and zip code) experience has shown that a minority of respondents present their answers in this format. Respondents often do not know the addresses of their destinations and can typically describe the locations in a general way. For example, some respondents can better identify the closest inter­section for a particular destination. The hit rate (address match to geo­graphic representation) achieved during geocoding can vary widely. In some cases, a hit rate of less than 50 percent is obtained. Also, the type of survey, whether it involves an interview where quality control instruc­tions can be followed or a self-administered survey questionnaire with less quality control, has an impact on the usability of address information that can be expected from respondents.

The survey team can identify measures to ensure higher success (hit) rates using interview surveys, including:

* Interviewers can be instructed to probe respondents for full addresses, rejecting post-office box numbers or other insufficient responses.

* “On-line geocoding” can also be used if the interview is being con­ducted with CATI. As interviewers enter address or place data, the CATI/GIS system seeks to locate the place on a geographical database. Interviewers can be instructed to probe respondents until a match is ob­tained for the address, intersection, or establishment. The technique requires an excellent geographic database and highly-skilled interview­ers. Otherwise, the added interview time and respondent burden brought about by continuous probing reduces the effectiveness of the method. It has been successfully used in a recent household travel sur­vey conducted in the Baltimore Metropolitan Area, using the enhanced 911 emergency system address database.

* Sophisticated geocoding applications using GIS can be used to integrate on-line business directories (available from commercial sources). When these databases are available, interviewers should press respondents for the actual name of the business establishment as businesses are referred to in the telephone book. Also, the nearest intersection can be determined to help resolve business names which operate from multi­ple locations in the region.

In addition, other geocoding techniques can be employed through GIS, including:

* **Coding to Zones** – In rural areas where address systems do not exist, the most effective approach may involve coding directly to an estab­lished zone system (e.g., city boundaries or zip codes). The X Y coordi­nate associated with the identified location would be taken from its associated traffic analysis zone. 

* **Place and Landmark Names –** GIS applications to support geocoding can offer users the capability to associate X Y coordinates with general place names or landmarks (e.g., university campuses). Dictionaries de­scribing the locations of these landmarks can be prepared in advance, or, in more sophisticated applications, can be built into the geocoding process as the effort progresses.

* **On-Screen Pointing –** GIS applications can be developed to allow users to use the screen cursor to point to geographic locations on on-screen graphics systems representing a particular region.

To a greater or lesser extent, some of these techniques may result in only the identification of approximate geographic locations and may involve interpretation of the respondent’s answer. Under these circumstances, it is important to record the geocoding method actually used as part of the survey effort, so that later analysis can be conducted to distinguish be­tween X Y coordinates which are known with some accuracy and preci­sion from those which were approximated or interpreted.

No GIS offers native capabilities to incorporate these kinds of functions into a geocoding project. However, since many systems are programma­ble, geocoding applications that can be run within a GIS can be developed to provide this type of functionality.

Using GIS for geocoding, the survey team can determine geographic points by searching an address database. The address database is typi­cally a digital map of street centerlines for a region which includes each street segment coded with the beginning and ending street numbers, on both the right and left sides of the street. A search of the database can lo­cate the appropriate street segment by the specific address provided by the respondent. Interpolation of the address from the end points of the block can be used to define a unique coordinate for the location.

This procedure dates back several decades with the emergence of GBF/DIME geographic files supported by the Census Bureau. The Census Bureau also offered address-matching software to allow planning agencies to geocode survey databases. These methods have now been eclipsed by geocoding capabilities offered by GIS, which operate in a personal com­puter or workstation environment, and are, therefore, more widely available to users.

A wide variety of GIS software is available in the marketplace, ranging in price from $600 for versions which operate on personal computers to $20,000 for large and powerful systems that operate on engineering work­stations. Various versions of these programs are available from vendors that can be operated on multiple and different operating systems (PC-DOS, OS/2, Windows, and UNIX). The features of these programs vary, and the buyer should explore their suitability for the types of address-matching and geocoding capabilities that are desired. Some of the rele­vant features that users may desire include:

1. **Capability to Geocode from Address Databases** – GIS packages typi­cally provide some capability to geocode locations based on addresses. For example, street centerline databases (such as those which might be acquired from Census TIGER files) are coded with the beginning and ending address for each street segment, on each side of the street. Locations for addresses appearing in a survey database, then, are typi­cally assigned an X Y coordinate location along the street segment through interpolation.

- **Capability to Geocode Intersections –** Survey respondents are fre­quently requested to identify the nearest intersection. GIS packages should have a capability to parse intersection addresses if users are dealing with surveys of this type.

- **Capability to Geocode from Parcel Files –** One of the first goals for regions embarking on GIS development programs often involves the creation of a parcel database (developed to support Assessor’s Infor­mation). Along with other data, a typical parcel database contains ad­dress information. Geocoding survey information based on rapid searches of a parcel database offers even greater precision than address-matching based on street centerline databases because X Y coordinate locations are not interpolated, but are precise to the zone of the parcel.

- **Programmability –** A capability for users to write applications to geo­code or to improve upon the geocoding process can be a desirable fea­ture for the GIS. These applications will permit agencies to write more sophisticated geocoding techniques and to conduct geocoding using less skilled technical staff (staff need only learn how to operate the application, not the GIS itself). For example, household surveys in­volve many repetitive locations (family members typically travel to­gether, and, therefore, the same destinations recur frequently in the file), so applications can be written to speed the geocoding process by checking if locations have been previously geocoded. More sophisti­cated applications can be developed to integrate the telephone direc­tory (for business names) on-line with the geographic database to augment geocoding capabilities.

- **Reject Processing –** Most of the effort expended on geocoding and address-matching involves reject processing. Rejects are survey rec­ords for which the GIS cannot fully resolve the respondent location. Reasons for address rejection may include spelling errors, incomplete or ambiguous address specifications, and non-existent addresses. These records must be inspected manually. In addition, individual addresses may not be resolved because of multiple hits. For example, two streets may intersect at more than one location, so the GIS cannot identify the appropriate address match. It is also common for the geo­coding process to accept a less than perfect match, i.e., to assume that a close match is acceptable. Extreme caution must be exercised if such a process is used. Users should examine how gracefully GIS handles the various types of rejects, and the degree of user-interaction provided (or required).

- **Geocoding Offsets –** Ultimately, travel surveys often require location information to be assembled into various zone systems (e.g., census tracts, traffic analysis zones). This can be easily and automatically per­formed by a GIS through point-in-polygon analysis. Many of these zone system boundaries, however, follow major streets. This may cause problems in the GIS related to assigning zones to points which fall exactly on the boundary. More sophisticated GISs provide a capa­bility to offset X Y locations so that they will fall into the correct zone.

- **Address Parsing –** Addresses described on survey records must first be interpreted by the GIS software. The number, street name, street type, city, and zip code information must be identified and then matched against the database. This interpretation of the survey record is known as parsing. The sophistication of GIS systems to parse address information is an important feature and should consider the following questions regarding GIS capabilities:
* Do address components have to be already divided into separate fields by the user so that they can be easily parsed, or can the GIS do this itself?

* Do all address components have to exist or can the GIS address-match based on incomplete information (e.g., survey respondents rarely know whether their destination was MAIN ST or MAIN BLVD)? Can the GIS accommodate vague or ambiguous addresses?

* Does the presence of other address information, such as apartment numbers, confuse the address-matching algorithm?

How well equipped is the address-matching function to accommodate the unique addressing schemes used in the area? For example, the following potential problem areas need to be considered:

* The same street name in two different communities;

* The same street name with different suffixes (Crescent Avenue versus Crescent Place);

* Directional prefixes (East Wyoming versus West Wyoming);

* Different ways of referring to the same street (Martin Luther King Jr. Blvd., M.L. King Blvd., King Blvd., etc.) and;

* The use of Spanish-style street naming, where the street type precedes, rather than follows, the street name (e.g. Camino del Fuego).

14.5 Summary of Recommended Geocoding Procedures
------------------------------------------------

While geocoding procedures will vary depending on the type and characteristics of the specific survey, the following guidelines are recommended.

1. **Geocode to X-Y coordinates**. As discussed in Sections 14.1 and 14.2, there are serious drawbacks to geocoding to areas, such as modeling zones or census tracts, rather than points. Point data can always be later aggregated to areas if necessary. Since point geocoding requires a data file to be used for address matching, this leads directly to the next guideline.

- **Begin by using an automated matching procedure**. If an interviewing system such as CATI is used, this may be done on-line as the survey proceeds. As mentioned in Section 14.3, all areas in the U.S. have at least one source for address matching, the TIGER file. Many areas may have alternate sources, either public or commercial, that my pro­vide greater accuracy. In any case, a significant percentage of the addresses can be matched at relatively low cost. It should be stressed, however, that there are always errors in automated geocoding and that there is always a substantial number of addresses that cannot be matched automatically.

- **Check a sample of the results from the automated matching procedure**. Because of the probability of errors, the results from the automated matching procedure must be checked. If a large number of errors is found, the automated procedure must be revised, replaced, or possibly abandoned.

- **Perform manual geocoding of addresses not matched or matched incorrectly by the automated procedure**.

[1](http://docs.google.com/Doc?id=ddc43dqc_57dbghhfd7&hl=en#sdfootnote1anc) Sarusa,Wayne A., and Meyer, Michael D., *New Technologies for Household Surveys*, Resource Paper for Household Travel Surveys: New Concepts and Research Needs Conference, Irvine, CA (March 1995).   
  


*Travel Survey Manual* 14-*1*

  
 

