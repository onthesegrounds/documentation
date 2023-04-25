# Place Record Properties

#### Class: Location

#### **Name (required)**

* Term: otgevents:title
* Equivalent Property: dcterms:title
* Data Type: Text
* Description: A name given to the place
* Usage:
* Input: Single

#### **Alternate Name**

* Term: otgevents:alternateName
* Equivalent Property: schema:alternateName
* Data Type: Text
* Description: An alias for the record.
* Usage: Can include any other variant form of name that the place is known by.
* Input: Multiple

#### **Latitude**

* Term: otgevents:latitude
* Equivalent Property: schema:latitude
* Data Type: Text
* Description: The latitude given to a location.
* Usage: Written as a decimal fraction using positive and negative to indicate north or south ("23.43", not "23° 26′").
* Input: Single

#### **Longitude**

* Term: otgevents:longitude
* Equivalent Property: schema:longitude
* Data Type: Text
* Description: The longitude given to a location.
* Usage: Written as a decimal fraction using negative and positive to indicate west or east ("−91" rather than "91°W").
* Input: Single

#### **City**

* Term: otgevents:city
* Equivalent Property: schema:addressLocality
* Data Type: Text or URI
* Description: The name of the city, town, or village where the place being described is located
* Usage:
* Input: Single

#### **State or Province**

* Term: otgevents:state
* Equivalent Property:&#x20;
* Data Type: Text or URI
* Description: The name of the state or province where the place being described is located.&#x20;
* Usage:
* Input: Single

#### **County or Parish**

* Term: otgevents:county-parish
* Equivalent Property:
* Data Type: Text or URI
* Description: The name of the county or parish where the place being described is located.
* Usage:
* Input: Single

#### **Country**

* Term: otgevents:country
* Equivalent Property: schema:addressCountry
* Data Type: Text or URI
* Description: The verbatim name of the nation where the place being described is located
* Usage: Use the modern name. Use an annotation with the Same As property to indicate the name that is contemporaneous with the events being described, not the modern name.
* Input: Single

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
* Usage: Developed internally by institutions to ease searching and location of places.
* Input: Multiple

#### **Place Type (required)**

* Term: otgevents:placeType
* Equivalent Property: Enslaved Place Type
* Data Type: Place Type Controlled Vocabulary (Enslaved)
* Description: A generic category or class of location.&#x20;
* Usage:
* Input: Multiple

#### **Organization**

* Term: otgevents:organization
* Data type: Omeka S Item or Text or URI
* Description: An organization related to the resource.
* Usage: Omeka S Item or URI are preferred data types.
* Input: Multiple

#### **Region**

* Term: otgevents:region
* Equivalent Property: schema:addressRegion
* Data Type: Text or URI
* Description: Identifies a geographic area that encompasses the place
* Usage:
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
* Input: Multiple
