# Description of Person

#### **Name (required)**

* Term: otgevents:title
* Equivalent Property: dcterms:title
* Data Type: Text
* Description: A name given to the record
* Usage: A title for the person record. Usually a combination of given name and family name, if available, in direct order. Use Unnamed when the source identifies a person but does not include a name. If a family name can be inferred, add it and then add an annotation pointing to the source.
* Input: Single

#### **Identifier**

* Term: otgevents:identifier
* Equivalent Property: dcterms:identifier
* Data Type: Text
* Description: A unique identifier&#x20;
* Usage: Developed internally by institutions to ease searching and location of people, especially unnamed individuals or those with only a given name.
* Input: Multiple

#### **Given Name**

* Term: otgevents:givenName
* Equivalent Property: schema:givenName
* Data Type: Text
* Description: Given name. In the U.S., the first name of a person.
* Usage:
* Input: Single

#### **Family Name**

* Term: otgevents:familyName
* Equivalent Property: schema:familyName
* Data Type: Text
* Description: Family name. In the U.S., the last name of a person.
* Usage: If the family name is unknown, leave this field blank. If a family name can be inferred, add it and then add an annotation pointing to the source.
* Input: Single

#### **Alternate Name**

* Term: otgevents:alternativeName
* Equivalent Property: schema:alternateName
* Data Type: Text
* Description: An alias for the person.
* Usage: Can include nicknames or any other variant form of name that the person is known by.
* Input: Multiple

#### **Birth Date**

* Term: otgevents:birthDate
* Equivalent Property: schema:birthDate
* Data Type: Timestamp or Text
* Description: Date of birth.
* Usage: Be as specific as possible, using the finest grained date specifier available from day to month to year.
* Input: Single

#### **Death Date**&#x20;

* Term: otgevents:deathDate
* Equivalent Property: schema:deathDate
* Data Type: Timespace or Text
* Description: Date of death.
* Usage: Be as specific as possible, using the finest grained date specifier available from day to month to year.
* Input: Single

#### **Sex**

* Term: otgevents:sex
* Equivalent Property:&#x20;
* Data Type: Sex Controlled Vocabulary (Enslaved)
* Description: Biological sex of the person as designated in or derived from source document(s), often based on observations by a third party of the individual's physical characteristics.&#x20;
* Usage: This can be directly noted in the document or inferred based on other data in the sources, such as gendered names or titles.
* Input: Single

#### **Occupation**

* Term: otgevents:hasOccupation
* Equivalent Property: schema:hasOccupation
* Data Type: Occupation Controlled Vocabulary (Enslaved)
* Description: Skills or trade of the person being described.
* Usage: If the person was active in multiple areas, use multiple instances of this field to include as many controlled vocabulary terms as necessary.
* Input: Multiple

#### **Description (required)**

* Term: otgevents:description
* Equivalent Property: dcterms:description&#x20;
* Data Type: Text
* Description: Narrative description and/or transcription of the entity.
* Usage: This field may include information about disambiguation.
* Input: Multiple

#### Keywords

* Term: otgevents:keywords
* Equivalent property: schema:keywords
* Data type: Text&#x20;
* Description: Keywords to further specify the entity being described.&#x20;
* Usages: Use one input for each word, rather than a comma-separated string.
* Input: Multiple

