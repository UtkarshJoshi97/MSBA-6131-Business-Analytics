# MSBA-6131-Business-Analytics

MSBA 6131 (Fall 2024) Live Case
# In Collaboration with The Good Acre

# 1. Problem Definition

This will be discussed in detail during the live case kickoff event by The Good Acre (TGA).
Broadly speaking, TGA is currently considering 5 possible locations to open additional
warehouses that would facilitate the aggregation of agricultural products from nearby farmers.
The objective is to assess which location(s) should be considered as the best candidate(s). The 5
locations under consideration are: Duluth, Rochester, Wilmar, Owatonna, Fergus Fall, which are
respectively in the St. Louis, Olmsted, Kandiyohi, Steele, and Otter Tail County.

# 2. Data Description

The live case uses a single (combined) data file, collected via government census. Data file will
be shared on Canvas and also pre-loaded in the live case Vocareum server. See below for
explanation of each field:

• Year: either 2017 or 2022, year of the census;

• Ag_District / Ag_District_Code: agricultural district and the corresponding code;

• County / County_ANSI: county (in Minnesota) and the corresponding American National
Standards Institute code;

• Commodity: The primary subject of interest (e.g., CORN, CATTLE, LABOR,
TRACTORS, OPERATORS);

• Data_Item: A more elaborate description of the subject of interest;

• Domain: Generally another characteristic of operations that produce a particular
commodity (e.g., ECONOMIC CLASS, AREA OPERATED, NAICS
CLASSIFICATION, SALES). For chemical usage data, the domain describes the type of
chemical applied to the commodity;

• Domain_Category: Categories or partitions within a domain (e.g., under domain = Sales,
domain categories include $1,000 TO $9,999, $10,000 TO $19,999, etc);

• Value: Published data value or suppression reason code. For suppression reason code, see
https://quickstats.nass.usda.gov/src/glossary.pdf (section “Abbreviations”);

• Type: type of data record, one of “Animals”, “Crops”, “Demographics”, and
“Economics”. “Animals” and “Crops” respectively record information about animal /
crop products. “Demographics” contains demographic information of producers/farmers
associated with different commodity categories. “Economics” contains transactional
information (e.g., labor, farm sales).

• For more information about data descriptions, please check

https://quickstats.nass.usda.gov/param_define and

https://quickstats.nass.usda.gov/src/glossary.pdf.

The client has also provided a map of their current suppliers:
-- Hideen due to NDA
