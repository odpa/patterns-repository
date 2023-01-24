# 

 Graphical representation



__Diagram__ 





[![Image:CommunicationEvent.jpg](../images/a/aa/CommunicationEvent.jpg)](../Image/CommunicationEvent.jpg "Image:CommunicationEvent.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  CommunicationEvent  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  To model communication events, such as phone calls, e-mails and meetings, their involved parties and the roles and relations of the parties in the context of the communication events.  |
|  Domains:  | [Organization](../Community/Organization "Community:Organization")  , [Business](../Community/Business "Community:Business")  , [Planning](../Community/Planning "Community:Planning")  , [Participation](../Community/Participation "Community:Participation")  , [Product development](../Community/Product_development "Community:Product development")  |
|  Competency Questions:  | <li>       What is the status of this event?      </li><li>       What is the purpose of this communication?      </li><li>       What are the valid contact mechanisms for this communication?      </li><li>       What roles did the different parties have in this communication event?      </li><li>       What are the roles of the parties involved in this relationship?      </li><li>       What was the contact mechanism used for this comunication?      </li><li>       When did this communication event take place?      </li><li>       In what reltionship context did this communication take place?      </li> |
|  Solution description:  |  The pattern introduces a specialization of the participation pattern, where parties hold different roles when participating in communication events.  |
|  Reusable OWL Building Block:  | [http://www.ontology.se/odp/content/owl/CommunicationEvent.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontology.se/odp/content/owl/CommunicationEvent.owl&message=OWL building block&from_page_id=2715&update=)  (827)  |
|  Consequences:  |  Pattern includes a set of standard communication mechanisms, but can be extended., The pattern does not take into account time-indexed participation in relationships, nor time-indexed participation in communication events. All parties are assumed to participate during the whole duration of relationships and events.  |
|  Scenarios:  |  A sales call between John at company x and Mary at company y took place on January 7 2009. In the call John had the role of seller and Mary the role of buyer. The call was made in the context of the long-term relation between comanies x and y, where x is the subcontractor of y. The purpose of the call was to agree on a price for a particular order item., In todays boardmeeting John was elected chairman of the meeting, and Michael was appointed to take the minutes. The meeting involved 6 people, where 5 were elected members of the board and one was an invited external party. The purpose of the meeting was to decide on the price of a new product. However, the participants did not agree so the meeting had to be suspended and will continue tomorrow.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li>       Data model pattern called "communication events".      </li> |
|  Has Components:  | <li><a href="Submissions%253AParticipantRole.html" title="Submissions:ParticipantRole">        Submissions:ParticipantRole       </a></li><li><a href="Submissions%253ATimeInterval.html" title="Submissions:TimeInterval">        Submissions:TimeInterval       </a></li> |
|  Specialization Of:  | <li><a href="Submissions%253AParticipantRole.html" title="Submissions:ParticipantRole">        Submissions:ParticipantRole       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __CommunicationEvent__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ContactMechanism__ 
 (owl:Class) The medium for the communication.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ContactMechanism](../Submissions/CommunicationEvent/ContactMechanism "Submissions:CommunicationEvent/ContactMechanism") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isValidContactMechanismFor__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isValidContactMechanismFor](../Submissions/CommunicationEvent/isValidContactMechanismFor "Submissions:CommunicationEvent/isValidContactMechanismFor") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CommunicationEventRole__ 
 (owl:Class) The role that this event plays for a specific party, e.g. a conference has the role of transmitting research results for a presenter while it has the role of generating income and connections for the organizers, and generating knowledge for the participants.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CommunicationEventRole](../Submissions/CommunicationEvent/CommunicationEventRole "Submissions:CommunicationEvent/CommunicationEventRole") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__mediumOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[mediumOf](../Submissions/CommunicationEvent/mediumOf "Submissions:CommunicationEvent/mediumOf") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CommunicationEvent__ 
 (owl:Class) An instance of communication, e.g. a phone call, a meeting or a conference.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CommunicationEvent](../Submissions/CommunicationEvent/CommunicationEvent "Submissions:CommunicationEvent/CommunicationEvent") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EventDuration__ 
 (owl:Class) The time duration of a communication event.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EventDuration](../Submissions/CommunicationEvent/EventDuration "Submissions:CommunicationEvent/EventDuration") 
 page_ 



[![DatatypeProperty](../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__eventStartTime__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventStartTime](../Submissions/CommunicationEvent/eventStartTime "Submissions:CommunicationEvent/eventStartTime") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__RelationshipDuration__ 
 (owl:Class) The time duration of a relationship.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[RelationshipDuration](../Submissions/CommunicationEvent/RelationshipDuration "Submissions:CommunicationEvent/RelationshipDuration") 
 page_ 



[![DatatypeProperty](../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__relationshipStartTime__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[relationshipStartTime](../Submissions/CommunicationEvent/relationshipStartTime "Submissions:CommunicationEvent/relationshipStartTime") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PartyRole__ 
 (owl:Class) The role of a party in a relationship, e.g. in a sales relationship one party has the customer role and the other party the provider role.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PartyRole](../Submissions/CommunicationEvent/PartyRole "Submissions:CommunicationEvent/PartyRole") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__RelationshipPartyRole__ 
 (owl:Class) The role of a specific party in a relationship, e.g. in this particular buyer-seller relationship company x is the seller.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[RelationshipPartyRole](../Submissions/CommunicationEvent/RelationshipPartyRole "Submissions:CommunicationEvent/RelationshipPartyRole") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__roleInRelationship__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[roleInRelationship](../Submissions/CommunicationEvent/roleInRelationship "Submissions:CommunicationEvent/roleInRelationship") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PartyRelationship__ 
 (owl:Class) An event in the sense of a state of things, where two or more parties are involved through different roles, e.g. a buyer-seller relation.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PartyRelationship](../Submissions/CommunicationEvent/PartyRelationship "Submissions:CommunicationEvent/PartyRelationship") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__includesCommunication__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[includesCommunication](../Submissions/CommunicationEvent/includesCommunication "Submissions:CommunicationEvent/includesCommunication") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__relationshipIncludes__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[relationshipIncludes](../Submissions/CommunicationEvent/relationshipIncludes "Submissions:CommunicationEvent/relationshipIncludes") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__relationshipHasDuration__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[relationshipHasDuration](../Submissions/CommunicationEvent/relationshipHasDuration "Submissions:CommunicationEvent/relationshipHasDuration") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EmailCommunication__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EmailCommunication](../Submissions/CommunicationEvent/EmailCommunication "Submissions:CommunicationEvent/EmailCommunication") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__throughMedium__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[throughMedium](../Submissions/CommunicationEvent/throughMedium "Submissions:CommunicationEvent/throughMedium") 
 page_ 



__e-mail__ 
 (
 [http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism") 
 )
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[e-mail](../Submissions/CommunicationEvent/e-mail "Submissions:CommunicationEvent/e-mail") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PhoneCommunication__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PhoneCommunication](../Submissions/CommunicationEvent/PhoneCommunication "Submissions:CommunicationEvent/PhoneCommunication") 
 page_ 



__phone__ 
 (
 [http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism") 
 )
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[phone](../Submissions/CommunicationEvent/phone "Submissions:CommunicationEvent/phone") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CommunicationPurpose__ 
 (owl:Class) The purpose or goal of the communciation event.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CommunicationPurpose](../Submissions/CommunicationEvent/CommunicationPurpose "Submissions:CommunicationEvent/CommunicationPurpose") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__purposeOfEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[purposeOfEvent](../Submissions/CommunicationEvent/purposeOfEvent "Submissions:CommunicationEvent/purposeOfEvent") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__WebSiteCommunication__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[WebSiteCommunication](../Submissions/CommunicationEvent/WebSiteCommunication "Submissions:CommunicationEvent/WebSiteCommunication") 
 page_ 



__web-site__ 
 (
 [http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism") 
 )
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[web-site](../Submissions/CommunicationEvent/web-site "Submissions:CommunicationEvent/web-site") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FaceToFaceCommunication__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FaceToFaceCommunication](../Submissions/CommunicationEvent/FaceToFaceCommunication "Submissions:CommunicationEvent/FaceToFaceCommunication") 
 page_ 



__face-to-face__ 
 (
 [http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism") 
 )
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[face-to-face](../Submissions/CommunicationEvent/face-to-face "Submissions:CommunicationEvent/face-to-face") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__roleOfParty__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[roleOfParty](../Submissions/CommunicationEvent/roleOfParty "Submissions:CommunicationEvent/roleOfParty") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__partyParticipating__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[partyParticipating](../Submissions/CommunicationEvent/partyParticipating "Submissions:CommunicationEvent/partyParticipating") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__inRelationship__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[inRelationship](../Submissions/CommunicationEvent/inRelationship "Submissions:CommunicationEvent/inRelationship") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Party__ 
 (owl:Class) A physical or juridical party, e.g. person or organization.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Party](../Submissions/CommunicationEvent/Party "Submissions:CommunicationEvent/Party") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__partyInvolvedIn__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[partyInvolvedIn](../Submissions/CommunicationEvent/partyInvolvedIn "Submissions:CommunicationEvent/partyInvolvedIn") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CommunicationEventPartyRole__ 
 (owl:Class) The role of a specific party for a specific communciation event, e.g. in this particular meeting John is the chairman.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CommunicationEventPartyRole](../Submissions/CommunicationEvent/CommunicationEventPartyRole "Submissions:CommunicationEvent/CommunicationEventPartyRole") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__partyInRelationship__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[partyInRelationship](../Submissions/CommunicationEvent/partyInRelationship "Submissions:CommunicationEvent/partyInRelationship") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasValidContactMechanism__ 
 (owl:ObjectProperty) Relates roles of communication events to their valid mediums, e.g. it may only be allowed to send contracts by letter or fax but not e-mail.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasValidContactMechanism](../Submissions/CommunicationEvent/hasValidContactMechanism "Submissions:CommunicationEvent/hasValidContactMechanism") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__eventRoleIncludedIn__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventRoleIncludedIn](../Submissions/CommunicationEvent/eventRoleIncludedIn "Submissions:CommunicationEvent/eventRoleIncludedIn") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__LetterCorrespondence__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[LetterCorrespondence](../Submissions/CommunicationEvent/LetterCorrespondence "Submissions:CommunicationEvent/LetterCorrespondence") 
 page_ 



__letter__ 
 (
 [http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism") 
 )
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[letter](../Submissions/CommunicationEvent/letter "Submissions:CommunicationEvent/letter") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FaxCommunication__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FaxCommunication](../Submissions/CommunicationEvent/FaxCommunication "Submissions:CommunicationEvent/FaxCommunication") 
 page_ 



__fax__ 
 (
 [http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism](http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism "http://www.ontology.se/odp/content/owl/CommunicationEvent#ContactMechanism") 
 )
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[fax](../Submissions/CommunicationEvent/fax "Submissions:CommunicationEvent/fax") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__roleOfEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[roleOfEvent](../Submissions/CommunicationEvent/roleOfEvent "Submissions:CommunicationEvent/roleOfEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__partyInEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[partyInEvent](../Submissions/CommunicationEvent/partyInEvent "Submissions:CommunicationEvent/partyInEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__inCommunicationEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[inCommunicationEvent](../Submissions/CommunicationEvent/inCommunicationEvent "Submissions:CommunicationEvent/inCommunicationEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__eventIncludes__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventIncludes](../Submissions/CommunicationEvent/eventIncludes "Submissions:CommunicationEvent/eventIncludes") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__communicationHasSetting__ 
 (owl:ObjectProperty) All communications take place within some relationship between parties, e.g. a sales call takes place within the relationship with a prospective customer.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[communicationHasSetting](../Submissions/CommunicationEvent/communicationHasSetting "Submissions:CommunicationEvent/communicationHasSetting") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__eventHasPurpose__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventHasPurpose](../Submissions/CommunicationEvent/eventHasPurpose "Submissions:CommunicationEvent/eventHasPurpose") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__eventHasDuration__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventHasDuration](../Submissions/CommunicationEvent/eventHasDuration "Submissions:CommunicationEvent/eventHasDuration") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventStatus__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventStatus](../Submissions/CommunicationEvent/hasEventStatus "Submissions:CommunicationEvent/hasEventStatus") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CommunicationEventStatus__ 
 (owl:Class) The status of an event, e.g. suspended, started, ongoing, planned, proposed.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CommunicationEventStatus](../Submissions/CommunicationEvent/CommunicationEventStatus "Submissions:CommunicationEvent/CommunicationEventStatus") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__statusOfEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[statusOfEvent](../Submissions/CommunicationEvent/statusOfEvent "Submissions:CommunicationEvent/statusOfEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isDurationOfEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDurationOfEvent](../Submissions/CommunicationEvent/isDurationOfEvent "Submissions:CommunicationEvent/isDurationOfEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isDurationOfRelationship__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDurationOfRelationship](../Submissions/CommunicationEvent/isDurationOfRelationship "Submissions:CommunicationEvent/isDurationOfRelationship") 
 page_ 



[![DatatypeProperty](../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__relationshipEndTime__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[relationshipEndTime](../Submissions/CommunicationEvent/relationshipEndTime "Submissions:CommunicationEvent/relationshipEndTime") 
 page_ 



[![DatatypeProperty](../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__eventEndTime__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventEndTime](../Submissions/CommunicationEvent/eventEndTime "Submissions:CommunicationEvent/eventEndTime") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about CommunicationEvent__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about CommunicationEvent__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 10036)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [EvaBlomqvist about CommunicationEvent](../Reviews/EvaBlomqvist_about_CommunicationEvent "Reviews:EvaBlomqvist about CommunicationEvent")  |  2455446  6 September 2010  |  10036  10,036  |



 This revision (revision ID
 __10036__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CommunicationEvent&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CommunicationEvent&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about CommunicationEvent__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References