#  Graphical representation


__Diagram__




[![Image:CommunicationEvent.jpg](./CommunicationEvent.jpg)](../Image/CommunicationEvent.jpg.md "Image:CommunicationEvent.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  CommunicationEvent |
|  Submitted by: | [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist") |
|  Also Known As: |  |
|  Intent: |  To model communication events, such as phone calls, e-mails and meetings, their involved parties and the roles and relations of the parties in the context of the communication events. |
|  Domains: | [Organization](../Community/Organization.md "Community:Organization"), [Business](../Community/Business.md "Community:Business"), [Planning](../Community/Planning.md "Community:Planning"), [Participation](../Participation/Participation.md "Community:Participation"), [Product development](../Community/Product_development.md "Community:Product development") |
|  Competency Questions: | <li> What is the status of this event?</li><li> What is the purpose of this communication?</li><li> What are the valid contact mechanisms for this communication?</li><li> What roles did the different parties have in this communication event?</li><li> What are the roles of the parties involved in this relationship?</li><li> What was the contact mechanism used for this comunication?</li><li> When did this communication event take place?</li><li> In what reltionship context did this communication take place?</li> |
|  Solution description: |  The pattern introduces a specialization of the participation pattern, where parties hold different roles when participating in communication events. |
|  Reusable OWL Building Block: | [http://www.ontology.se/odp/content/owl/CommunicationEvent.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontology.se/odp/content/owl/CommunicationEvent.owl&message=OWL building block&from_page_id=2715&update=) (827) |
|  Consequences: |  Pattern includes a set of standard communication mechanisms, but can be extended., The pattern does not take into account time-indexed participation in relationships, nor time-indexed participation in communication events. All parties are assumed to participate during the whole duration of relationships and events. |
|  Scenarios: |  A sales call between John at company x and Mary at company y took place on January 7 2009. In the call John had the role of seller and Mary the role of buyer. The call was made in the context of the long-term relation between comanies x and y, where x is the subcontractor of y. The purpose of the call was to agree on a price for a particular order item., In todays boardmeeting John was elected chairman of the meeting, and Michael was appointed to take the minutes. The meeting involved 6 people, where 5 were elected members of the board and one was an invited external party. The purpose of the meeting was to decide on the price of a new product. However, the participants did not agree so the meeting had to be suspended and will continue tomorrow. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: | <li> Data model pattern called "communication events".</li> |
|  Has Components: | <li><a href="../ParticipantRole/ParticipantRole.md" title="Submissions:ParticipantRole">Submissions:ParticipantRole</a></li><li><a href="../SmartHome_TimeInterval/SmartHome_TimeInterval.md" title="Submissions:TimeInterval">Submissions:TimeInterval</a></li> |
|  Specialization Of: | <li><a href="../ParticipantRole/ParticipantRole.md" title="Submissions:ParticipantRole">Submissions:ParticipantRole</a></li> |
|  Related CPs: |  |


  




#  Elements


_The __CommunicationEvent__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ContactMechanism__ (owl:Class) The medium for the communication. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ContactMechanism](./CommunicationEvent/ContactMechanism.md "Submissions:CommunicationEvent/ContactMechanism") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isValidContactMechanismFor__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isValidContactMechanismFor](./CommunicationEvent/isValidContactMechanismFor.md "Submissions:CommunicationEvent/isValidContactMechanismFor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CommunicationEventRole__ (owl:Class) The role that this event plays for a specific party, e.g. a conference has the role of transmitting research results for a presenter while it has the role of generating income and connections for the organizers, and generating knowledge for the participants. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CommunicationEventRole](./CommunicationEvent/CommunicationEventRole.md "Submissions:CommunicationEvent/CommunicationEventRole") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __mediumOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[mediumOf](./CommunicationEvent/mediumOf.md "Submissions:CommunicationEvent/mediumOf") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CommunicationEvent__ (owl:Class) An instance of communication, e.g. a phone call, a meeting or a conference. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CommunicationEvent](./CommunicationEvent.md "Submissions:CommunicationEvent/CommunicationEvent") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __EventDuration__ (owl:Class) The time duration of a communication event. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[EventDuration](./CommunicationEvent/EventDuration.md "Submissions:CommunicationEvent/EventDuration") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __eventStartTime__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[eventStartTime](./CommunicationEvent/eventStartTime.md "Submissions:CommunicationEvent/eventStartTime") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __RelationshipDuration__ (owl:Class) The time duration of a relationship. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[RelationshipDuration](./CommunicationEvent/RelationshipDuration.md "Submissions:CommunicationEvent/RelationshipDuration") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __relationshipStartTime__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[relationshipStartTime](./CommunicationEvent/relationshipStartTime.md "Submissions:CommunicationEvent/relationshipStartTime") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PartyRole__ (owl:Class) The role of a party in a relationship, e.g. in a sales relationship one party has the customer role and the other party the provider role. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PartyRole](./CommunicationEvent/CommunicationEventPartyRole.md "Submissions:CommunicationEvent/PartyRole") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __RelationshipPartyRole__ (owl:Class) The role of a specific party in a relationship, e.g. in this particular buyer-seller relationship company x is the seller. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[RelationshipPartyRole](./CommunicationEvent/RelationshipPartyRole.md "Submissions:CommunicationEvent/RelationshipPartyRole") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __roleInRelationship__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[roleInRelationship](./CommunicationEvent/roleInRelationship.md "Submissions:CommunicationEvent/roleInRelationship") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PartyRelationship__ (owl:Class) An event in the sense of a state of things, where two or more parties are involved through different roles, e.g. a buyer-seller relation. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PartyRelationship](./CommunicationEvent/PartyRelationship.md "Submissions:CommunicationEvent/PartyRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesCommunication__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesCommunication](./CommunicationEvent/includesCommunication.md "Submissions:CommunicationEvent/includesCommunication") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __relationshipIncludes__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[relationshipIncludes](./CommunicationEvent/relationshipIncludes.md "Submissions:CommunicationEvent/relationshipIncludes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __relationshipHasDuration__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[relationshipHasDuration](./CommunicationEvent/relationshipHasDuration.md "Submissions:CommunicationEvent/relationshipHasDuration") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __EmailCommunication__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[EmailCommunication](./CommunicationEvent/EmailCommunication.md "Submissions:CommunicationEvent/EmailCommunication") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __throughMedium__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[throughMedium](./CommunicationEvent/throughMedium.md "Submissions:CommunicationEvent/throughMedium") page_
__e-mail__ ([http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism")) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[e-mail](./CommunicationEvent/e-mail.md "Submissions:CommunicationEvent/e-mail") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PhoneCommunication__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PhoneCommunication](./CommunicationEvent/PhoneCommunication.md "Submissions:CommunicationEvent/PhoneCommunication") page_
__phone__ ([http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism")) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[phone](./CommunicationEvent/phone.md "Submissions:CommunicationEvent/phone") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CommunicationPurpose__ (owl:Class) The purpose or goal of the communciation event. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CommunicationPurpose](./CommunicationEvent/CommunicationPurpose.md "Submissions:CommunicationEvent/CommunicationPurpose") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __purposeOfEvent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[purposeOfEvent](./CommunicationEvent/purposeOfEvent.md "Submissions:CommunicationEvent/purposeOfEvent") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __WebSiteCommunication__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[WebSiteCommunication](./CommunicationEvent/WebSiteCommunication.md "Submissions:CommunicationEvent/WebSiteCommunication") page_
__web-site__ ([http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism")) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[web-site](./CommunicationEvent/web-site.md "Submissions:CommunicationEvent/web-site") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __FaceToFaceCommunication__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[FaceToFaceCommunication](./CommunicationEvent/FaceToFaceCommunication.md "Submissions:CommunicationEvent/FaceToFaceCommunication") page_
__face-to-face__ ([http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism")) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[face-to-face](./CommunicationEvent/face-to-face.md "Submissions:CommunicationEvent/face-to-face") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __roleOfParty__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[roleOfParty](./CommunicationEvent/roleOfParty.md "Submissions:CommunicationEvent/roleOfParty") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __partyParticipating__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[partyParticipating](./CommunicationEvent/partyParticipating.md "Submissions:CommunicationEvent/partyParticipating") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __inRelationship__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[inRelationship](./CommunicationEvent/inRelationship.md "Submissions:CommunicationEvent/inRelationship") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Party__ (owl:Class) A physical or juridical party, e.g. person or organization. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Party](./CommunicationEvent/Party.md "Submissions:CommunicationEvent/Party") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __partyInvolvedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[partyInvolvedIn](./CommunicationEvent/partyInvolvedIn.md "Submissions:CommunicationEvent/partyInvolvedIn") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CommunicationEventPartyRole__ (owl:Class) The role of a specific party for a specific communciation event, e.g. in this particular meeting John is the chairman. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CommunicationEventPartyRole](./CommunicationEvent/CommunicationEventPartyRole.md "Submissions:CommunicationEvent/CommunicationEventPartyRole") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __partyInRelationship__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[partyInRelationship](./CommunicationEvent/partyInRelationship.md "Submissions:CommunicationEvent/partyInRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasValidContactMechanism__ (owl:ObjectProperty) Relates roles of communication events to their valid mediums, e.g. it may only be allowed to send contracts by letter or fax but not e-mail. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasValidContactMechanism](./CommunicationEvent/hasValidContactMechanism.md "Submissions:CommunicationEvent/hasValidContactMechanism") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __eventRoleIncludedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[eventRoleIncludedIn](./CommunicationEvent/eventRoleIncludedIn.md "Submissions:CommunicationEvent/eventRoleIncludedIn") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __LetterCorrespondence__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[LetterCorrespondence](./CommunicationEvent/LetterCorrespondence.md "Submissions:CommunicationEvent/LetterCorrespondence") page_
__letter__ ([http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism")) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[letter](./CommunicationEvent/letter.md "Submissions:CommunicationEvent/letter") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __FaxCommunication__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[FaxCommunication](./CommunicationEvent/FaxCommunication.md "Submissions:CommunicationEvent/FaxCommunication") page_
__fax__ ([http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism")) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[fax](./CommunicationEvent/fax.md "Submissions:CommunicationEvent/fax") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __roleOfEvent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[roleOfEvent](./CommunicationEvent/roleOfEvent.md "Submissions:CommunicationEvent/roleOfEvent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __partyInEvent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[partyInEvent](./CommunicationEvent/partyInEvent.md "Submissions:CommunicationEvent/partyInEvent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __inCommunicationEvent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[inCommunicationEvent](./CommunicationEvent/inCommunicationEvent.md "Submissions:CommunicationEvent/inCommunicationEvent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __eventIncludes__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[eventIncludes](./CommunicationEvent/eventIncludes.md "Submissions:CommunicationEvent/eventIncludes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __communicationHasSetting__ (owl:ObjectProperty) All communications take place within some relationship between parties, e.g. a sales call takes place within the relationship with a prospective customer. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[communicationHasSetting](./CommunicationEvent/communicationHasSetting.md "Submissions:CommunicationEvent/communicationHasSetting") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __eventHasPurpose__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[eventHasPurpose](./CommunicationEvent/eventHasPurpose.md "Submissions:CommunicationEvent/eventHasPurpose") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __eventHasDuration__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[eventHasDuration](./CommunicationEvent/eventHasDuration.md "Submissions:CommunicationEvent/eventHasDuration") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasEventStatus__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasEventStatus](./CommunicationEvent/hasEventStatus.md "Submissions:CommunicationEvent/hasEventStatus") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CommunicationEventStatus__ (owl:Class) The status of an event, e.g. suspended, started, ongoing, planned, proposed. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CommunicationEventStatus](./CommunicationEvent/CommunicationEventStatus.md "Submissions:CommunicationEvent/CommunicationEventStatus") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __statusOfEvent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[statusOfEvent](./CommunicationEvent/statusOfEvent.md "Submissions:CommunicationEvent/statusOfEvent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDurationOfEvent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDurationOfEvent](./CommunicationEvent/isDurationOfEvent.md "Submissions:CommunicationEvent/isDurationOfEvent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDurationOfRelationship__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDurationOfRelationship](./CommunicationEvent/isDurationOfRelationship.md "Submissions:CommunicationEvent/isDurationOfRelationship") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __relationshipEndTime__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[relationshipEndTime](./CommunicationEvent/relationshipEndTime.md "Submissions:CommunicationEvent/relationshipEndTime") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __eventEndTime__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[eventEndTime](./CommunicationEvent/eventEndTime.md "Submissions:CommunicationEvent/eventEndTime") page_
#  Additional information


#  Scenarios



__Scenarios about CommunicationEvent__
No scenario is added to this Content OP.




#  Reviews



__Reviews about CommunicationEvent__


| Review article | [Posted on](../Property/CreationDate.md "Property:CreationDate") | [About revision (current is 10036)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion") |
| --- | --- | --- |
| [EvaBlomqvist about CommunicationEvent](../Reviews/EvaBlomqvist_about_CommunicationEvent.md "Reviews:EvaBlomqvist about CommunicationEvent") | 24554466 September 2010 | 1003610,036 |


This revision (revision ID __10036__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CommunicationEvent&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CommunicationEvent&action=evaluation")




  




#  Modeling issues



__Modeling issues about CommunicationEvent__
There is no Modeling issue related to this proposal.




  




#  References