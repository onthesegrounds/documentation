# Description of Primary Enslaved Participant

The following properties are intended to capture information about enslaved participants within the context of a specific event (for example, a person's freedom status or age at the time of the event being described). For characteristics that describe people but are not event-dependent (such as birth date or familial relationships), see [Person Record Properties](https://docs.google.com/document/d/1HwTODfL6w3gcKLb93SkUmsUPA32pXTnfg4HH-ndXg3Y/edit#heading=h.rvvd4c7lpluv).

P**rimary Participant**

* Term: otgevents:principal
* Equivalent property: bio:principal
* Data type: Omeka S Item or Text&#x20;
* Description: The primary person who is involved in the event.
* Usage: Link to the Person record for the primary enslaved participant. If no record exists, use the text input to specify participants.&#x20;
* Input: Single

#### **Primary Participant Description**

* Term: otgevents:primaryParticipantDescription
* Equivalent property:
* Data type: Text
* Description: A description of the primary participant in the event.
* Usage: Verbatim description from the archival source that describes the physical characteristics of the person in any way.
* Input: Multiple
* Rationale: This property is included in lieu of having a property in the Person record that designates race. It is a recognition that phenotypic descriptions change over time and that different archival materials may describe a person in vastly different ways.&#x20;

#### **Freedom Status**

* Term: otgevents:freedomStatus
* Equivalent property:
* Data type: Custom Vocabulary: Freedom Status
* Description: An indication of the freedom status of the primary participant in the event at the time of the event.
* Usage: Select from a controlled vocabulary to indicate the enslavement status of the primary participant at the time of the event.
* Input: Single

#### **Enslaver**

* Term: otgevents:enslaver
* Equivalent property:
* Data type: Omeka S Item or Text or URI
* Description: The person or institution responsible for holding in slavery the primary particpant in the event.&#x20;
* Usage: Omeka S Item or URI are preferred data types.
* Input: Multiple

#### **Age**

* Term: otgevents:age
* Equivalent property: bio:age
* Data type: Integer or Text
* Description: The age of the primary participant at the time of the event.
* Usage:&#x20;
* Input: Single

###
