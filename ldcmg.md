---
title: " Specifications for Chinese Monographs of the 20th Century: 1900-1949 [ldcmg]  \n  \nLSD Standard, Version 1.2"
---

[[Go to Table of
Contents]](../AppData/Local/Microsoft/Windows/Temporary%20Internet%20Files/Content.Outlook/W7NM08M9/xxh_Spec_Template-1.docx#TOC)

Design Standard Information
---------------------------

| **Version:** |   |
|--------------|---|


DataSource Information
----------------------

| **DataSource Name:** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **DataSource ID:**   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Version:**         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Description:**     | Chinese Monographs of the 20th Century: 1900-1949 is a collection of more than 120,000 Chinese Language books in full-text, PDF format covering 13 primary disciplines: philosophy, religion, social science, politics, legal, military, economic, culture and arts, education, language, literature, history, geography, science and technology. This collection gives researchers a unique view of Chinese history and literature during the transition from a semi-feudal society to anew socialist China. |

DataSet Information
-------------------

| **DataSet Name:**     |                                                 |
|-----------------------|-------------------------------------------------|
| **DataSet location:** | \\\\openfiler101\\ddd-data1\\jtyler\\ldcmg\\fix |
| **Description:**      | MARC                                            |
| **Content included:** | (A&I, FTPDF)                                    |

User Interfaces
---------------

| EBSCOhost           |                                 | [] Yes [] No |
|---------------------|---------------------------------|--------------|
| **Other Interface** | [Interface Name, including EDS] | [] Yes [] No |
| **Z39.50**          | *Generic Z39.50*                | [] Yes [] No |

Feature Overview
----------------

| Full text            | *Data includes full text*                                 | [] Yes [] No                                                                           |
|----------------------|-----------------------------------------------------------|----------------------------------------------------------------------------------------|
|                      | *Hyperlinks within FT*                                    | [] Yes [] No                                                                           |
|                      | *Embedded images*                                         | [] Yes [] No                                                                           |
|                      | *Source(s) of Full Text (MFS, XML, etc.)*                 |                                                                                        |
| Linking              | *Local Titles*                                            | [] Yes [] No                                                                           |
|                      | *Quick View Image*                                        | [] Yes [] No                                                                           |
|                      | *Database is Smartlinking Target2*                        | [] Yes [] No                                                                           |
| **Expansion Files**  | *Include RDK Expansion Thesaurus (as T1)*                 | [] Yes [] No                                                                           |
|                      | *Product-specific Expansion Thesauri(us) exist(s)*        | [] Yes [] No                                                                           |
|                      | *Include RDK Standard Expansion Thesaurus (T13)*          | [] Yes [] No                                                                           |
| **Stopwords**        | *Stopword list*  *“Other” = (specify here)*               | [] Std (rdk_seg.stp) [] rdk-school.stp [] Medical market stopword list [] Other        |
| Parameters and       | *Enforce Simultaneous User Limit*                         | [] Yes [] No                                                                           |
| **Attributes**       | *Pre-Explosion in Index (MaxKW)*                          | [] Yes [] No                                                                           |
|                      | *Index Browse Enabled*                                    | [] Yes [] No                                                                           |
|                      | *Enhanced Clustering*                                     | [] On [] Off                                                                           |
|                      | *SDI enabled*                                             | [] Yes [] No                                                                           |
|                      | *Spellchecker*                                            | [] Yes [] No                                                                           |
|                      | *Suggest Subjects (requires thesaurus)*                   | [] Yes [] No                                                                           |
|                      | *Reference Browsing Allowed*                              | [] Yes [] No                                                                           |
|                      | *Reference Searching Allowed*                             | [] Yes [] No                                                                           |
|                      | *Database Supports Citation Matcher*                      | [] Yes [] No                                                                           |
|                      | *Selected by Default*                                     | [] Yes [] No                                                                           |
|                      | *DB Title EPKB Enabled Merge/dedupe ese language control* | [] Yes [] No 10510,18701,18720,18721,10041,10245,18246,106,28,30,10093 MUL.ideograph=1 |

<br>Document History 
---------------------

| **Person** | **Date of Change** | **Description of Change**      |
|------------|--------------------|--------------------------------|
| Jtyler     | 3/10/2020          | **Added FT fields (39 and 4)** |
| Jtyler     | 2/10/2020          | **QA changes**                 |
| Jtyler     | 02/04/2020         | **Added to github**            |

-   **Removed RV limiter**

-   **Removed author from sort keys**

-   **Added standard repletion note for 930**

-   **QA request to use DB-specific EPT to remove values from index browse and
    Guided Search style (effectively, move following tags to hidden section:**

-   **Visible section: AU, and SO tag**

-   **Index browse: ZA, ZT, ZD, ZG, ZH, ZI, ZJ, ZP, ZW**

**Added db-specific 516 form**

Table of Contents:

[Specifications for Chinese Monographs of the 20th Century: 1900-1949 [ldcmg]
1](#_Toc32650940)

[LSD Standard, Version 1.2 1](#_Toc32650941)

[Design Standard Information 1](#design-standard-information)

[DataSource Information 1](#datasource-information)

[DataSet Information 1](#dataset-information)

[User Interfaces 1](#user-interfaces)

[Feature Overview 1](#feature-overview)

[Document History 3](#document-history)

[DATA NORMALIZATION (Loader and DDF) 5](#data-normalization-loader-and-ddf)

[Field Information (IP Data to EP Storage XML – “DDF Spec”)
5](#field-information-ip-data-to-ep-storage-xml-ddf-spec)

[DDF Spec Column Footnotes (Design Reference)
42](#ddf-spec-column-footnotes-design-reference)

[Limitations on Indexing, Searching, MARC records (General Reference)
43](#limitations-on-indexing-searching-marc-records-general-reference)

[AUTHORITY FILES - none 44](#authority-files---none)

[EPT 45](#ept)

[SOURCE TYPE SEARCHING (STS) 49](#source-type-searching-sts)

[TOOLBAR ITEMS 49](#toolbar-items)

[LIMITERS 49](#limiters)

[Dropdown box limiter values 49](#dropdown-box-limiter-values)

[FACETS / CLUSTERS 50](#facets-clusters)

[SORT KEYS 50](#sort-keys)

[DISCIPLINE-LIMITED SEARCHING - none 51](#discipline-limited-searching---none)

[Search Concept Mappings 51](#search-concept-mappings)

[RECORD PRECEDENCE SETTING 51](#record-precedence-setting)

[RELEVANCY RANKING 52](#relevancy-ranking)

[Customizers and R-Files 52](#customizers-and-r-files)

[Enter the 52](#_Toc32650965)

[Field Match - NONE 52](#field-match---none)

[RR Field Weights - NONE 52](#rr-field-weights---none)

[SRP ELEMENTS 53](#srp-elements)

[Title Lists - NONE 53](#title-lists---none)

[EPU/ Global UI 53](#epu-global-ui)

[DBConfigOverride for EPLR (all locals generation)
53](#dbconfigoverride-for-eplr-all-locals-generation)

[SmartLinking - NONE 54](#_Toc32650972)

[DBTagList — Article Relationship Repository (ARR) Smartlinking Information
54](#_Toc32650973)

[\*\*\*Critically important that this is filled out and added to the SRP for all
databases 54](#_Toc32650974)

[DISPLAY & P/S/E FORMS (EPF) – See LSD STandarD form spec
55](#display-pse-forms-epf-see-lsd-standard-form-spec)

[APPENDICES 56](#appendices)

[Appendix A—[Item] 56](#appendix-aitem)

[Appendix B—[Item] 56](#appendix-bitem)

###### DATA NORMALIZATION (Loader and DDF)<br>

**Designer Notes:**

-   **Fields for UST (Universal Search Tags) and Common/Word Tags must be
    defined in the DDF and the EPT**

    -   **For list of these tags,** see the Confluence page “Common Search Tags”
        : <http://confluence/display/ddp/Common+Search+Tags>

    -   Any of these listed tags which are not supported by the data may be
        defined with the EPD number **19991** (this EPD number should not be
        used for anything other than a “dummy” tag)

        -   In the DDF, a single row for EP Storage XML tag \<TagUST\> with EPD
            number 19991 can be used to group all the UST/Common search tags
            which are not appropriate for the database product (in spec
            template, this row is provided above the customizer fields – just
            add tags in EPT column)

        -   In the EPT, each tag must go on a separate row, at the bottom of the
            \#hidden section

-   **Columns 4-9 are subject to QA automation.** These columns *cannot* contain
    strikeouts or comments. They may contain contrasting colors and other
    formatting as necessary to communicate instruction to developer, but this
    formatting will not be interpreted meaningfully by autoQA.

-   Restrict notes regarding specific version changes in Notes column; keep
    change histories in the Document History table

-   **Each EPD number gets its own row** (if necessary, a single EPD number may
    be assigned to more than one row, but it cannot share a row with other EPD
    numbers)

-   **Each Equivalent must go on own row**

-   Follow formatting and content rules for each column (see
    [footnotes](../AppData/Local/Microsoft/Windows/Temporary%20Internet%20Files/Content.Outlook/W7NM08M9/xxh_Spec_Template-1.docx#_DDF_Spec_Column))

Field Information (IP Data to EP Storage XML – “DDF Spec”)
----------------------------------------------------------

| **IP Field ID [1]** | **Name/**                              | **Notes [3]**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | **EP Storage XML tag**                                           | **EPMARC No. [5]** | **EPD No. OR EPMARC XML field value [6]** | **Indexing [7]** | **EPT [8]**                                  |
|                     | **Description [2]**                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | **OR  EPMARC XML**  **desc attribute [4]**                       |                    |                                           |                  |                                              |
|---------------------|----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|--------------------|-------------------------------------------|------------------|----------------------------------------------|
|                     |                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                                                                  |                    |                                           |                  |                                              |
|                     | Delete                                 | *Designer Note: Instruct for record deletion if \@status=”deleted”*  **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                  |                    |                                           |                  |                                              |
| **STATIC**          | DataSource In mapping                  | Output: Required. Does Not Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | \<SourceCat\>                                                    | 18138              | 18138                                     | P                | LN                                           |
| **001**             | Record Identifier CORE                 | Input: Not Required. Output: Required. Does Not Repeat. *Designer Note: Designer must construct a unique identifier if one is not given in the provider’s metadata.* **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | \<AN\>                                                           | 20                 | 13                                        | P                | AN                                           |
|                     |                                        | WLS-Equivalent of AN_13                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                  | [13]               | 11000                                     | WLSR1            | TX / XY                                      |
|                     | Original Vendor record identifier CORE | Input: Not Required. Output: Not Required. Does Not Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | \<ANIP\>                                                         | 11013              | 11013                                     | P                | AN                                           |
|                     |                                        | WLS-Equivalent of ANIP_11013                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                                                  | [11013]            | 11000                                     | WLSR1            | TX / XY                                      |
|                     | Date Update CORE                       | *Designer Note: Not needed; ldcmg is a static db.* Input: Not Required. Output: Not Required. Does Not Repeat. **INSTRUCTIONS:** Parse to CCYYMMDD (no hyphens)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | \<DateEntryCYMD\>                                                | 140                | 18                                        | D                | ED                                           |
|                     |                                        | P-indexed Equivalent for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                  | [18]               | 180                                       | P                | ZD                                           |
|                     | Cover date CORE                        | Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. *Designer Note: Intended to be a string to reflect the date as it is stated by the provider. Not normalized. Added to the Spec Template April 2018.* **INSTRUCTIONS:** Load as is. **Ex. / AN**  \<df tag=”10011”\>     \<sf code=”a”\>Spring 1971\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | \<DateCover\>                                                    | 10011              | 10011                                     | O                |                                              |
| 260\$c              | Publication date In mapping            | Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. *Designer Note: \<DatePubCYMD\> MUST be valid CCYYMMDD date. CANNOT be 00000000* **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | \<DatePubCYMD\>                                                  | 191                | 30                                        | D                | DT                                           |
| 260\$c              | Publication Year In mapping            | Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS:** Load to DatePubCY_28 as CCYY Compression is : D   C   2   2 **Ex. / AN ldcmg.1**  [ { "fields.260.subfields.c": "1939" } ] { "df": [ { "\@tag": "30", "sf": [ { "\@code": "a", "\#text": "19390101" } ] } ] }                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | \<DatePubCY\>                                                    | 192                | 28                                        | D                | PY                                           |
|                     |                                        | P-Equivalent of DatePubCY_28 for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                                                  | [28]               | 10028                                     | P                | ZR                                           |
| 260\$c              | ISI Date In mapping                    | Not required. May repeat. **INSTRUCTIONS:** Load the *YYYY/MM/DD/other info* string into subfield a. **Ex. / AN ldcmg.1**  [ { "fields.210.subfields.d": "1939" } ] { "df": [ { "\@tag": "930", "sf": [ { "\@code": "a", "\#text": "1939/01/01/" } ] } ] }                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | \<DateISI\>                                                      | 930                | 930                                       | O                |                                              |
|                     | Publication Status COMMON              | Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. *Designer Note: Designer must describe source field and conditions for loading status. Values may include:*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | \<StatusPub\>                                                    | 18264              | 18264                                     | P                | PU                                           |
|                     | ISBN CORE                              | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<ISBN\>                                                         | 10020              | 10020                                     | P                | IB                                           |
|                     |                                        | WLS-Equivalent of ISBN_10020_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                  | [10020_a]          | 11000                                     | WLSR1            | TX / XY                                      |
|                     | ISBN CORE                              | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<ISBNNoDash\>                                                   | 22                 | 10022                                     | P                | IB / ZH                                      |
|                     |                                        | WLS-Equivalent of ISBNNoDash_10022                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                                                  | [10022]            | 11000                                     | WLSR1            | TX / XY                                      |
|                     | ISSN CORE                              | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<ISSN\>                                                         | 10021              | 10021                                     | P                | IS                                           |
|                     |                                        | WLS-Equivalent of ISSN_10021_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                  | [10021]            | 11000                                     | WLSR1            | TX / XY                                      |
|                     | ISSN CORE                              | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<ISSNNoDash\>                                                   | 21                 | 21                                        | P                | IS / ZI                                      |
|                     |                                        | WLS-Equivalent of ISSNNoDash_21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                                                                  | [21]               | 11000                                     | WLSR1            | TX / XY                                      |
|                     | Author CORE                            | \_a Main Language \_b Affiliation Number \_c Email \_d Dates \_e Role \_f Affiliations (not numeric) \* \_q Fuller Form of Name \_u AuthorID Active URL Link (to be used only when supplied by data, should not be used for constructed links) \_w AuthorID \_x Alternate Spellings \_y Alternate Language *Designer Note: Please note that subfield b (and the use of an outside \<affiliation\> field) is preferred for affiliation handling.* Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN**  \<df tag=”10510”\>     \<sf code=”a”\>\</sf\> \<sf code=”b”\>\</sf\> \<sf code=”c”\>\</sf\> \<sf code=”d”\>\</sf\> \<sf code=”e”\>\</sf\> \<sf code=”f”\>\</sf\> \<sf code=”q”\>\</sf\> \<sf code=”u”\>\</sf\> \<sf code=”w”\>\</sf\> \<sf code=”x”\>\</sf\> \<sf code=”y”\>\</sf\> \</df\> | \<Author\>                                                       | 510                | 10510                                     | O                |                                              |
|                     |                                        | WLS-Equivalent of Author_10510_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                  | [10510_a]          | 12511                                     | WLR10            | AU / TX / XX / XY                            |
|                     |                                        | P-Equivalent of Author_10510_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                  | [10510_a]          | 10511                                     | P                | AR / ZA                                      |
|                     | Contributor CORE                       | Subfields a, b, c, d, e, f, q, u, w, x, y may be used, following the usage as described above in Author. Input: May not always be present. May Repeat. Output: Not Required. May Repeat. *Designer Note: Please note that subfield b (and the use of an outside \<affiliation\> field) is preferred for affiliation handling.* **INSTRUCTIONS: Ex. / AN**  \<df tag=”18701”\>     \<sf code=”a”\>\</sf\> \<sf code=”b”\>\</sf\> \<sf code=”c”\>\</sf\> \<sf code=”d”\>\</sf\> \<sf code=”e”\>\</sf\> \<sf code=”f”\>\</sf\> \<sf code=”q”\>\</sf\> \<sf code=”u”\>\</sf\> \<sf code=”w”\>\</sf\> \<sf code=”x”\>\</sf\> \<sf code=”y”\>\</sf\> \</df\>                                                                                                                                                                                                   | \<Contributor\>                                                  | 18701              | 18701                                     | O                |                                              |
|                     |                                        | WLS-Equivalent of Contributor_18701_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                  | [18701_a]          | 12511                                     | WLR10            | AU / TX / XX / XY                            |
|                     |                                        | P-Equivalent of Contributor_18701_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                  | [18701_a]          | 10511                                     | P                | AR / ZA                                      |
| 100\$a              | Non-author contributor COMMON          | Subfields a, b, c, d, e, f, q, u, w, x, y may be used, following the usage as described above in Author. Input: May not always be present. May Repeat. Output: Not Required. May Repeat. *Designer Note: Note that ContributorOther is not searched like the other author/contributor fields.*  *Please note that subfield b (and the use of an outside \<affiliation\> field) is preferred for affiliation handling.* **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                 | \<ContributorOther\>                                             | 18721              | 18721                                     | WLSR1            | XX / XY / TX                                 |
|                     | Corporate Author CORE                  | Subfields a, b, c, d, e, f, q, u, w, x, y may be used, following the usage as described above in Author. Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN**  \<df tag=”710”\>     \<sf code=”a”\>\</sf\> \<sf code=”b”\>\</sf\> \<sf code=”c”\>\</sf\> \<sf code=”d”\>\</sf\> \<sf code=”e”\>\</sf\> \<sf code=”f”\>\</sf\> \<sf code=”q”\>\</sf\> \<sf code=”u”\>\</sf\> \<sf code=”w”\>\</sf\> \<sf code=”x”\>\</sf\> \<sf code=”y”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                           | \<AuthorCorporate\>                                              | 710                | 710                                       | O                |                                              |
|                     |                                        | WLS-Equivalent of AuthorCorporate \_710_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                  | [710_a]            | 12511                                     | WLR10            | AU / TX / XX / XY                            |
|                     |                                        | P-Equivalent of AuthorCorporate \_710_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                  | [710_a]            | 10511                                     | P                | AR / ZA                                      |
|                     | Author Affiliation CORE                | *Designer Note: Use when data has author affiliations.* \_a Main Language \_b Affiliation Number Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN**  \<df tag=”11700”\>     \<sf code=”a”\>\</sf\> \<sf code=”b”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | \<Affiliation\>                                                  | 11700              | 11700                                     | WLR0             | AF / XX / TX / XY                            |
| **200\$a \$b \$n**  | Title CORE                             | \_a Title (used to say main language) \_y Expression of \_a in Alternate Character Script (same language) (if provided) \_l Language of Title Field (if provided) Input: Not Required. Does Not Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | \<Title\>                                                        | 245                | 10245                                     | O                |                                              |
|                     |                                        | WLS-Equivalent of 10245                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                  | [10245_a]          | 12245                                     | WLSR30           | TI / XX / TX / XY                            |
|                     | Title CORE                             | \_a Translated or Other Language Expression of the Title (if provided) \_y Expression of \_a in Alternate Character Script (same language) (if provided) \_l Language of \_a (if provided) Input: Not Required. May Repeat. Output: Not Required. May Repeat. Example usage \<df tag=”11242”\>     \<sf code=”a”\>Translation of 10245 into Japanese kanji\</sf\> \<sf code=”y”\>Same Japanese translation of 10245 expressed in yomigana character set\</sf\> \<sf code=”l”\>jap\</sf\> \</df\> **INSTRUCTIONS: Ex. / AN**  ****\<df tag=”11242”\>     \<sf code=”a”\>\</sf\> \<sf code=”y”\>\</sf\> \<sf code=”l”\>\</sf\>   \</df\>                                                                                                                                                                                                                  | \<TitleTranslated\>                                              | 11242              | 11242                                     | O                |                                              |
|                     |                                        | WLS-Equivalent of 11242                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                  | [11242_a]          | 12245                                     | WLSR30           | TI / XX / TX / XY                            |
|                     | Title Variant CORE                     | Additional title selections (component, version, , etc., marc 7xx) \_a Variant Title (not translation) \_y Expression of \_a in Alternate Character Script (same language) (if provided) \_l Language of \_a (if provided) *Designer Note: Please note this field is not intended for title translations but for alternate titles.* Input: Not Required. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                 | \<TitleVariant\>                                                 | 18246              | 18246                                     | WLSR1            | TI / XX / TX / XY                            |
|                     | Abstract CORE                          | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<AbstractSupplied\>                                             | 503                | 10503                                     | O                |                                              |
|                     |                                        | WLS-Equivalent of AbstractSupplied_10503_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |                                                                  | [10503_a]          | 12503                                     | WLSR1            | AB / XX / TX / XY                            |
| **650\$a**          | Subjects CORE                          | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_t Term Type (use only if not already an option in terms with different field numbers) \_w Term ID \_y Transliteration of Term (in same language as \_a) **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<Subject\>                                                      | 650                | 10650                                     | WLSR10           | SU / MH / TX / XX / XY                       |
|                     |                                        | P-Equivalent of Subject_10650_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                  | [10650_a]          | 11602                                     | P                | DE / ZU                                      |
|                     |                                        | P-Equivalent for subject cluster                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                  | [10650_a]          | 11601                                     | P                | QD                                           |
|                     | Subject Person CORE                    | ONLY when subjects can be identified programmatically as person \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_w Term ID (may be OrcID) \_y Transliteration of Term (in same language as \_a) Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”11652”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                  | \<SubjectPerson\>                                                | 11652              | 11652                                     | WLSR10           | SU / PE / MH / TX / XX / XY                  |
|                     |                                        | P-Equivalent of SubjectPerson_11652_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                  | [11652_a]          | 11602                                     | P                | DE / ZU                                      |
|                     |                                        | P-Equivalent of SubjectPerson_11652_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                  | [11652_a]          | 15652                                     | P                | ZP                                           |
|                     |                                        | P-Equivalent for subject cluster                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                  | [11652_a]          | 11601                                     | P                | QD                                           |
|                     | Subject Geographic CORE                | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_w Term ID \_y Transliteration of Term (in same language as \_a) **INSTRUCTIONS:** Ex. / AN \<df tag=”10651”\>     \<sf code=”a”\>\</sf\> \<sf code=”y”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                          | \<SubjectGeographic\>                                            | 10651              | 10651                                     | WLSR1            | SU / GE / MH / TX / XX / XY                  |
|                     |                                        | P-Equivalent of SubjectGeographic\_ 10651_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                  | [10651_a]          | 11602                                     | P                | DE / ZU                                      |
|                     |                                        | P-Equivalent of SubjectGeographic_10651_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                  | [10651_a]          | 16651                                     | P                | ZG / QD                                      |
|                     | Subject Chronological CORE             | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_w Term ID \_y Transliteration of Term (in same language as \_a) **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | \<SubjectChronological\>                                         | 18648              | 18648                                     | WLS              | SU / MH / TX / XX / XY                       |
|                     |                                        | P-Equivalent of SubjectChronological_18648_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                                                  | [18648_a]          | 11602                                     | P                | DE/ ZU                                       |
|                     | Subject Product CORE                   | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_w Term ID \_y Transliteration of Term (in same language as \_a) **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | \<SubjectProduct\>                                               | 11653              | 11653                                     | WLSR0            | PS / XX / XY / TX                            |
|                     |                                        | P-Equivalent of SubjectProduct \_11653_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                  | [11653_a]          | 11602                                     | P                | DE/ZU                                        |
|                     |                                        | P-Equivalent of SubjectProduct \_11653_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                  | [11653_a]          | 15653                                     | P                | ZS                                           |
|                     | Subject Company CORE                   | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_w Term ID \_y Transliteration of Term (in same language as \_a) **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | \<SubjectCompany\>                                               | 11651              | 11651                                     | WLSR1            | CO / TX / XX / XY                            |
|                     |                                        | P-Equivalent of SubjectCompany_11651_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                  | [11651_a]          | 11602                                     | P                | ZU / DE                                      |
|                     |                                        | P-Equivalent of SubjectCompany_11651_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                  | [11651_a]          | 15651                                     | P                | ZO                                           |
|                     | Keyword COMMON                         | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. *Designer Note: These are uncontrolled terms. Controlled terms should be loaded as subjects, even if vendor refers to them as keywords. If provider data has keywords and not subjects, load the keywords – even uncontrolled – to subject_10650. Only use this field when provider sends uncontrolled keywords in addition to subject terms.* \_a Main Term, in Any Language \_l Language of Term \_g Miscellaneous Information, Including Number Linking to Translation of Term \_s Source of Term \_w Term ID \_y Transliteration of Term (in same language as \_a) **INSTRUCTIONS:**                                                                                                                                                                                 | \<Keyword\>                                                      | 10073              | 10073                                     | WLSR1            | KW / TX / XX / XY                            |
|                     |                                        | P-Equivalent of Keyword_10073 for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                  | [10073]            | 15662                                     | P                | ZW                                           |
|                     | Book Edition COMMON                    | Input: Not Required. Does Not Repeat. Output: Not Required. Does Not Repeat. *Designer Note: \*Found in Books and multimedia only* \_a Edition Statement **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | \<BookEdition\>                                                  | 250                | 250                                       | O                |                                              |
|                     | Publisher Info CORE                    | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. \_a Imprint (Display string composite of Place and Publisher as available) *Designer Note: Populate this field for records on which the pub info string is desired for display forms 501/502/516. (Publisher name and location will not be displayed separately). Do not include date in PubInfo string.* **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                              | \<PubInfo\>                                                      | 260                | 260                                       | WLSR0            | TX / XY                                      |
|                     | Publisher Location CORE                | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<PlacePub\>                                                     | 261                | 261                                       | WLSR0            | TX / XY                                      |
| **260\$b**          | Publisher Name CORE                    | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN** ldcmg.1 [ { "fields.260.subfields.b": "新亚书店" } ] { "df": [ { "\@tag": "11260", "sf": [ { "\@code": "a", "\#text": "新亚书店" } ] } ] }                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | \<Publisher\>                                                    | 11260              | 11260                                     | O                |                                              |
|                     |                                        | WLS-Equivalent of Publisher 11260_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                  | [11260_a]          | 12262                                     | WLSR0            | PB / XX / XY / TX                            |
|                     |                                        | P-Equivalent of Publisher 11260_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                                                  | [11260_a]          | 11261                                     | P                | ZB                                           |
|                     | Rights COMMON                          | Input: Not Required. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”18540”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | \<NoteRights\>                                                   | 18540              | 18540                                     | WLSR0            | TX / XY                                      |
|                     | Copyright COMMON                       | Input: Not Required. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”11036”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | \<Copyright\>                                                    | 11036              | 11036                                     | O                |                                              |
|                     | General Note COMMON                    | Input: Not Required. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”11731”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | \<NoteGeneral\>                                                  | 11731              | 11731                                     | WLSR1            | XX / XY / TX                                 |
|                     | Electronic Location and Access CORE    | Input: Not Required. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | \<URLIP\>                                                        | 856                | 856                                       | O                |                                              |
|                     | Open Access Indicator CORE             | *Designer Note: Added April 2018. Does not display in forms, generally.* Input: May not always be present. Does Not Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | \<FlagOpenAccessAvailYN\>                                        | 19041              | 19041                                     | B                | OA                                           |
|                     | Document Type CORE                     | *Designer Note: Document type as given by the vendor. Will not standardize.* Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | \<TypeDocument\>                                                 | 11705              | 11705                                     | P                | PZ / ZT                                      |
|                     |                                        | WLS-Equivalent of TypeDocument_11705                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                  | [11705]            | 11000                                     | WLSR1            | TX / XY                                      |
| **CREATE**          | Publication Type In mapping            | *Designer Note: Needed to support STS and Icons when feasible.* Input: May not always be present. May Repeat. Output: Not Required. May Repeat. Provider’s publication type value must be mapped to an EIS-standard value, found [here](http://ddd.svn.epnet.com/design/Processes/STS/Global%20STS%20Definition.doc) **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | \<TypeSource\>                                                   | 093                | 10093                                     | P                | PT                                           |
|                     |                                        | WLS-Equivalent of TypeSource_10093                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                                                  | [10093]            | 11000                                     | WLSR1            | TX / XY                                      |
|                     | Peer Review CORE                       | Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. *Designer Note: Do not create output for this field if one is not indicated in provider metadata.* **INSTRUCTIONS: Ex. / AN** \<df tag=”10092”\>     \<sf code=”a”\>N\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | \<FlagPeerReviewedY\>                                            | 092                | 10092                                     | B                | RV                                           |
|                     | Source Title CORE                      | *Designer Note: Where journal title (or book title, if item is a book chapter or article) can be captured efficiently, load Title ONLY to this field.*  \_a Main Language \_y Alternative Language Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”10910”\>     \<sf code=”a”\>\</sf\> \<sf code=”y”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                               | \<TitleSource\>                                                  | 910                | 10910                                     | WLSR1            | SO / TX / XY / XX                            |
|                     |                                        | P-Equivalent of TitleSource 10910_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                  | [10910_a]          | 10950                                     | P                | JN                                           |
|                     |                                        | P-Equivalent of TitleSource 10910_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                  | [10910_a]          | 10951                                     | F                | ZJ                                           |
|                     | Volume CORE                            | *Designer Note: Where Journal VOLUME can be captured efficiently, load volume NUMBER (alphanumeric is ok) to this field*. Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”10019”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | \<Volume\>                                                       | 061                | 10019                                     | P                | VI                                           |
|                     | Issue CORE                             | *Designer Note: Where Journal Issue can be captured efficiently, load issue NUMBER (alphanumeric is ok) to this field. Also load supplemental information here.* Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”10062”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | \<Issue\>                                                        | 062                | 10062                                     | P                | IP                                           |
|                     | Start Page CORE                        | *Designer Note: Where article (or chapter) start page can be captured efficiently, load page NUMBER (alphanumeric is ok) to this field. For SEARCH and linking functions. Does not display separately. This should be included within Item Citation for display.* Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”14”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                     | \<PagesStart\>                                                   | 063                | 14                                        | P                | SP                                           |
|                     | End Page CORE                          | *Designer Note: Where article end page can be captured efficiently, load page NUMBER (alphanumeric is ok) to this field*. Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS: Ex. / AN** \<df tag=”366”\>     \<sf code=”a”\>\</sf\> \</df\>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | \<PagesEnd\>                                                     | 366                | 366                                       | O                | O                                            |
| **300**             | Page Count CORE                        | *Designer Note: Where number of pages can be captured efficiently, load NUMERIC Value to this field.* Input: May not always be present. May Repeat. Output: Not Required. Does Not Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | \<CntPages\>                                                     | 912                | 16                                        | I                | PG                                           |
| **546\$a**          | Language In mapping                    | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. Standard practice is to take the value provided in the raw data, load to \_a; then map and load code to \_l. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | \<Language\>                                                     | 546                | 546                                       | WLSR1            | LA / TX / XY                                 |
|                     |                                        | P-Equivalent of Language_546_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                                                                  | [546_a]            | 10546                                     | P                | ZL                                           |
|                     |                                        | P-Equivalent of Language_546_l                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                  | [546_l]            | 11546                                     | P                | LM                                           |
|                     | Series information COMMON              | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<TitleSourceSeries\>                                            | 10908              | 10908                                     | WLSR1            | ST, XX, XY, TX                               |
|                     |                                        | P-Equivalent of TitleSourceSeries 10908_a for phrase-indexing                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                                                  | [10908_a]          | 440                                       | P                | SE                                           |
|                     |                                        | Equivalent of TitleSourceSeries 10908_a for Index Browse                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                                                                  | [10908_a]          | 490                                       | F                | ZQ                                           |
|                     | Digital Object Identifier CORE         | Input: May not always be present. May Repeat. Output: Not Required. May Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<DOI\>                                                          | 11076              | 11076                                     | O                |                                              |
|                     |                                        | WLS-Equivalent for DOI_11076                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                                                  | [11076_a]          | 12076                                     | WLS              | DI / XX / XY / TX                            |
|                     |                                        | P-Equivalent of DOI_11076                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                  | [11076_a]          | 13076                                     | P                | DO                                           |
| **Create**          | FT Indicator CORE                      | Input: May not always be present. Does Not Repeat. Output: Required. Does Not Repeat. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | \<FlagFullTextAvailYN\>                                          | 041                | 10041                                     | B                | FT                                           |
| **CREATE**          | Full Text CORE                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | \<FullText32\>                                                   |                    | 32                                        | TR0              | XY / TX                                      |
| **001**             | Hidden Full Text CORE                  | Hidden Full Text May be dirty full text from PDF processing, or just unformatted full text. **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | \<FullText39\>                                                   |                    | 39                                        | TR0              | XY / TX / XF                                 |
|                     |                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                                                                  |                    |                                           |                  |                                              |
| **Create**          | PDF Size CORE                          | **INSTRUCTIONS:** This is automatically created by SLS. Will load PDF size in \_a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | \<SizePDF\>                                                      | 11659              | 11659                                     | O                |                                              |
| **CREATE**          | Format Full Text CORE                  | Input: N/A Output: Not Required. May Repeat. INSTRUCTIONS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | \<FormatFullText\>                                               | 4                  | 4                                         | P                | FM                                           |
|                     | Thumbnail Image Identifier COMMON      | Used whenever result list must link an image instead of an icon. It can be a base ID that you add a path to in forms, or a full path, as needed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | \<IdentifierImage\>                                              | 10852              | 10852                                     | O                |                                              |
| **create**          | ISI Generic Type Code CORE             | Input: May not be present. May Repeat. Output: Required. May Repeat. *Designer Note: Create lookup to map provider values to ISI Type values below.* **INSTRUCTIONS:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | \<TypeISI\>                                                      | 30000              | 30000                                     | P                | YZ                                           |
|                     |                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                                                                  |                    |                                           |                  |                                              |
|                     | File Identifier CORE                   | **(SLS Supplied)**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | \<LoadDetail\>                                                   | 11681              | 11681                                     | O                |                                              |
| CREATE FOR DDF ONLY | Placeholder for EPT                    | Provides EPD number to anchor UST/Common Word tags in EPT. For more information: <http://confluence/display/ddp/Common+Search+Tags> Designer Note: Added generic list: Please add more if need customization.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | TagUST                                                           | 19991              | 19991                                     | P                | AS/AT/BE/BY/CC/DO/DG/IF/IN/IT/LX/NO/OF/ON/TO |
| CREATE FOR DDF ONLY | TitleSource customizer                 | For Relevancy Ranking – this DDF-only “virtual” field is not loaded to records. (The indexer creates the hook for customizer R-file in a downstream process.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | RankTitleSourceProd                                              | 20001              | 20001                                     | C                | MF                                           |
| CREATE FOR DDF ONLY | PubType customizer                     | For Relevancy Ranking – this DDF-only “virtual” field is not loaded to records. (The indexer creates the hook for customizer R-file in a downstream process.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | RankTypeSourceProd                                               | 20011              | 20011                                     | C                | PF                                           |
| CREATE FOR DDF ONLY | Doc Type customizer                    | For Relevancy Ranking – this DDF-only “virtual” field is not loaded to records. (The indexer creates the hook for customizer R-file in a downstream process.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | RankTypeDocumentProd                                             | 20021              | 20021                                     | C                | DF                                           |
| CREATE FOR DDF ONLY | Date customizer                        | For Relevancy Ranking – this DDF-only “virtual” field is not loaded to records. (The indexer creates the hook for customizer R-file in a downstream process.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | \<RankDateProd\>                                                 | 20031              | 20031                                     | C                | TF                                           |
| CREATE FOR DDF ONLY | Page Count customizer                  | For Relevancy Ranking – this DDF-only “virtual” field is not loaded to records. (The indexer creates the hook for customizer R-file in a downstream process.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | RankCntPagesProd                                                 | 20041              | 20041                                     | C                | LF                                           |

-   If record status is “deleted” add record as a delete record

-   If delete record is AN in lookup then add deleted attribute flag.

The ‘delete’ record will function in the build to overwrite an existing record
with same AN if there is one and will NOT return results on the interface.

-   Create SourceCat_18138 on each record

-   Load subfields with following values:

>   \$a: ldcmg

**Ex. / AN ldcmg.1**

\<df tag=”18138”\>

    \<sf code=”a”\>ldcmg\</sf\>

\</df\>

-   Load filename, omit extension, and appended with dbcode and period

**Ex. / AN ldcmg.1**

[

{

"fields.001": "1"

}

]

{

"df": [

{

"\@tag": "13",

"sf": [

{

"\@code": "a",

"\#text": "ldcmg.1"

}

]

}

]

}

-   Load as given

**Ex. / AN**

\<df tag=”11013”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Compression is: D   C   6   6

**Ex. / AN**

\<df tag=”18”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Take first 4 values of Use appropriate date-parser which recognizes various
    date format conventions, spelled-out months, etc.

-   Load d to DatePubCYMD_30 as CCYYMMDD, padding “MM” and/or “DD” with **01**
    as needed

-   Compression is: D   C   6   6

-   IF date is greater than current year plus 10, THEN do not load date

-   Where no input field, or no input field with a parseable date, THEN do not
    create field in record.

Ex. / AN **ldcmg.**1

[

{

"fields.260.subfields.c": "1939"

}

]

{

"df": [

{

"\@tag": "30",

"sf": [

{

"\@code": "a",

"\#text": "19390101"

}

]

}

]

}

-   **In press**

-   **Preprint**

-   **Postprint**

-   **Published**

-   **etc.**

**INSTRUCTIONS:**

**DEFAULT BEHAVIOR**: -no field created

Will load only with a specified source value.

**Ex. / AN**

{specify source field}

\<df tag=”18264”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   IF field only has ISBN-10:

-   THEN use the standard library to create an ISBN-13 for each ISBN-10. Load to
    \_a

-   Load ISBN Type, where it is known or given in the data, to \_t

-   Type values in \_t should be normalized to the following:

-   print

-   electronic

-   amazon

-   other

-   Load parentheticals or other additional information to \_c, retaining
    parentheses

-   Load each provided and created occurrence to a separate instance of
    ISBN_10020

Ex / AN

\<df tag=”10020”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”c”\>\</sf\>

\<sf code=”t”\>\</sf\>

\</df\>

-   Use valid ISBN parser

-   IF field only has ISBN-10:

-   THEN use the standard library to create an ISBN-13 for each ISBN-10.

-   Load ISBN value only to \_a; Omit any dashes or parenthetical information

-   Load each provided and created occurrence to a separate instance of
    ISBNNoDash_10022

Ex / AN

\<df tag=”10022”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load ISSN to \_a

-   Load ISSN Type, where it is known or given in the data, to \_t

-   Type values in \_t should be normalized to the following:

-   print

-   electronic

-   other

-   Load parentheticals or other additional information to \_c, retaining
    parentheses

-   Load each provided and created occurrence to a separate instance of
    ISSN_10021

Ex / AN

\<df tag=”10021”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”c”\>\</sf\>

\<sf code=”t”\>\</sf\>

\</df\>

-   Use valid ISSN parser.

-   Remove any dashes or parenthetical information and load ISSN value to \_a

-   Load each occurrence to a separate instance of ISSNNoDash_21

Ex / AN

\<df tag=”21”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load as given.

Ex. / AN **ldcmg.**1

5e39e085e4b0bf15477e46c6

[

{

"fields.100.subfields.a": "(美) 范因　著\|沈璇等译述"

}

]

{

"df": [

{

"\@tag": "18721",

"sf": [

{

"\@code": "a",

"\#text": "(美) 范因　著\|沈璇等译述"

}

]

}

]

}

-   Load \$a : \$b. \$n in that order with given delimiters.

**Ex. / AN ldcmg.58769**

[

{

"fields.245.subfields.a": "范氏高等代数学 普及本"

},

{

"fields.245.subfields.b": "普及本"

}

]

{

"df": [

{

"\@tag": "10245",

"sf": [

{

"\@code": "a",

"\#text": "范氏高等代数学 普及本 : 普及本"

}

]

}

]

}

Ex. / AN ldcmg. 58769

[

{

"fields.245.subfields.n": "乙稿"

},

{

"fields.245.subfields.a": "汲古阁景宋钞南宋群贤六十家小集."

},

{

"fields.245.subfields.b": "适安蔵拙余稿"

}

]

{

"df": [

{

"\@tag": "10245",

"sf": [

{

"\@code": "a",

"\#text": "汲古阁景宋钞南宋群贤六十家小集. : 适安蔵拙余稿. 乙稿"

}

]

}

]

}

-   Load second and subsequent occurrences to separate instances of
    TitleVariant_18246 as given

**Ex. / AN**

\<df tag=”18246”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”y”\>\</sf\>

\<sf code=”l”\>\</sf\>

\</df\>

-   Load each occurrence to a separate instance of AbstractSupplied_10503 as
    given.

**Ex. / AN ldcmg.l**

[

{

"fields.520.subfields.a": "数学,自然科学"

}

]

{

"df": [

{

"\@tag": "10503",

"sf": [

{

"\@code": "a",

"\#text": "数学,自然科学"

}

]

}

]

}

-   Load each occurrence of subject to a separate instance of Subject_10650 as
    given.

**Ex. / AN** ldcmg.1

**[**

**{**

**"fields.650.subfields.a": "科学与技术-自然科学-数学"**

**}**

**]**

{

"df": [

{

"\@tag": "10650",

"sf": [

{

"\@code": "a",

"\#text": "科学与技术-自然科学-数学"

}

]

}

]

}

-   Load each selected occurrence to a separate instance of
    SubjectChronological_18648

Ex. / AN

\<df tag=”18648”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”y”\>\</sf\>

\</df\>

-   Load each selected occurrence to a separate instance of SubjectProduct_11653

Ex. / AN

\<df tag=”11653”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”y”\>\</sf\>

\</df\>

-   Load each selected occurrence to a separate instance of SubjectCompany_11651

Ex. / AN

\<df tag=”11651”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”y”\>\</sf\>

\</df\>

-   Load each selected occurrence to a separate instance of Keyword_10073

Ex. / AN

\<df tag=”10073”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load edition statement as given to 250_a

**Ex. / AN**

\<df tag=”250”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load each occurrence to a separate instance of PubInfo_260 as given.

**Ex. / AN**

\<df tag=”260”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load each occurrence to a separate instance of PubPlace_261 as given.

**Ex. / AN**

\<df tag=”261”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load URL to 856_a

-   Load type of URL to 856_b (i.e. Publisher’s URL:, Open Access Full Text,
    Related Information, etc.)

-   IF some or all of the URLs can be determined to resolve to external open
    access full text, load “Open Access Full Text” to 856_b

**Ex. / AN**

\<df tag=”856”\>

    \<sf code=”a”\>\</sf\>

\<sf code=”b”\>\</sf\>

\</df\>

-   Load Y to indicate Open Access, if appropriate to data (*edit instructions
    for each case)*.

**Ex. / AN**

\<df tag=”19041”\>

    \<sf code=”a”\>Y\</sf\>

\</df\>

-   Create on each occuracne and load “BoLoad each occurrence to a separate
    instance of TypeDocument_11705 as given.

**Ex. / AN**

\<df tag=”11705”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Create an instance on each record and load “Book”

**Ex. / AN** 1

\<df tag=”10093”\>

    \<sf code=”a”\>Book\</sf\>

\</df\>

-   Strip “ pages”, and load.

**Ex. / AN** ldcmg.1

[

{

"fields.300.subfields.a": "669 pages"

}

]

{

"df": [

{

"\@tag": "16",

"sf": [

{

"\@code": "a",

"\#text": "669"

}

]

}

]

}

-   Load each occurrence to a separate instance of Language_546

-   Use standard language lookup to render given values to

>   **subfield \$a:** Language name

>   **subfield \$l:** ISO 639-2 alpha-3 code

-   Will render from most current and deprecated ISO 639 alpha-2 and alpha-3
    codes, and elaborated language names (in English)

-   If a match is not found, load:

>   **subfield \$a: [load as given]**

>   **subfield \$l: und**

**Ex. / AN** ldcmg.1

[

{

"fields.041.subfields.a": "chi"

}

]

{

"df": [

{

"\@tag": "546",

"sf": [

{

"\@code": "l",

"\#text": "chi"

},

{

"\@code": "a",

"\#text": "Chinese"

}

]

}

]

}

-   Load content before open parens in \_a, and content inside of parens in \_n.

-   Use mask to pull data conforming to DOI pattern and validate structure:

-   10.[number]/[string]

-   Load the matching string from each such occurrence to a separate instance of
    DOI_11076.

**EX. / AN**

  
\<df tag=”11076”\>

    \<sf code=”a”\>\</sf\>

\</df\>

-   Load “Y” on each record.

**Ex. / AN** ldcmg.117420

\<df tag=”10041”\>

    \<sf code=”a”\>Y\</sf\>

\</df\>

-   Match full text by using 001 and appending “.pdf”

-   Load offset to \_a and full text library filename to \_b

Ex. / AN ldcmg.117420

[\\\\prod-nas105\\licenseddata\\ldcmg-ft](file:///\\prod-nas105\licenseddata\ldcmg-ft)

{

"001" : "117420"

},

117420.pdf

\<df tag="39"\>\<sf code="a"\>cf:y/13708940\</sf\>\<sf
code="b"\>ldcmg2-2113179-20200310-1

23803-423-0002.lib\</sf\>\</df\>

(note values are generated at runtime, so will change for every build. this is
just an example)

-   Load “P” in \_a and \_p on each record

Ex. / AN ldcmg.117420

\<df tag="4"\>\<sf code="a"\>P\</sf\>\<sf code="p"\>P\</sf\>\</df\>

-   Load “BOOK” on each record.

Ex. / AN ldcmg.1

{

"df": [

{

"\@tag": "30000",

"sf": [

{

"\@code": "a",

"\#text": "BOOK"

}

]

}

]

}

### DDF Spec Column Footnotes (Design Reference)

1.  **IP Field ID:** Field ID/tag provided in the original data format (can be
    in XML format via IP2XML program)

2.  **Field Name:** IP’s original name for the field, or some vernacular
    description of the field content.

3.  **Notes:** Provide instruction for handling input data. Can also hold
    examples of data conversions, Designer Notes for future guidance, and QA
    Explain File Notes.

>   Each example must give the source AN and provide examples of input and
>   output fields, representing each aspect of noted instructions and exception
>   handling. Notate output with XMLtag (remember to close tags). Use
>   nonproportional font.

>   **Ex. / AN 11064107000230000-FHWA**

>   004000 20060803

>   004010 2007

>   \<DatePubCYMD\>20060803\</DatePubCYMD\>

>   \<DatePubCY\>2006\</DatePubCY\>

>   \<DatePubFY\>2007\</DatePubFY\>

>   \<DateSortKey\>2006\</DateSortKey\>

1.  **EP Storage XML tag OR EPMARC XML desc attribute**: If EP Storage XML
    output is required, then use values in this column as the EP Storage XML
    tagnames; if EP MARC XML is required, then use values in this column as the
    values for the desc attribute of the datafield element.

2.  **EPMARC No.:** If EPD output is required, then use values in this column as
    the EPD field numbers; if EP MARC XML is required, then use values in this
    column as the values for the tag attribute of the datafield element.

3.  **EPD No. OR EPMARC XML field value:** EBSCO Publishing Database — the data
    file created for databases in EBSCOhost Number that will be stored in the
    database catalog; can differ from the MAR No. When assembling forms, use the
    EPD No. to reference individual fields. Equivalent fields are always created
    in the DDF from the stored EPD number. **Each EPD Number gets its own row.**

4.  **Indexing: most common Indexing types** are: WLS; WLSR; P; W; D and O Legal
    combinations are W, P, N, D (N), R, WS, WL, WR, WLS, WSR, WLR, WLSR, O:

| W         | **Word Indexed —** Indexing the contents of a field by breaking it down by individual words (tokens are indexed as single words). Word parsing rules use spaces and certain punctuation characters as word separators. The “W” indexing type in the DDF. Pure “W” indexing cares only about the existence of the word in that field in the record and does not care where in the field the word occurs. Cannot do phrase or proximity with only “W”. Prefer for fields where P indexing might be difficult to use because multiple variations of data content may be present (e.g., language fields containing full word for language or abbreviations). Most often combined with S and L types.                                                                              |
|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **P**     | **Phrase or Literally Indexed —** Tokens will be indexed literally, including any spaces and other special characters, such as punctuation, not valid for a word. Indexing the contents of a field as if it were a single word. Normally used for fields accessed from authority files or ListBox look-ups. Combines with Types *None.*                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **L**     | Location (Proximity) — Index will include record-relative location information. This allows searching to use proximity operators to specify a relative proximity between tokens. Combines with Types R, S, W. *Must be combined with* W *type.*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **N**     | **Number Indexed —** A field is indexed as a number. These are very large files to maintain. Not used very often or without careful consideration. Can be used for tokens containing purely numeric sequences (integer or floating point). Allows comparison operators such as \>, \<, =, and combinations to be used during searching, allowing for range specifications. Combines with Types *None.*                                                                                                                                                                                                                                                                                                                                                                        |
| **D (N)** | **Date Indexed —** DDF 7+ supports this indexing type and allows fuzzy range searching of date information if incoming data is incomplete (i.e., only YYYY is available and search engine needs to apply MM information to execute the search properly. **N.B.** This is depicted as **N** indexed elsewhere in specifications. Combines with Types *None.*                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **R**     | **Relevancy Ranking Indexing —** Tokens are indexed with relevancy information included. Tokens are checked against a built-in Stopword list, the input Stopword list is **not** used. Combines with Types L, S, W                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **WLS**   | **Word-Location- Stopwords Apply (don’t index Stopwords) (required combo for XX and XY keyword search)—** Indexing the contents of the field by individual word and keeping track of the word location (word number within the field). The “WL” indexing type in the DDF. Proximity operators and adjacency searching is possible only with “WL” indexed fields. Enables proximity searching within field and applies default Stopwords (STOPWORDS: tokens are checked against values specified in the **input** Stopword file. If there is a match the token is not indexed. Combines with Types L,R,W. *Must be combined with* **W** *type.)*                                                                                                                               |
| **WLSR**  | **Word-Location-Stop + Relevancy Ranked (Keyword and Natural Language) —** Same as above plus assign relevancy rank and weight for Natural Language support. Nat.Lang. searching: the technique of searching where the words in a user’s query are compared against the records and documents in the database. Each result is scored (based on the number of words in the query that match words in the database) and records are ordered by relevance — the higher the score the more relevant the hit. Weight: the importance of a field within the record is determined by the weight set in the DDF. The weight acts as a multiplier, e.g. is a field with a weight of 20 (WLSR20.0) the indexing engine will treat every word in that field as if it had 20 occurrences. |
| **O**     | **Display Only Fields —** Field labels will be needed for the display forms. Search tags are “fake” and for use in Bib-3 only, place them in brackets (assign last).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

5.  **Comp = Compression**

6.  **EPT:** List two-character search tags here; may also list alternate search
    tags. Must separate tags with slash delimiter for QA, e.g.: **AU / TX / XY**

Limitations on Indexing, Searching, MARC records (General Reference)
--------------------------------------------------------------------

>   **For general reference, not part of spec.** Programmers should use values
>   from header files via their appropriate defines.

| **Indexing Engine (IE)**                              |               |                                                                                                                                 |
|-------------------------------------------------------|---------------|---------------------------------------------------------------------------------------------------------------------------------|
| Max new unique words per record                       | 20000 words   | Will cause a memory flush after the record completes indexing                                                                   |
| Max words indexed per record                          | 256,000 bytes | filename. 2Mb document                                                                                                          |
| Max size of singe word                                | 255 bytes     |                                                                                                                                 |
| Max number of intermediate files before a merge stage | 240           | Previous TRM ==Initial file 0.0 The indexing is 0.1-0.239, then merge into 1.0, then index the next 240 and merge into 2.0 etc. |
| **Search Engine (SE)**                                |               |                                                                                                                                 |
| Max length of Query                                   | none          | 4K -10K is normally used in applications                                                                                        |
| Max number of Query terms                             | none          |                                                                                                                                 |
| **US MARC Record (output from EPServer or DDS)**      |               |                                                                                                                                 |
| Number of Fields                                      | 1 — 320       |                                                                                                                                 |
| Identifiers (Fields Numbers)                          | 001 — 999     | The range 001-009 is reserved for special uses                                                                                  |
| Max Size of Record                                    | 28,000 bytes  |                                                                                                                                 |

###### AUTHORITY FILES - none

###### EPT

| **Vis/Hid/Def [1]** | **Tag [2]** | **Description [3]**  | **Indexing [4]** | **EPD Numbers [5]**                                                                                                                       | **Expansion [6]** | **Change Notes [7]**        |
|---------------------|-------------|----------------------|------------------|-------------------------------------------------------------------------------------------------------------------------------------------|-------------------|-----------------------------|
| \# [visible]        |             |                      |                  |                                                                                                                                           |                   |                             |
|                     | TX          | All_Text_Fields      | WLS              | 32;39;260;261;546;10073;10650;10651;10908;10910;11000;11651;11652;11653;11700;11731;12076;12245;12262;12503;12511;18246;18540;18648;18721 | T1                | TX: add 10245               |
|                     | TI          | Title                | WLS              | 12245;18246                                                                                                                               | T1                | TI: add row TI Title        |
|                     | SU          | Subject              | WLS              | 10650;10651;11652;18648                                                                                                                   | T1                |                             |
|                     | AB          | Abstract             | WLS              | 12503                                                                                                                                     |                   |                             |
|                     | AN          | Accession_Number     | P                | 13;11013                                                                                                                                  |                   |                             |
|                     | PY          | Publication_Year     | N                | 28                                                                                                                                        |                   |                             |
| \#                  |             |                      |                  |                                                                                                                                           |                   |                             |
|                     | ZU          | Subject_Terms        | P                | 11602                                                                                                                                     |                   |                             |
|                     | ZB          | Publisher            | P                | 11261                                                                                                                                     |                   |                             |
|                     | ZL          | Language             | P                | 10546                                                                                                                                     |                   |                             |
|                     | ZR          | Year_of_Publication  | P                | 10028                                                                                                                                     |                   |                             |
| \# [hidden]         |             |                      |                  |                                                                                                                                           |                   |                             |
|                     | AU          | Author               | WLS              | 12511                                                                                                                                     | T1                |                             |
|                     | SO          | Journal_Name         | WLS              | 10910                                                                                                                                     |                   |                             |
|                     | ZA          | Author               | P                | 10511                                                                                                                                     |                   | ZA: change EPD (from 11501) |
|                     | ZT          | Document_Type        | P                | 11705                                                                                                                                     |                   |                             |
|                     | ZD          | Entry_Date           | P                | 180                                                                                                                                       |                   |                             |
|                     | ZG          | Geographic_Terms     | P                | 16651                                                                                                                                     |                   |                             |
|                     | ZH          | ISBN                 | P                | 10022                                                                                                                                     |                   |                             |
|                     | ZI          | ISSN                 | P                | 21                                                                                                                                        |                   |                             |
|                     | ZJ          | Journal_Name         | P                | 10951                                                                                                                                     |                   |                             |
|                     | ZP          | People               | P                | 15652                                                                                                                                     |                   |                             |
|                     | ZW          | Keyword              | P                | 15662                                                                                                                                     |                   |                             |
| \*                  | AF          | Author_Affiliation   | WLS              | 11700                                                                                                                                     |                   |                             |
|                     | AR          | Author_Phrase        | P                | 10511                                                                                                                                     |                   |                             |
|                     | DE          | Subject_Exact        | P                | 11602                                                                                                                                     |                   |                             |
|                     | DI          | DOI_Word             | WLS              | 12076                                                                                                                                     |                   |                             |
|                     | DO          | DOI_Exact            | P                | 13076                                                                                                                                     |                   |                             |
|                     | DT          | Date_of_publication  | N                | 30                                                                                                                                        |                   |                             |
|                     | ED          | Entry_Date           | N                | 18                                                                                                                                        |                   |                             |
|                     | FM          | FullText_format      | P                | 4                                                                                                                                         |                   |                             |
|                     | FT          | Full_Text_available  | P                | 10041                                                                                                                                     |                   |                             |
|                     | GE          | Geographic_Terms     | WLS              | 10651                                                                                                                                     |                   |                             |
|                     | IB          | ISBN                 | P                | 10020;10022                                                                                                                               |                   |                             |
|                     | IP          | Issue                | P                | 10062                                                                                                                                     |                   |                             |
|                     | IS          | ISSN                 | P                | 21;10021                                                                                                                                  |                   |                             |
|                     | JN          | Journal_name         | P                | 10950                                                                                                                                     |                   |                             |
|                     | KW          | Keyword              | WLS              | 10073                                                                                                                                     |                   |                             |
|                     | LA          | Language_of_Item     | WLS              | 546                                                                                                                                       |                   |                             |
|                     | LM          | Language_Code        | P                | 11546                                                                                                                                     |                   |                             |
|                     | LN          | Source_Institution   | P                | 18138                                                                                                                                     |                   |                             |
|                     | MH          | Subject_Word         | WLS              | 10650;10651;11652;18648                                                                                                                   |                   |                             |
|                     | OA          | OpenAccess_Flag      | P                | 19041                                                                                                                                     |                   |                             |
|                     | PB          | Publisher            | WLS              | 12262                                                                                                                                     |                   |                             |
|                     | PU          | Publication_Status   | P                | 18264                                                                                                                                     |                   |                             |
|                     | PE          | Subject_Person       | WLS              | 11652                                                                                                                                     |                   |                             |
|                     | PG          | Number_of_Pages      | N                | 16                                                                                                                                        |                   |                             |
|                     | PT          | Publication_Type     | P                | 10093                                                                                                                                     |                   |                             |
|                     | CO          | Subject_Company      | WLS              | 11651                                                                                                                                     |                   |                             |
|                     | ZO          | Subject_Companies    | P                | 15651                                                                                                                                     |                   |                             |
|                     | PS          | Subject_Product      | WLS              | 11653                                                                                                                                     |                   |                             |
|                     | ZS          | Subject_Products     | P                | 15653                                                                                                                                     |                   |                             |
|                     | PZ          | Document_Type        | P                | 11705                                                                                                                                     |                   |                             |
|                     | QD          | Subject_Cluster      | P                | 11601;16651                                                                                                                               |                   |                             |
|                     | RV          | Peer_Review          | P                | 10092                                                                                                                                     |                   |                             |
|                     | SE          | Series_Phrase        | P                | 440                                                                                                                                       |                   |                             |
|                     | ZQ          | Series_Browse        | P                | 490                                                                                                                                       |                   |                             |
|                     | ST          | Series_Word          | WLS              | 10908                                                                                                                                     |                   |                             |
|                     | SP          | Start_Page           | P                | 14                                                                                                                                        |                   |                             |
|                     | VI          | Volume               | P                | 10019                                                                                                                                     |                   |                             |
|                     | YZ          | ISI_Type             | P                | 30000                                                                                                                                     |                   |                             |
|                     | XF          | Hidden_Full_Text     | WLS              | 39                                                                                                                                        |                   |                             |
|                     | AS          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | AT          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | BE          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | BY          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | CC          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | DG          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | IF          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | IN          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | IT          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | LX          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | NO          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | OF          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | ON          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
|                     | TO          | TagUST               | P                | 19991                                                                                                                                     |                   |                             |
| \*                  | LO          | Local_BM             | B                | \#externalbitmap                                                                                                                          |                   |                             |
| \*                  | EX          | Exclusion_BM         | B                | \#externalbitmap                                                                                                                          |                   |                             |
| \*                  | MF          | RankTitleSourceProd  | N                | 20001                                                                                                                                     |                   |                             |
| \*                  | PF          | RankTypeSourceProd   | N                | 20011                                                                                                                                     |                   |                             |
| \*                  | DF          | RankTypeDocumentProd | N                | 20021                                                                                                                                     |                   |                             |
| \*                  | TF          | RankDateProd         | N                | 20031                                                                                                                                     |                   |                             |
| \*                  | LF          | RankCntPagesProd     | N                | 20041                                                                                                                                     |                   |                             |
| \# [default]        |             |                      |                  |                                                                                                                                           |                   |                             |
| \*                  | XX          | Default_Search       | WLS              | 10073;10650;10651;10908;10910;11651;11652;11653;11700;11731;12076;12245;12262;12503;12511;18246;18648;18721                               | T1                |                             |
| \*                  | XY          | All_Text_Fields      | WLS              | 32;39;260;261;546;10073;10650;10651;10908;10910;11000;11651;11652;11653;11700;11731;12076;12245;12262;12503;12511;18246;18540;18648;18721 | T1                |                             |

###### <br>SOURCE TYPE SEARCHING (STS)

>   Per Product management request. Usually aligns with selected Publication
>   Types, and occasionally Doc Types. List is in Admin or

>   <http://wiki.epnet.com/twiki/pub/Technology/SchoolK5DatabaseDesign/GlobalSTSDefinition_Refined.doc>

>   Doctype ID and caption and Icon are fixed. Search strings only may be
>   customized. If you need different doc types/captions, place request at
>   <http://epic/departments/technologyandservices/ehostpm/businessanalysis/STSRequests/Forms/Standard.aspx>
>   (and think hard before requesting, especially just for caption)

>   Setup in Admin at Parameters Document Types.

**PM STS Request URL:** [URL from request at STSRequests page (see above)]

| **Product Code** | **Order** | **DocTypeID** | **Caption** | **Global Search String** | **Custom Search String**                                      | **INTERFACE** |   |
|------------------|-----------|---------------|-------------|--------------------------|---------------------------------------------------------------|---------------|---|
| Ldcmg            |           | 4002BK        | Books       |                          | PT Book OR PT Almanac OR PT REFBK OR PT eBook OR PT Audiobook |               |   |
|                  |           |               |             |                          |                                                               |               |   |
|                  |           |               |             |                          |                                                               |               |   |

###### TOOLBAR ITEMS

| **Toolbar ID** | **Caption**  | **Description** | **Start Page Caption** | **Widget** |
|----------------|--------------|-----------------|------------------------|------------|
| 1000IB         | Indexes      | Indexes         | Indexes                | Off        |

###### LIMITERS

>   **Designer Note:**

-   Use cell values as in Admin:Limiters

-   No strikeouts, no comments. Contrasting color may be used to indicate new
    material. Restrict notes and deletions to Document History table

-   Note values for dropdown box limiters in table below

| **Order**  | **Limiter ID**  | **Caption**      | **Control Type**                  | **Search String** | **Default** | **EDS Basic**  **Show** | **EDS Advance Show** |   |
|------------|-----------------|------------------|-----------------------------------|-------------------|-------------|-------------------------|----------------------|---|
|            | FT              | Full Text        | Checkbox                          | FT Y              | Off         | Y                       | Y                    |   |
|            | RV              |                  | Academic (Peer-Reviewed) Journals | Checkbox          | RV Y        |                         |                      |   |
|            | DT1             | Published Date   | Date range                        | DT {val}          |             | Y                       | Y                    |   |
|            | PT100           | Publication Type | Dropdown                          | PT {val}          |             | Y                       | Y                    |   |
|            | LA99            | Language         | ListBox                           | LM {val}          |             | Y                       | Y                    |   |

### Dropdown box limiter values

>   **Designer Note:**

-   Use cell values as in Admin:Limiters

-   No strikeouts, no comments. Contrasting color may be used to indicate new
    material. Restrict notes and deletions to Document History table

| **Limiter ID** | **Values**  |
|----------------|-------------|
| LA99           | chi_Chinese |
| PT100          | Book        |

###### <br>FACETS / CLUSTERS

>   **Designer Notes:**

-   Delete rows not used

-   **Search tag column:** note tag actually used – some dbs will require an
    override tag instead of the default

-   **Create a separate table** for database(s) in family with different sets of
    facets

| **Cluster ID** | **CAPTION**   | **Search Tag** | **Notes** |
|----------------|---------------|----------------|-----------|
| **Subject**    | **Subject**   | DE             |           |
| **Language**   | **Language**  | ZL             |           |
| **Publisher**  | **Publisher** | ZB             |           |
| **SubjectEDS** | **Subject**   | DE             |           |

###### SORT KEYS 

| **Order** | **Sort ID** | **Sort Name** | **Sort Field**                                 |
|-----------|-------------|---------------|------------------------------------------------|
|           | relevance   | Relevance     |                                                |
|           | date        | Date Newest   | L\~30.D:L10910,10909,10245:L14.10:L10510,10071 |
|           | date2       | Date Oldest   | L30.D:L10910,10909,10245:L14.10:L10510,10071   |

**Ehost — suggested sort keys (**Sort keys can use only the physical fields in
your data)**:**

-   date: L\~30.D:L10910:L14.5:L10510

-   date2: L30.D:L10910:L14.5:L10510

-   source: L10910:L\~30.D:L14.5:L10510

-   author: L10510:L\~30.D:L10910:L14.5

-   relevance: does not use sort field

**EDS Data Partners** (Use Author only if supported by data. Relevance is
absolutely required; date and date2 appear to be required, if only to pass
autoqc. Sort Keys can use only the physical fields in your data)

-   relevance \| Relevance

-   date \| Date Descending \| L\~30.D:L10910:L14.5:L10510

-   date2 \| Date Ascending \| L30.D:L10910:L14.5:L10510

-   author \| Author \| L10510:L\~30.D:L10910:L14.5

>   **Designer Notes:**

-   **relevance** is required.

-   **date** and **date2** may not be required by the system, but are required
    to pass autoqc, and their absence *will* cause the database to be dropped
    from results when either of these options are chosen and may mess up
    cross-database sorting in multidatabase profiles/EDS

-   Only one date field is allowed per Sort Key

-   No strikeouts, no comments. Contrasting color may be used to indicate new
    material. Restrict notes and deletions to Document History table

-   Order of elements: [\~\|\^][F\|L][R]\<fld1[,fld1a[,fld1b]]\>[.\<size1\>]

-   Use a tilde (\~) before the field to indicate descending order.

-   L means if not present sort to the end of this subsort

-   F is rarely used, but should sort in title order (i.e., discard initial
    articles like A, An, The, etc.)

-   The .5 in the start page does something good if there are two on the same
    page, and is recommended practice (per RMurray)

-   .D is for date sorting, and recognizes the ccyymmdd format. \~L30.D is the
    standard

-   Use a comma (,) between fields when there are multiple fields to choose from
    for the same subsort (i.e. TitlesSource or TitleSourceSelect)

-   Use a colon (;) to indicate a secondary sort

-   DATE *\*Not required by the system BUT: You must force a “Date” sort if you
    don’t want the non-date-sort database to have its results dropped when you
    select another sort option. The date Sort Key is used by epserver as the
    default sort order for the database and should contain the fields desired
    for the default sort order. This means that it doesn’t matter what field we
    put in the Date sort. Fallout includes poor cross database sorting. This is
    the standard as of 8/2001 and may or may not change in later versions of
    epserver.*

<br>DISCIPLINE-LIMITED SEARCHING - none
=======================================

Search Concept Mappings
-----------------------

See [EPLR Database Configuration Instructions
(Admin)](http://confluence/pages/viewpage.action?pageId=38371974) for detail.
Supply search tags as supported in database. Remove rows not supported by
database (e.g. MID may not be supported in non-Citation Builder databases; BISAC
is for the BISAC code only (not headings); CALLNO is rare; I don’t know what PUB
or SUBJECT are for — they just appeared.

| **Context** | **Concept** | **Search Tag** |
|-------------|-------------|----------------|
| default     | AN          | AN             |
| default     | DT          | DT             |
| default     | ISBN        | IB             |
| default     | ISSN        | ZI             |
| eplr        | AN          | AN             |
| eplr        | DT          | DT             |
| eplr        | ISBN        | IB             |
| eplr        | ISSN        | ZI             |
|             |             |                |

RECORD PRECEDENCE SETTING
=========================

| **dbName** | **Set Precedence Rule?** | **Field map  value** | **Operator** | **Type** |
|------------|--------------------------|----------------------|--------------|----------|
| **ldcmg**  | [X] Yes [] No            | TIMESTAMP            | GTE          | DATE     |

>   The record precedence setting is a field map setting
>   ([FieldMap_Setting.doc](http://epic/departments/technologyandservices/ebscohostServicesEngineering/CSE/EPDB/Configuration/FieldMap_Setting.doc))
>   that has two extra attributes: type and operator. These attributes are
>   optional and default values used if they are not present are:

>   Operator = “GT”

>   Type = “CASE_INSENSITIVE_STRING”.

>   Valid values for the operator attribute are:

| GT  | Greater than (Default) |
|-----|------------------------|
| GTE | Greater than or equal  |
| LT  | Less than              |
| LTE | Less than or equal     |
| EQ  | Equal                  |
| NEQ | Not equal              |

>   Valid values for the type attribute are:

| CASE_INSENSITIVE_STRING | Compares values as case-insensitive strings (Default) |
|-------------------------|-------------------------------------------------------|
| CASE_SENSITIVE_STRING   | Compares values as case-sensitive strings             |
| DATE                    | Compares values as dates                              |
| INTEGER                 | Compares values as integers                           |

>   If precedence is not specified then the system will always up the record in
>   the system. If this is not what you want, you will need to provide an
>   explicit record precedence setting in your system configuration.

>   In the above example (XML View), precedence is being performed on the
>   timestamp field using a DATE comparison. A record has precedence when its
>   timestamp value is GT than the existing record’s timestamp.

>   Some other things to be aware of with precedence rules:

1.  If the new record has the field and the existing record doesn’t, then new
    record has precedence.

2.  If the existing record has the field and new record doesn’t, then the
    existing record has precedence.

3.  It is possible to specify multiple paths. In this scenario the new record
    has precedence only when it meets ALL of the conditions (logical AND).

4.  If neither record has the field, then existing record has precedence.

###### <br>RELEVANCY RANKING

Customizers and R-Files
-----------------------

**Name:** LDBOwFTBaseCustomizer

*Designer Note: if using a product-specific R-file for any of the customizers
(e.g., Pub Type PT/PF), please supply snippet below for development. If using a
“canned” LDBO r-file, or if you are using a Boolean or strictly numerical tag,
no snippet is necessary.*

| Description     | Search Tag | Min      | Max      | Weight | Favor Large |
|-----------------|------------|----------|----------|--------|-------------|
| Pub Date        | TF         | 0        | 127      | 25     | TRUE        |
| Page Count      | LF         | 0        | 4        | 11     | TRUE        |
| Pub Type        | PF         | 0        | 100      | 10     | TRUE        |
| Full Text       | FT         | 0        | 1        | 6      | TRUE        |
| Pub Date Annual | DT         | 19900101 | 20150101 | 5      | TRUE        |

Enter the

**Type** = what kind of data

**Rfile Name** (omit version) – not all customizers require an Rfile. This field
MAY be blank even with weights applied. Should contain the XML file name MINUS
leading “customizer_” and trailing version.xml (For example:
customizer_medical_date-relative-qtr_dt_tf_v1.0_2_5.xml
medical_date-relative-qtr_dt_tf)

**Data Source Search Tag** - Tag of source data pulled by the indexer to create
a new Customizer value index

**Index Search Tag** – may be Calculated field tag created by the Rfile, (ex.
PF) when Rfile is designated OR may be ‘normal’ tag when the existing field
provides sufficient numeric or Boolean value to create the needed relevance
weight.

**MinValue** – min R value generated

**Max Value**- max R value generated

**Weight** – percentage of total relevance weigh that this field controls

**Favor Large** – most always ‘true”

Field Match - NONE
------------------

RR Field Weights - NONE
-----------------------

###### <br>**SRP ELEMENTS**

**Designer Note:**

-   No strikeouts, no comments. Contrasting color may be used to indicate new
    material. Restrict notes and deletions to Document History.

**Title Lists - NONE**
----------------------

-   **Developer:** Transfer these specifications to the “Title List for Admin
    Import” section of SRP.

|                   | **EPMARC** | **EPD** |
|-------------------|------------|---------|
| **Journal Title** | 910        | 10910   |
| **ISSN**          | 21         | 21      |
| **Book Title**    | 245        | 10245   |
| **ISBN**          | 22         | 10022   |
| **Publisher**     | 11260      | 11260   |

>   *Journal title: no format restrictions*

>   *ISSN: no-dash format only*

>   *ISBN: no-dash format only*

>   *Book title: no format restrictions*

>   *Publisher: prefer field (or subfield) which contains only the publisher
>   name*

>   *EPMARC: no restrictions*

>   *EPD: only real fields can be specified, (no Equivalents) since tools used
>   to pull contents of the specified fields target the EPD directly*

**EPU/ Global UI**
------------------

-   **Developer:** Transfer these specifications to the “Title List” section of
    SRP.

| **EPMARC** | *–um D:191;V:61;I:62;P:63;A:510;T:245,11245;J:910,10909;N:21*            |
|------------|--------------------------------------------------------------------------|
| **EPD**    | *–ue D:30;V:10019;I:10062;P:14;A:10510;T:10245,11245;J:10910,10909;N:21* |

>   *Key: D=date; =V=volume; I=issue; P=page; A=author; T=title; J=journal;
>   N=ISSN*

>   *Ex./*

>   *–um D:191;V:61;I:62;P:63;A:510;T:245,11245;J:910,10909;N:21*

>   *–ue D:30;V:10019;I:10062;P:14;A:10510;T:10245,11245;J:10910,10909;N:21*

DBConfigOverride for EPLR (all locals generation)
-------------------------------------------------

If any of the following tags are missing, locals generation for the database
will fail (causing the build to fail). These tags should be included if at all
possible; if the data is not available or the tag cannot be provided for some
other reason (or if some oddity forces a substitute tag to be used instead), the
exception will need to be noted in the eplrdata.DbConfigOverride table.

Greyed values in the table are for illustration ONLY. Before submitting spec to
development, please remove these examples and use values (in black or red font)
appropriate to the database.

| **DbConfigOverride column / DB field** | **Default search tag** | **Is Field Present?**  | **Alternate Search Tag (if Default tag not used in db)**  | **Reason for field not present, or for the alternate search tag** |
|----------------------------------------|------------------------|------------------------|-----------------------------------------------------------|-------------------------------------------------------------------|
|                                        |                        |                        |                                                           |                                                                   |
|                                        |                        |                        |                                                           |                                                                   |
| DTTag / Date 30                        | DT                     | YES                    |                                                           |                                                                   |
| ANTag / Unique ID                      | AN                     | YES                    |                                                           |                                                                   |

<br> 
-----

*SmartLinking - NONE*

| **This database is (mark “[X]” where applicable)**                                                                                                                                                                                                                                                       | **Notes**                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| [ ] Neither a target nor a source for Smartlinking                                                                                                                                                                                                                                                       | **Please note reason:**  |
| [**X** ] Subject to **Article Relationship Repository Smartlinking**  [**X** ] This database is a source. [[see here for list of targets]](http://confluence/display/ddp/Smartlinking+--+General+Information) [ ] This database is a target for the following sources: {list codes, separated by commas} | (Use **DBTagList**)      |
| [ ] Subject to **Book Relationship Repository Smartlinking** [ ] This database is a source. {list codes, separated by commas} [ ] This database is a target for the following sources: {list codes, separated by commas}                                                                                 | (Use **DbBookTagList** ) |

>   **DBTagList — Article Relationship Repository (ARR) Smartlinking
>   Information**

>   *\*\*\*Critically important that this is filled out and added to the SRP for
>   all databases*

>   This section is required for databases with journal articles, whether or not
>   the database is a designated source.

>   **See tag definitions**
>   [here.](http://confluence/display/ddp/Smartlinking+--+General+Information)
>   Use EPD numbers for physical fields only; no Equivalents.

| **dbName** | **tagAN** | **tagIS** | **tagSO** | **tagDT** | **tagVI** | **tagIP** | **tagSP** | **tagAU** | **tagTI** | **tagDI** | **tagFT** | **tagDB** |
|------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|            | 13        | 21        | 10910     | 30        | 10019     | 10062     | 14        | 10510     | 10245     | 12076     |           |           |

###### DISPLAY & P/S/E FORMS (EPF) – See LSD STandarD form spec

APPENDICES
==========

Appendix A—[Item]
-----------------

Appendix B—[Item]
-----------------
