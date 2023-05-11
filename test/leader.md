---
description: html page imported successfully from UNBIS Manual
---

# 👍 Leader

***

The **Leader** is the first field of a bibliographic record. The Leader is fixed in length at 24 character positions (**00-23**) consisting of data elements with coded values.

See [MARC21](http://www.loc.gov/marc/bibliographic/bdleader.html) for descriptions of all character positions **00-23**. See [CODES](https://www.un.org/depts/dhl/unbisref\_manual/bd/cleader.htm) for UNBIS coded values.

Fixed field elements entered in the Leader include the following:

**Positions 00-04:** Record length. Computer-generated, five-character numeric string that specifies the length of the entire record.\
**Position 05:** Record status.\
**Position 06:** One-letter code indicating the type of item being described. If the item is essentially the equivalent of a print item but in electronic form, use the same type code you would use for the print version. For UN documents, use the code �a� (language material) regardless of whether the format is printed material or an electronic resource.\
**Position 07:** One-letter code indicating the bibliographic level.\
**Position 17:** One-character code indicating the encoding level, i.e. the status of completion or fullness of the bibliographic record.\
**Position 18:** One-letter code indicating the cataloguing form of the record.

_Examples:_

**000** 02227cam 2200517#a 4500\
where:\


* Positions 00-04: **02227** is record length;\
  Position 05: **c** is record status (corrected or revised)\
  Position 06: **a** is type of the item (language material)\
  Position 07: **m** is bib. level (monograph/item)\
  Position 17: **#** is encoding level (full level)\
  Position 18: **a** is cataloguing form (AACR 2)\


**000** 01063cem 2200325 a 4500\
where:\


* Positions 00-04: **01063** is record length;\
  Position 05: **c** is record status (corrected or revised)\
  Position 06: **e** is type of the item (cartographic material)\
  Position 07: **m** is bib. level (monograph/item)\
  Position 17:   is encoding level (blank)\
  Position 18: **a** is cataloguing form (AACR 2)\
