# Description of the Event

#### **Title (required)**

* Term: otgevents:title
* Equivalent property: dcterms:title
* Data type: Text
* Description: A name given to the record.&#x20;
* Usage: A descriptive title for the event. Usually includes the date, the participant, and event type
* Input: Single

#### **Description**&#x20;

* Term: otgevents:description
* Equivalent property: dcterms:description
* Data type: Text
* Description: Narrative description and/or transcription of the entity.
* Usage:
* Input: Multiple

#### Identifier

* Term: otgevents:identifier
* Equivalent Property: dcterms:identifier
* Data Type: Text
* Description: An unambiguous reference to the resource within a given context.
* Usage: Developed internally by institutions to ease searching and location of places.
* Input: Multiple

#### **Event Type (required)**

* Term: otgevents:type
* Equivalent property: dcterms:type
* Data type: Custom Vocabulary: Event Types
* Description: The kind of event being described.
* Usage: Select from a controlled vocabulary of event types.
* Input: Single

#### **Keywords**

* Term: otgevents:keywords
* Equivalent property: schema:keywords
* Data type: Text&#x20;
* Description: Keywords to further specify the entity being described.&#x20;
* Usages: Use one input for each word, rather than a comma-separated string.
* Input: Multiple

#### **Action Status (required)**

* Term: otgevents:actionStatus
* Equivalent property: schema:actionStatus
* Data type: Custom Vocabulary: Action Status
* Description: An indicator of the completion status of an event.
* Usage: Select from a controlled vocabulary indicating the status of the event.
* Input: Single

#### **Date (required)**

* Term: otgevents:date
* Equivalent property: dcterms:date
* Data type: Timestamp or Interval
* Description: Date of event being described.
* Usage: If the date of the event is not explicitly indicated by the document, supply an estimated date or date range based on context. Use in conjunction with Date Certainty to provide more information about the certainty of the supplied date.
* Input: Single

#### **Date Certainty**

* Term: otgevents:dataCertainty
* Equivalent property:
* Data Custom Vocabulary: Certainty
* Description: An indicator of the confidence or certainty of the date.
* Usage: Select from a controlled vocabulary to indicate the certainty of the date of the event.
* Input: Single

#### **Location**&#x20;

* Term: otgevents:location
* Equivalent property: schema:location
* Data type: Omeka S Item or URI or Text
* Description: The location of the event being described.&#x20;
* Usage: Can be general. Omeka S Item or URI are preferred data types.
* Input: Multiple

#### **Preceding Event**

* Term: otgevents:precedingEvent
* Equivalent Property: bio:precedingEvent
* Data type: Text or Omeka S Item
* Description: A significant event that preceded the one being described.
* Usage: May be a narrative explanation or a link to another event.
* Input: Multiple

#### **Following Event**

* Term: otgevents:followingEvent
* Equivalent property: bio:followingEvent
* Data type: Text or Omeka S Item
* Description: A significant event that occurred after the one being described.
* Usage: May be a narrative explanation or a link to another event.
* Input: Multiple

#### **Source (required)**

* Term: otgevents:source
* Equivalent property: dcterms:source
* Data type: Omeka S Item or URI or Text
* Description: The archival document from which the record information is drawn.&#x20;
* Usage: Link to the digitized document or the finding aid if available. If not, input a bibliography citation.
* Input: Multiple

#### **Related Event**

* Term: otgevents:relatedEvent
* Equivalent property: dcterms:relation
* Data type: Omeka S Item or URI
* Description: An event that is related to the one being described.
* Usage:
* Input: Multiple

#### Relation

* Term :otgevents:relation
* Equivalent property: dcterms:relation
* Data type: Omeka S Item or URI
* Description: A related resource
* Usage:&#x20;
* Input: Multiple
