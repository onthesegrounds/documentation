# Organization Record Properties

#### Class: Agent

**Name (required)**

* Term: otgevents:title
* Equivalent Property: dcterms:title
* Data Type: Text
* Description: A name given to the record
* Usage: A title for the organization record, consisting of the commonly used name for the organization.
* Input: Single

#### **Alternate Name**

* Term: otgevents:alternateName
* Equivalent Property: schema:alternateName
* Date Type: Text
* Description: An alias for the record.
* Usage: Can include any other variant form of name that the organization is known by.
* Input: Multiple

#### **Description (required)**

* Term: otgevents:description
* Equivalent Property: dcterms:description
* Data Type: Text
* Description: Narrative description and/or transcription of the entity.
* Usage:
* Input: Multiple

#### **Identifier**

* Term: otgevents:identifier
* Equivalent Property: dcterms:identifier
* Data Type: Text
* Description: An unambiguous reference to the resource within a given context.
* Usage: Developed internally by institutions to ease searching and location of organizations.
* Input: Multiple

#### **Same As**

* Term: otgevents:sameAs
* Equivalent Property: schema:sameAs
* Data Type: URI
* Description: URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.
* Usage:
* Input: Multiple

#### **Is Part Of**

* Term: otgevents:isPartOf
* Equivalent Property: dcterms:isPartOf
* Data Type: Omeka S Item or URI
* Description: A related resource in which the described resource is physically or logically included.
* Usage:
* Input: Multiple

#### **Has Part**

* Term: otgevents:hasPart
* Equivalent Property: dcterms:hasPart
* Data Type: Omeka S Item or URI
* Description: A related resource that is included either physically or logically in the described resource.
* Usage:
* Input: Multiple

#### **Bibliographic Citation**

* Term: otgevents:bibliographicCitation
* Data type: Omeka S Item or URI or Text
* Description: A bibliographic reference for the resource&#x20;
* Usage: Use for references to external secondary sources that provide additional information about the entity. Link to a digitized version if available. If not, input a bibliography citation.
* Input: Multiple\
