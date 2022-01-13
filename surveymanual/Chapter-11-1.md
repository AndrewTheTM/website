---
title: 'Household Survey Coding And Geocoding'
categories:
  - Survey Manual
---
### Chapter-11-1

### CHAPTER 11.0 HOUSEHOLD SURVEY CODING AND GEOCODING

*Note: Significant components of this chapter come from Stopher et al.’s (2008) NCHRP Report, Chapter 2.5 and Tierney et al.’s FHWA**Manual**Introduction (Cambridge Systematics 1994), Chapters L and Z. Other key contributors are Celia Boertlein, Michael Greenwald, Martin Trepanier and Elaine Murakami.*

Common socioeconomic indicators (e.g., household income levels, auto mobile ownership rates), employment requirements (e.g., work shift times), and life-style characteristics (e.g., children in daycare) all contribute to our insight into how and why people travel. In much of the analysis of survey data, such as the number of trips per household in each income range, a trip is a single event and is counted as one unit. However, the fundamental factor which underlies the use of transportation systems is geography. Origin-destination patterns define how many people are traveling in individual corridors, and how many people are in the market to use individual highway facilities or transit services, and how many people converge on downtowns or suburban activity centers. Therefore, travel survey data must be linked geographically.  In this chapter, the coding of survey data is addressed, especially geographic data (origin and destination locations) that have to be geocoded.   

### 11.1 Coding Survey Data

This section addresses the coding of non-geographic data and the coding of complex variables.

**11.1.1 Missing Values, Use of Zero, Etc.**

There is considerable variability in how missing data are recorded in transport surveys and even variability within the same survey. The issues in this item, which are discussed in detail in Section 8.3 of the Technical Appendix, relate to standardizing the ways in which missing data are flagged and how zeroes and blanks are to be used in coding.  

 



It is recommended that the following standardized procedures be adopted together as a group because adoption of some without others will actually increase ambiguities in the data:

 



1.      ***No blanks:***Blanks should never be a legitimate code, and all data fields must contain alphanumeric data.

2.      ***Missing data:***Missing data—whether as the result of a respondent refusal, an indication that the respondent does not know the answer, or as a legitimate skip of the question—should receive a coded numeric value. These values should be negative values (because negative values will not normally occur in a data set except as income) and should be -99 for a refusal. For “don’t know” responses, it should be set as -98. For legitimate skips or non-applicability of a question, the value -97 should be entered.

3.      ***Correspondence between numeric values and codes:***In any question where a legitimate response could be zero, the code for that response will be the number zero (0). This will normally apply to any question requesting a count of elements, where a count of zero is possible—e.g., number of workers in the household, number of children in the household, number of infants in the household, number of cars available to the household, etc. In like manner, the count that is the response will be the coded value in all cases.

4.      ***Coding the number of person trips reported:***In all personal travel surveys that seek to ascertain trip-making behavior of individuals, the person record should contain a count of the number of trips reported by the individual. A count of 0 is to be used only to indicate the response that the person did not travel on the diary day. If no travel information was provided, then the value coded should be -99.

5.      ***Coding binary variables:***The principal binary variables in personal travel surveys are yes/no responses and responses to gender. For questions to which the response is either “yes” or “no,” the response of “yes” is coded as 1 and the response of “no” is coded as 2. For response to the gender question, “male” is 1 and “female” is 2.

### 11.1.2 Coding Complex Variables

This item is concerned with how to code the responses to certain types of questions involving categories that may vary from survey to survey, depending on the level of detail required for a specific survey. Among the questions that fit within this category of variables are income and activity.

 



There are a number of complex variables where it would be useful to adopt a consistent procedure for the values used to report the data. This would enhance comparability of surveys and remove potential ambiguities. It is also contingent on standardizing response categories to certain questions, as discussed in Section 2.1.2 (Stropher et al., 2008). These proposed procedures should be developed not only for any appropriate questions in the minimum question specifications, but also for additional questions that may be used in many travel surveys. Further discussion may be found in Section 8.4 of the Technical Appendix (Stropher et al., 2008). Section 2.1.2 (Stropher et al., 2008) also provides categories for a number of questions which are consistent with the coding procedure proposed here. It is recommended that the codes in that table also be adopted as a consistent set of codes for the variables listed therein.

 



1.      Multi-digit codes for complex variables, similar to the codes shown in Table 11.1, can be adopted in all future travel surveys. For income, the codes specified in Table 1 are recommended to be used for consistency across surveys.

2.      The activity categories shown in Table 11.2 can be adopted for general use in future travel surveys. These categories are based on more or less commonly used trip-purpose categories, but provide for a much more detailed breakdown into activity types that can be used in activity surveys.

 



***Table 11.1 Possible Coding for Varying Income Detail***



| **Minimum Detail for Income Categories** | Minimum Coding | More Detailed Categories | More Detailed Coding |
| Under $10,000 | 00 | Under $5,000 | 000 |
| $5,000–$9,999 | 005 |
| $10,000–$19,999 | 01 | $10,000 –$14,999 | 010 |
| $15,000–$19,999 | 015 |
| $20,000–$29,999 | 02 | $20,000–$24,999 | 020 |
| $25,000–$29,999 | 025 |
| $30,000–$39,999 | 03 | $30,000–$34,999 | 030 |
| $35,000–$39,999 | 035 |
| $40,000–$49,999 | 04 | $40,000–$44,999 | 040 |
| $45,000–$49,999 | 045 |
| $50,000–$59,999 | 05 | $50,000–$54,999 | 050 |
| $55,000–$59,999 | 055 |
| $60,000–$69,999 | 06 | $60,000–$64,999 | 060 |
| $65,000–$69,999 | 065 |
| $70,000–$79,999 | 07 | $70,000–$74,999 | 070 |
| $75,000–$79,999 | 075 |
| $80,000–$89,999 | 08 | $80,000–$84,999 | 080 |
| $85,000–$89,999 | 085 |
| $90,000–$99,999 | 09 | $90,000–$94,999 | 090 |
| $95,000–$99,999 | 095 |
| $100,000–$109,999 | 10 | $100,000–$104,999 | 100 |
| $105,000–$109,999 | 105 |
| $110,000–$119,999 | 11 | $110,000–$114,999 | 110 |
| $115,000–$119,999 | 115 |
| $120,000–$129,999 | 12 | $120,000–$124,999 | 120 |
| $125,000–$129,999 | 125 |
| $130,000–$139,999 | 13 | $130,000–$134,999 | 130 |
| $135,000–$139,999 | 135 |
| $140,000–$149,999 | 14 | $140,000–$144,999 | 140 |
| $145,000–$149,999 | 145 |
| $150,000 and over | 15 | $150,000 and over | 150 |
| Legitimate skip | –997 | Legitimate skip | –997 |
| Don’t know | –998 | Don’t know | –998 |
| Refused | –999 | Refused | –999 |



 



***Table 11.2 Guidelines for Trip-purpose / Activity Categories***



| **Primary Category** | **Code** | **Secondary Categories** | **Code** | **Tertiary Categories** | **Code** |
| Home  | 01  | Sleeping/napping | 011 | Sleeping | 0110 |
| Preparing/eating meals/snack/drinks | 012 | Preparing a meal/snack | 0121 |
| Eating a meal/snack | 0122 |
| Other specified food-related activities | 0129 |
| Home maintenance/cleaning | 013 | Indoor cleaning | 0131 |
| Outdoor cleaning | 0132 |
| Gardening/ tending plants | 0134 |
| Care of textiles and footwear | 0138 |
| Other specified home maintenance and cleaning | 0139 |
| Household management | 014 | Paying household bills | 0141 |
| Budgeting, organizing, planning | 0142 |
| Selling, disposing of household assets | 0143 |
| Other specified household management | 0149 |
| Personal care activities  | 015  | Showering, bathing, personal grooming | 0151 |
| Health/medical care to oneself | 0152 |
| Receiving personal care from others | 0153 |
| Other specified personal care activities | 0159 |
| Using computer/telephone    | 016 | Using telephone (fixed line) (not incl. telephone shopping) | 0161 |
| Using cell phone (not incl. telephone shopping) | 0162 |
| Sending/reading/receiving email | 0163 |
| Internet browsing (not incl. online shopping) | 0164 |
| Shopping for goods and services using telephone (fixed line) | 0165 |
| Shopping for goods and services using cell phone | 0166 |
| Shopping for goods and services using Internet | 0167 |
| Other specified use of computer/telephone | 0169 |
| Caring for others | 017 | Caring for children | 0171 |
| Teaching, training, helping children | 0172 |
| Caring for adults | 0173 |
| Other specified caring for others | 0179 |
| Paid work | 018 | Paid work – main job | 0181 |
| Paid work – other job | 0182 |
| Other specified at home paid work | 0189 |
| Other specified at home activities | 019 | Not further defined (n.f.d.) | 0190 |
| Work    | 02          | Main job | 021 | Regular hours | 0211 |
| Overtime hours | 0212 |
| Extra hours (not paid as overtime) | 0213 |
| Other specified main job activities | 0219 |
| Other job | 022 | Regular hours | 0221 |
| Overtime hours | 0222 |
| Extra hours (not paid as overtime) | 0223 |
| Other specified other job activities | 0229 |
| Work in internship, apprenticeship, etc. | 023 | Regular hours | 0231 |
| Overtime hours | 0232 |
| Extra hours (not paid as overtime) | 0233 |
| Other specified internship/apprenticeship activities | 0239 |
| Unpaid work in family business | 024 | Includes people who worked without pay in a business or on a farm operated by a relative | 0240 |
| Breaks and interruptions from work | 025 | n.f.d. | 0250 |
| Training and studies in relation to work | 026 | n.f.d. | 0260 |
| Volunteer work and community services | 027 | n.f.d. | 0270 |
| Looking for work/setting up business | 028 | Looking for work | 0281 |
| Looking for/setting up business | 0282 |
| Other specified work-related activities | 029 | n.f.d. | 0290 |
| Education/ Childcare Activities | 03 | Attendance at childcare | 031 | n.f.d. | 0310 |
| Attendance at school | 032 | n.f.d. | 0320 |
| Attendance at college | 033 | n.f.d. | 0330 |
| Breaks/waiting at place of general education | 034 | n.f.d. | 0340 |
| Self study for distance education course work | 035 | n.f.d. | 0350 |
| Homework, study, research | 036 | n.f.d. | 0360 |
| Career/professional development training and studies | 037 | n.f.d. | 0370 |
| Other specified activities relating to education/childcare | 039 | n.f.d. | 0390 |
| Eating Out | 04 | Restaurant/café | 041 | Restaurant | 0411 |
| Café/snack bar/cafeteria | 0412 |
| Fast food | 042 | Take out | 0421 |
| Eat in | 0422 |
| At friends’ home | 043 | n.f.d. | 0430 |
| Picnicking | 044 | n.f.d. | 0440 |
| Other specified eating out | 049 | n.f.d. | 0490 |
| Personal Business | 05 | Availing of/shopping for administrative services | 051 | Post Office | 0511 |
| Other specified administrative service | 0519 |
| Availing of/shopping for educational services | 052 | n.f.d. | 0520 |
| Availing of/shopping for professional services | 053 | Banking/credit union | 0531 |
| Insurance | 0532 |
| Real Estate | 0533 |
| Tax or accountant | 0534 |
| Legal services | 0535 |
| Other specified professional services | 0539 |
| Availing of/shopping for government/public services | 054 | n.f.d. | 0540 |
| Availing of/shopping for personal services | 055 | Hairdresser/barber/beautician | 0551 |
| Other specified personal service | 0559 |
| Availing of/shopping for medical and health care services | 056 | Medical | 0561 |
| Dental | 0562 |
| Eye care | 0563 |
| Physiotherapy | 0564 |
| Other specified healthcare service | 0569 |
| Availing of/shopping for rental services | 057 | n.f.d. | 0570 |
| Availing of/shopping for repair and maintenance services | 058 | n.f.d. | 0580 |
| Other specified activities relating to personal business | 059 | n.f.d. | 0590 |
| Shopping          | 06    | Purchasing food and household supplies (groceries) | 061 | n.f.d. | 0610 |
| Purchasing clothes, shoes, personal items | 062 | n.f.d. | 0620 |
| Purchasing school supplies | 063 | n.f.d. | 0630 |
| Purchasing medical supplies | 064 | n.f.d. | 0640 |
| Purchasing household appliances, articles, equipment | 065 | n.f.d. | 0650 |
| Purchasing capital goods (cars, houses, etc.) | 066 | n.f.d. | 0660 |
| Comparison shopping | 067 | n.f.d. | 0670 |
| Window shopping | 068 | n.f.d. | 0680 |
| Purchasing other specified goods. | 069 | n.f.d. | 0690 |
| Social and Recreational Activities | 07                                                   | Communication/ correspondence | 071 | n.f.d. | 0710 |
| Socializing activities | 072 | Doing activities/going to places and events together | 0721 |
| Receiving visitors | 0722 |
| Visiting friends and relatives | 0723 |
| Other specified socializing activities | 0729 |
| Participating in religious/community/cultural events/activities | 073 | Participating in community celebration of historical/cultural events | 0731 |
| Participation in non-religious community rites of weddings, funerals, births, etc. | 0732 |
| Participating in community social functions | 0733 |
| Participating in religious activities | 0734 |
| Participating in other specified religious/community/cultural activities | 0739 |
| Visiting entertainment and cultural venues | 074 | Attendance at movies/cinema | 0741 |
| Attendance at concerts | 0742 |
| Attendance at sporting events | 0743 |
| Attendance at library | 0744 |
| Attendance at amusement park | 0745 |
| Attendance at museum/exhibition/art gallery | 0746 |
| Attendance at zoo/animal park | 0747 |
| Attendance at other specified entertainment and cultural venues | 0749 |
| Indoor and outdoor sporting activities | 075 | Organized sport | 0751 |
| Informal sport | 0752 |
| Exercise (excludes walking) | 0753 |
| Walking, hiking, bushwalking | 0754 |
| Fishing, hunting | 0755 |
| Driving for pleasure | 0756 |
| Participation in other specified indoor and outdoor sporting activities | 0759 |
| Games/hobbies/arts/ crafts | 076 | Card, paper, board games, crosswords | 0761 |
| Gambling | 0762 |
| Arcade games | 0763 |
| Home computer games | 0764 |
| Hobbies, handwork, crafts | 0765 |
| Other specified activities relating to games/hobbies/arts/crafts | 0769 |
| Print/audio/visual media | 077 | Reading | 0771 |
| Watching/listening to television/video programs/radio | 0774 |
| Other specified activities using print, audio or visual media | 0779 |
| Other specified social and recreational activities | 079 | n.f.d. | 0790 |
| Accompan-ying/helping others and travel-related | 08 | Accompanying children to places | 081 | Accompanying children to receive personal services | 0811 |
| Accompanying children to receive medical/health services | 0812 |
| Accompanying children to school, daycare centers | 0813 |
| Accompanying children to sports lessons, etc. | 0814 |
| Accompanying children to other specified places | 0819 |
| Accompanying adults to places | 082 | Accompanying adults to receive personal services | 0821 |
| Accompanying adults to receive medical/health services | 0822 |
| Accompanying adults for shopping | 0823 |
| Accompanying adults for social activities | 0824 |
| Accompanying adults to cultural, sports and entertainment venues | 0825 |
| Accompanying adults to other specified places | 0829 |
| Pick up or drop off other people/get picked up or dropped off (private car, car/van pool, shuttle/limousine) | 083 | Pick up someone or get picked up | 0831 |
| Drop off someone or get dropped off | 0832 |
| Activities related to bus, public transit, and group rides (except car/van pool and shuttle/limousine) | 084 | Wait for/get on vehicle | 0841 |
| Leave/get off vehicle | 0842 |
| Change travel mode | 085 | n.f.d. | 0850 |
| Other specified activity related to accompanying others or travel-related | 089 | n.f.d. | 0890 |
| No activity | 09 | No activity | 091 | n.f.d. | 0910 |
| No recorded activity | 092 | n.f.d. | 0920 |
| No further activity recorded | 093 | n.f.d. | 0930 |
| Other | 99 | n.f.d. | 990 | n.f.d. | 9900 |



### Note: n.f.d. means “not further defined”.

### 11.2 Geocoding of Survey Data

The specificity of travel survey compared to other surveys is that data gathered from surveys on trip origins and destinations must be related to specific geographic locations.  This process is commonly referred to as geocoding. Geocoding is the process of identifying the geographic location of a trip end and coding a number, such as traffic analysis zone (TAZ), or Census definition, like a Tract or Block, or X Y coordinate, to represent that location. Typically, geocoding begins by using a GIS, and manual geocoding is used only for those addresses for which an automated process fails. An overview of geocoding is available on the ESRI website:  <http://webhelp.esri.com/arcgisdesktop/9.2/index.cfm?TopicName=An_overview_of_geocoding>.

 



Geographic Information Systems (GIS) are changing the way survey data are collected, analyzed, and displayed. They are designed to capture, store, retrieve, analyze, and display data files referenced to detailed geographic locations, e.g., latitude and longitude, state plane coordinates, census tracts or blocks, or locally developed geographic schemes such as TAZs. GIS organizes and provides access to geographically coded and referenced data, allowing the user to overlay and analyze it using a common frame of reference (either address or block specific), and display it in an easily understood format.

### 11.2.1 Purpose of Geocoding

The travel surveys described in this manual are just some of the examples of data collection efforts which are routinely undertaken in transportation modeling studies to deepen our understanding of the overall demand for travel. Descriptions of locations reported by survey respondents have to be identified in some organized way so that they can be analyzed. Analysis and processing of data collected from these survey efforts inevitably involve geocoding.

Geocoding trip data supports analysis by allowing information collected in the survey (or from the Census) to be graphically displayed and mapped. For instance, the mapping of trip interchanges between zones provides a summary picture of travel in the region by showing the density of movement in particular corridors. A map of the volume of trips over the roadway system overlaid on the top of the capacity of the links making up the system can quickly show the locations where travel is constrained by inadequate transportation infrastructure.

Origin and destination data can also be error checked through the geocoding process. For example, information about the zone, such as the number of households or employees by type in the zone, is gathered to verify the trip ends to that area. If after the data are geocoded, the analyst identifies a significant amount of shopping trips destined to an industrial or empty zone, then error checks on these trip ends can be performed. Geocoded data can also be used to validate the use of modes in the trip declarations.  For example, a procedure can check if transit has been used in an area where there is station nearby or not.

 



In the past, geocoding typically occurred as a survey post-processing step.  That is, the survey company took the respondents’ reported destinations and appended a geocode at the end.  More recently, this step has occurred much closer in time to the survey collection point, with some examples of real-time geocoding (see Section 11.5).  More typically, survey responses are coded each evening by the survey research firm, so that respondents with uncoded addresses can be called to provide more detail, if time and resources allow.  

 



Since most household travel and activity surveys are now conducted under contract by survey research firms, the geocoding step is most often conducted directly by this firm, or their subcontractor.  There are some cases where the local agency believes that their local knowledge affords them greater insight into geocoding, and they handle the geocoding directly.   

### 11.2.2 Geocoding with GIS

Many GIS applications include a geocoding capability that automates this process, allowing a street address, place name, or intersection to be geographicallygraphically referenced to latitude and longitude, census tract, or traffic analysis zone. Computer-aided geocoding within GIS, such as TIGER/Line Files and Commercial Files described in Section 14.3, offer numerous advantages over manual techniques including:

* First and foremost, GIS, with a good database, can offer precise results. Locations can be geocoded to exact X Y coordinates (expressed according to any desired coordinate system or projection, whether it be State Plane Coordinates, Latitude-Longitude, Universal Transverse Mercator, etc.).
* Native GIS capabilities to perform point-in-polygon analysis, i.e., geographic data can be routinely summarized according to any zone system, multiple zone systems, or TIGER File geographic representations. The integrity of the data is also maintained even if zone systems change over time. Data from surveys can be readily analyzed with respect to other socioeconomic data expressed according to other zone systems (e.g., census block groups).
* Automated geocoding with GIS offers significant improvements in geocoding accuracy. While errors can undoubtedly occur through ambiguous address information associated with individual survey rec­ords or through errors associated with the address database itself, results will be consistent and will not be subject to judgment errors, fatigue, low skill levels, or other potential problems associated with manual geocoding.
* Automated geocoding is comparatively fast and efficient, and consequently far more economical than manual geocoding. Batch runs can geocode large portions of entire survey databases without user intervention. Rejects, that is those records which cannot be resolved with high confidence by automated geocoding methods, can either be batched out for correction or be inspected interactively. Misspelled words, vague address references, or other problems which can be corrected or interpreted by operators, can also be modified interactively.
* Since many GISs are programmable, high skill levels are not required for geocoders (). Geocoders need to be trained in the operation of the program, not in the geography of the region. With many application programs, the system can be designed to be simple enough for people who are not GIS specialists to operate. GIS graphical displays can also be used to compensate for the missing, inaccurate and incorrect address matches that are likely to occur once the initial rounds of geocoding have been conducted. For example, “Heads-Up Digitizing” can be used to visually locate trip destination paths identified from collected surveys on a digitized road map. This technique identifies the approximate locations of geographic destinations for missing address information. This same technique can be used to identify the likely travel paths of origin and destination zone pairs having identical roadway names in more than one City/Town being surveyed (Sarusa and Meyer, 1995).

### 11.2.3 Level of Geocoding to Be Performed

It is theoretically possible to geocode 100% of all trip ends in a survey, but in practice this is difficult, if not impossible. Most travel surveys will encounter some difficulties in geocoding, so there is a need to determine a reasonable minimum match rate that could be achieved in most survey settings. The reader is referred to Section 8.2 of the Technical Appendix for further information on this topic.  It is recommended that standardized procedures be adopted so that

 



1.      Surveys should successfully geocode no less than 99% of household addresses, 95% of school and workplace addresses, and 90% of other locations to latitude/longitude.

2.      Any locations that cannot be geocoded to latitude/longitude should be referenced at least to a TAZ to avoid systematic bias.

3.      Where it is not possible to match out of region locations with a TAZ, it is proposed they be assigned to a representative point outside the study area.

### 11.3 Geographic Unit

Historically, the unit of geography used for analyzing travel data has been zone systems because regions are divided into geographic units (such as census tracts), and travel patterns can be described in terms of origins in one zone connected to destinations in another zone. Census blocks and census tracts both have been used as a geographic zone system in which travel data can be expressed. More often than not, planners define their own zone system (e.g., traffic analysis zones) to describe travel patterns.  In some countries like Canada and the U.K., postal codes can be used because they represent a block face and can be related to precise X Y coordinates.  However, this cannot be done with U.S. ZIP codes.

### 11.3.1 Traffic Analysis Zones

Zones are geographic sections dividing the planning area into relatively similar areas of land-use and land activity. Most often, survey data are geocoded to zones that represent the origins and destinations of travel activity within the region. Since typical travel model systems are not powerful enough to represent every household, place of employment, shopping center, and other activity as a separate origin and destination, these land uses are aggregated into zonal representations.

 



There are serious limitations to geocoding to areas, such as zones, rather than points. These include:

·         Surveys geocoded to one zone system cannot easily be translated to a different zone system without repeating the entire process;

·         Information collected at one point in time may become obsolete because of subsequent zone system revisions; and

·         Surveys geocoded to one zone system cannot be easily summarized and analyzed with respect to other geographic and data sources.

### 11.3.2 Census Unit

Zone systems should (and typically do) follow available census data boundaries, either tracts, block groups, or blocks, so that data collected in the decennial census can be used for analysis purposes with minimal manipulation. To implement an efficient data collection and maintenance method, equivalency tables are typically developed to correlate census tracts and census blocks to traffic analysis zones. This table will enable immediate cross reference and database aggregation to traffic analysis zones and various planning areas or other study areas contiguous with Census geography.

 



The problems previously cited with geocoding to areas rather than points apply to geocoding to census units.

### 11.3.3 X Y Coordinates

Much of the current bias in transportation models, such as trip generation and path assignment, are due to the crudeness of zone specification (as well as network definition). Using an X Y coordinate can generate a precise location for each trip end. The X Y standard allows the greatest flexibility in terms of redefining geography, such as adjusting zone sizes or recoding to specifications of other zone systems.

 



The use of X Y coordinate coding does have a drawback. X Y coordinates must be designated through a GIS and not manually coded. Therefore, addresses which cannot be automatically matched to a digitized file (which often happens in rural areas) cannot be manually approximated to a particular zone. Although the future of geographic coding will be using the X Y standard, the decision to use these coordinates must be made on a area by area (travel model by travel model) basis. The travel data may become less representative, for example, if a disproportionate number of trip ends that cannot be coded are from a specific area type, such as a rural area.

As *global positioning system* (GPS) equipment becomes less expensive and more widely used in travel behavior studies, use of latitude and longitude and automated routines to convert them into other coordinate systems will become standard practice.  

### 11.4 Sources of Base Maps and Address Databases

The availability and cost of the various base map data sources is a primary criterion in determining the suitability for use as the master database for geographic coding and analysis. Another important selection criterion is the accuracy and ability to periodically update the database. Using these two criteria, the following data sources should be evaluated.

### 11.4.1 TIGER/Line Files

TIGER is a Census Bureau acronym for the digital map database which contains the following digital data for every county in the United States as well as Puerto Rico, the Virgin Islands, Guam, American Samoa, and the Northern Mariana Islands:

·         All census map features such as roads, railroads, and rivers;

·         Associated collection geography such as census tracts and blocks;

·         Political areas such as cities and townships;

·         Feature names and classification codes;

·         FIPS (Federal Information Processing Standard) codes; and

·         Address ranges and ZIP codes for streets in many areas.

A TIGER/Line is prepared for each county, and the Census Bureau provides files for a State, and all files for the whole nation. TIGER/Line files are now available as shapefiles and can be downloaded free of charge, from the U.S. Census Bureau webpage.  <http://www.census.gov/geo/www/tiger/tgrshp2009/tgrshp2009.html>.

·         The MAF/TIGER Accuracy Improvement Project (MTAIP) conducted in advance of the 2010 U.S. Census aims to meet or exceed a spatial accuracy of 7.6 meters for the street centerline file.  (<http://www.census.gov/geo/mod/maftiger.html>, accessed October 19, 2009)

·         TIGER files can  be out-of-date. For example, new subdivisions, roadways, , and other attributes may be missing, a perpetual problem for geographic referencing systems in times of rapid growth. 

### 11.4.2 Commercial Files

Commercial files are widely available through companies that provide navigation systems, such as TeleAtlas Dynamap,  . The commercial navigation files have typically been driven with high precision GPS units, and address information may be more complete in larger urban areas than in more rural areas.  Similar to the publicly available TIGER files, incompleteness is often a problem in fast growing areas.  

Often, GIS software includes an option for a geographic base file.  For example, ESRI ArcView  includes Streetmap in the license, but this file may be 3-5 years old.  For some areas, this may be sufficient, while fast growing areas may need to license an updated file.  

 



Users should note that successful geocoding through address matching requires, at a minimum, an underlying address system. This element is sometimes forgotten. Typically, most metropolitan areas cover some communities which are rural in character, so references to *Rural Route 1* may not be geocoded efficiently with a GIS. However,  improved emergency response systems have resulted in many areas changing their addressing to more geocodable formats.  Also, most metropolitan areas encompass significant numbers of respondents who report *post office box numbers* as their official mailing address. These too, cannot be geocoded. Telephone interview surveys can help to ameliorate these problems with careful instructions to field personnel to probe for actual structure number street name style addresses, closest intersections, or  physical landmarks. However, location data drawn from other sources, such as from self-administered surveys or enrollment files, will continue to present these kinds of problems.

 



Geocoding inaccuracies due to missing post office box numbers and rural addresses may create a biased dataset. This is an important issue considering the nature of this missing information. For example, inaccuracies would be insignificant if such instances were uniformly distributed throughout a region. However, they typically occur in rural areas more than in urban areas Methods can be devised to account for these types of problems, although with less accuracy. For example, survey records can be geocoded according to ZIP code and possibly allocated to traffic analysis zones based on some type of per capita apportionment, “round-robin,” or other random technique. The suitability of these methods depends entirely on how the data will be used.

11.5 Address Matching and Geocoding
-----------------------------------

Although trip-end data questions are often designed to ask for the structured address response (street address and number, city, state, and ZIP code) experience has shown that a minority of respondents present their answers in this format. Respondents often do not know the addresses of their destinations and can typically describe the locations in a general way. For example, some respondents can better identify the closest intersection. The hit rate (address match to geographic representation) achieved during geocoding can vary widely. In some cases, a hit rate of less than 50 percent is obtained. Also, the type of survey, whether it involves an interview where quality control instructions can be followed (or with the help of a CATI with a GIS database) or a self-administered survey questionnaire with less quality control, has an impact on the usability of address information that can be expected from respondents.

The survey team can identify measures to ensure higher success (hit) rates using interview surveys, including:

·         Interviewers can be instructed to request that respondents give full street addresses, rejecting post-office box numbers or other incomplete or nonspecific responses.

·         “On-line geocoding” can also be used if the interview is being conducted with CATI. As interviewers enter address or place data, the CATI/GIS system seeks to locate the place on a geographical database. Interviewers can be instructed to probe respondents until a match is obtained for the address, intersection, or establishment. The technique requires an excellent geographic database and highly-skilled interviewers. Otherwise, the added interview time and respondent burden brought about by continuous probing reduces the effectiveness of the method. It has been successfully used in a recent household travel survey conducted in the Baltimore Metropolitan Area, using the enhanced 911 emergency system address database.

·         Sophisticated geocoding applications using GIS can be used to integrate on-line business directories (available from commercial sources). When these databases are available, interviewers should press respondents for the actual name of the business establishment as businesses are referred to in the telephone book. Also, the nearest intersection can be determined to help resolve business names which operate from multiple locations in the region.

 



In addition, other geocoding techniques can be employed through GIS, including:

·         **Coding to Zones** – In rural areas where address systems do not exist, the most effective approach may involve coding directly to an established zone system (e.g., city boundaries or ZIP codes). The X Y coordinate associated with the identified location would be taken from its associated traffic analysis zone.

·         **Place and Landmark Names –** GIS applications to support geocoding can offer users the capability to associate X Y coordinates with general place names or landmarks (e.g., university campuses). Dictionaries de scribing the locations of these landmarks can be prepared in advance, or, in more sophisticated applications, can be built into the geocoding process as the effort progresses.  Many on-line resources, including GoogleMaps, MapQuest, electronic Yellow Pages, and other resources incorporate business directories, and addresses that can be used to assist with geocoding.  Google Maps TM,  especially using their StreetView may be especially useful when attempting to find a location for which respondents provide only partial address information. 

·         **On-Screen Pointing –**GIS applications can be developed to allow users to use the screen cursor to point to geographic locations on on-screen graphics systems representing a particular region.

 



To a greater or lesser extent, some of these techniques may result in only the identification of approximate geographic locations and may involve interpretation of the respondent’s answer. Under these circumstances, it is important to record the geocoding method actually used as part of the survey effort, so that later analysis can be conducted to distinguish between X Y coordinates which are known with some accuracy and precision from those which were approximated or interpreted.

 



No GIS offers native capabilities to incorporate these kinds of functions into a geocoding project. However, since many systems are programmable, geocoding applications that can be run within a GIS can be developed to provide this type of functionality.

 



Using GIS for geocoding, the survey team can determine geographic points by searching an address database. The address database is typically a digital map of street centerlines for a region which includes each street segment coded with the beginning and ending street numbers, on both the right and left sides of the street. A search of the database can locate the appropriate street segment by the specific address provided by the respondent. Interpolation of the address from the end points of the block can be used to define a unique coordinate for the location.

These methods have now been eclipsed by geocoding capabilities offered by GIS, which operate in a personal computer or workstation environment, and are, therefore, more widely available to users.

 



A wide variety of GIS software is available in the marketplace, ranging in price from $600 for versions which operate on personal computers to $20,000 for large and powerful systems that operate on engineering work stations. Various versions of these programs are available from vendors that can be operated on multiple and different operating systems (PC-DOS, OS/2, Windows, and UNIX). The features of these programs vary, and the buyer should explore their suitability for the types of address-matching and geocoding capabilities that are desired. Some of the relevant features that users may desire include:

1.      **Capability to Geocode from Address Databases** – GIS packages typically provide some capability to geocode locations based on addresses. For example, street centerline databases (such as those which might be acquired from Census TIGER files) are coded with the beginning and ending address for each street segment, on each side of the street. Locations for addresses appearing in a survey database, then, are typically assigned an X Y coordinate location along the street segment through interpolation.

2.      **Capability to Geocode Intersections –**Survey respondents are frequently requested to identify the nearest intersection. GIS packages should have a capability to parse intersection addresses if users are dealing with surveys of this type.

3.      **Capability to Geocode from Parcel Files –**One of the first goals for regions embarking on GIS development programs often involves the creation of a parcel database (developed to support Assessor’s Information). Along with other data, a typical parcel database contains ad dress information. Geocoding survey information based on rapid searches of a parcel database offers even greater precision than address-matching based on street centerline databases because X Y coordinate locations are not interpolated, but are precise to the zone of the parcel.

4.      **Programmability –**A capability for users to write applications to geocode or to improve upon the geocoding process can be a desirable feature for the GIS. These applications will permit agencies to write more sophisticated geocoding techniques and to conduct geocoding using less skilled technical staff (staff need only learn how to operate the application, not the GIS itself). For example, household surveys involve many repetitive locations (family members typically travel together, and, therefore, the same destinations recur frequently in the file), so applications can be written to speed the geocoding process by checking if locations have been previously geocoded. More sophisticated applications can be developed to integrate the telephone directory (for business names) on-line with the geographic database to augment geocoding capabilities.

5.      **Reject Processing –**Most of the effort expended on geocoding and address-matching involves reject processing. Rejects are survey records for which the GIS cannot fully resolve the respondent location. Reasons for address rejection may include spelling errors, incomplete or ambiguous address specifications, and non-existent addresses. These records must be inspected manually. In addition, individual addresses may not be resolved because of multiple hits. For example, two streets may intersect at more than one location, so the GIS cannot identify the appropriate address match. It is also common for the geocoding process to accept a less than perfect match, i.e., to assume that a close match is acceptable. Extreme caution must be exercised if such a process is used. Users should examine how gracefully GIS handles the various types of rejects, and the degree of user-interaction provided (or required).

6.      **Geocoding Offsets –**Ultimately, travel surveys often require location information to be assembled into various zone systems (e.g., census tracts, traffic analysis zones). This can be easily and automatically performed by a GIS through point-in-polygon analysis. Many of these zone system boundaries, however, follow major streets. This may cause problems in the GIS related to assigning zones to points which fall exactly on the boundary. More sophisticated GISs provide a capability to offset X Y locations so that they will fall into the correct zone.

7.      **Address Parsing –**Addresses described on survey records must first be interpreted by the GIS software. The number, street name, street type, city, and ZIP code information must be identified and then matched against the database. This interpretation of the survey record is known as parsing. The sophistication of GIS systems to parse address information is an important feature and should consider the following questions regarding GIS capabilities:

·         Do address components have to be already divided into separate fields by the user so that they can be easily parsed, or can the GIS do this itself?

·         Do all address components have to exist or can the GIS address-match based on incomplete information (e.g., survey respondents rarely know whether their destination was MAIN ST or MAIN BLVD)? Can the GIS accommodate vague or ambiguous addresses?

·         Does the presence of other address information, such as apartment numbers, confuse the address-matching algorithm?

How well equipped is the address-matching function to accommodate the unique addressing schemes used in the area? For example, the following potential problem areas need to be considered:

* The same town name in two different but adjacent states (Kansas City);
* The same street name in two different but nearby communities;

·         The same street name with different street types (e.g., Crescent Avenue versus Crescent Place);

·         Directional prefixes and suffixes (East Wyoming versus West Wyoming; 14th ST NE versus 14th ST NW);

·         Different ways of referring to the same street (Martin Luther King Jr. Blvd., M.L. King Blvd., King Blvd., etc.) and;

·         The use of Spanish-style street naming, where the street type precedes, rather than follows, the street name (e.g., Camino del Fuego).

11.6 Summary of Recommended Procedures
--------------------------------------

While geocoding procedures will vary depending on the type and characteristics of the specific survey as well as the desired outcomes, the following guidelines are recommended.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.      **Geocode to X-Y coordinates**. As discussed in Sections 14.1 and 14.2, there are serious drawbacks to geocoding to areas, such as modeling zones or census tracts, rather than points. Point data can always be later aggregated to areas if necessary. Since point geocoding requires a data file to be used for address matching, this leads directly to the next guideline.

2.      **Begin by using an automated matching procedure**. If an interviewing system such as CATI is used, this may be done on-line as the survey proceeds. As mentioned in Section 14.3, all areas in the U.S. have at least one source for address matching, the TIGER file. Many areas may have alternate sources, either public or commercial, that may provide greater accuracy. In any case, a significant percentage of the addresses can be matched at relatively low cost. It should be stressed, however, that there are always errors in automated geocoding and that there is always a substantial number of addresses that cannot be matched automatically.

3.      **Check a sample of the results from the automated matching procedure**. Because of the probability of errors, the results from the automated matching procedure must be checked. If a large number of errors are found, the automated procedure must be revised, replaced, or possibly abandoned.

4.      **Perform manual geocoding of addresses not matched or matched incorrectly by the automated procedure**.

 



**In summary**, for most uses, data must be coded.  There are many categories of interest, and some standardization is valuable, as described here.  Moreover, the spatial nature of the data sets is undeniable, so geocoding becomes a key task in data preparation for users. 

**REFERENCES**

Sarusa, Wayne A. and Michael D. Meyer. *New Technologies for Household Surveys*, Resource Paper for Household Travel Surveys: New Concepts and Research Needs Conference, Irvine, CA (March 1995).

 



Stopher, P. et al. 2008. Standardized Procedures for Personal Travel Surveys. National Cooperative Highway Research Program Report 571, Transportation Research Board, Washington, D.C. Available at <http://onlinepubs.trb.org/onlinepubs/nchrp/nchrp_rpt_571.pdf>. (Technical appendix available at http://onlinepubs.trb.org/onlinepubs/nchrp/nchrp\_w93.pdf.).

