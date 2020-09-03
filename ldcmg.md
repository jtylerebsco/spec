# Specifications for CHD

## DataSource  Information and Feature Overview
|name | value|
|-----|------|
|DataSource name: | Chicano|
|Version: | 1.0|
|Description: OCLC data format – modified MARC tags |
|Content includes: | A&I |
|Ehost Interface: | Y |
|Generic Z39.50: | Y |
|Data includes full text: | N |
|Hyperlinks within FT: | N |
|Embedded images | N |
|Include RDK Expansion Thesaurus (as T1)  | Y |
|Include RDK Standard Expansion Thesaurus (T13) | Y |
|Stopword list | Std (rdk_seg.stp) |
|Enforce Simultaneous User Limit: | N |
|Pre-Explosion in Index (MaxKW): | N |
|Index Browse Enabled | Y |
|Enhanced Clustering: | Off |
|SDI enabled | Y |
|Spellchecker | Y |
|Subject Headings: | N |
|Reference Browsing Allowed: | N |
|Reference Searching Allowed: | N |
|Database Supports Citation Matcher: | N |
|Selected by Default: | N |

## Document History

### jtyler - 202008
-Added XF tag to 19991.

### MWhittaker - 11/30/12
-Per JIRA PECO-189 – corrected Holdings data transformation

## Field Information (IP Data to EP Storage XML – "DDF Spec")

### AN_13
- IP Field ID: 035_a 
- Name/Description: Unique ID
- desc: AN
- EPMARC No.: 13
- EPXMLD No.: 13
- Indexing: P
- EPT: AN
- Required / Does not repeat.
- INSTRUCTIONS:
  - Backfile insructions:
  - Prepend “XCHD” to <d>
  - Load into <AN>
 

    EX. / AN XCHD2
    [
      {
        "CDFRec.v035.sa.d.#text": "2"
      }
    ]
    
    -->
    {
      "df": [
        {
          "@tag": "13",
          "sf": [
            {
              "@code": "a",
              "#text": "XCHD2"
            }
          ]
        }
      ]
    }


### ANIP_11013
- IP Field ID: 
- Name/Description: 
- desc:
- EPMARC No.: 
- EPXMLD No.:
- Indexing:
- EPT: 
