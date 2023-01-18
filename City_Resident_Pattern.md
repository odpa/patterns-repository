# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  City Resident Pattern  |
|  Submitted by:  | [MarkFox](../User/MarkFox "User:MarkFox")  |
|  Also Known As:  |  |
|  Intent:  |  This file defines an ontology design pattern for City "Resident.” Why is the development a Resident pattern important for the development of a city data on-tology? In the PolisGnosis project (Fox, 2017), where ontologies have been developed for measuring city performance across the 17 themes defined in ISO37120:2104 (e.g., Education, Public Safety, Health, Water & Sanitation), one of the concepts that recurs across themes is “(city) Resident”. The provisioning of city services is often contingent upon whether the person is a resident of the city. Whether it is access to swimming lessons provided by Parks and Recreation, or affordable housing provided by Shelters and Housing, many are contingent upon satisfying the residency requirement. This ontology pattern make it possible to define the semantics of residency for a city, and use the definition to automate the classification of a person as a resident or not of a city.  |
|  Domains:  | [Smart City](../Community/Smart_City "Community:Smart City")  |
|  Competency Questions:  | <li>       1.	Does the person reside in the city/country?      </li> 2. How long has the person resided in the city?  3. Is the person a citizen of the country which contains the city?  4. Does the person have a residence/home/domicile in the city?  5. If the person has more than one residence <li>       where does the person spend the most time?      </li> 6. Does the person own property or business in the city?  7. Does the person operate a business in the city?  8. Is the person an official resident of the city?  |
|  Solution description:  |  The Resident class is a subclass of Person. The properties of the Resident class are used to construct the definition of a resident for a particular city. These properties are:  • a residence property hasResidence that specifies one or more individuals of Residence, where each individual specifies a residence distinguished by city, address and/or time interval. A resident can have more than one residence;  • a citizenship property citizenOf that specifies one or more Citizenship’s, each specifying the country (Country) and time interval (time:ProperInterval) the resident is a citizen. A person can be a citizen of more than country and for different time intervals;  • an ownership property owns, that specifies zero or more ControlledEntity’s where entity’s are buildings (Building) and/or land areas (LandArea) that the resident owns; and  • a business operate property operate, that specifies zero or more ControlledEntity where the entity is an Organization that the resident operates.  The ControlledEntity and Citizenship classes are necessary to capture the time inter-val during which an entity is owned or operated, or the person is a citizen of a country.  A major part of determining whether a person is a resident of a city is the specification of where and when they have resided. The hasResidence property links a Resident to a Residence. The cardinality of the property is greater than one as over time a person may reside in more than one place/address, in the same city and/or different cities.  The Residence class specifies  • a location property forCity whose range is a single city (City),  • a time interval property time:hasTime whose range is a single time interval,  • the home type property hasHomeType whose range is a single type of home, such house, apartment, etc.,  • an address property hasAddress whose range is a single address, and  • a property hasResidentialRelationship whose range specifies whether the resident rents, owns, etc. the home.  The temporal extent of individuals of Residence can imply a total or partial ordering on the individuals, as a person may reside in more than one place at the same time.  |
|  Reusable OWL Building Block:  | [http://ontology.eil.utoronto.ca/cdm/Resident.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontology.eil.utoronto.ca/cdm/Resident.owl&message=OWL building block&from_page_id=4656&update=)  (251)  |
|  Consequences:  |  |
|  Scenarios:  |  The definition of Resident varies from city to city and country to country. We use as our use cases definitions of Resident as provided by four cities: Toronto Canada: “you are identified as a resident if you reside in, own property, or own or operate a business in Toronto” (311 Toronto). Beijing China: Beijing uses the Hukou system which is a household registration program that results in a government issued permit. Beijing residents are “all indi-viduals holding the nationality of the People’s Republic of China who [have]a domicile in Beijing and nowhere else. If the individual maintains a regular dwell-ing somewhere else, the more regular dwelling is considered their place of resi-dence” (Li, 1991). New York USA: a resident is defined by “Regulation 105.20 (d)(1)” which stipu-lates, “the place which an individual intends to be his permanent home –the place to which he intends to return. It is the home with range of sentiment, feeling and permanent association. One must be domiciled in New York and maintain a home in New York, the time spent in the State is irrelevant” (McGladrey, 2009). Germany: “a resident of Germany generally refers to an individual who has a dom-icile in Germany or spends more than six consecutive months in Germany (habitu-al place of abode)” (Seidel, 2011). As different cities have different definitions of Resident the design pattern must con-tain the properties required by each.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li></li> |
|  Extracted From:  |  |
|  Reengineered From:  | <li><a class="external free" href="http://ontology.eil.utoronto.ca/GCI/Innovation/GCI-Innovation.owl" rel="nofollow" title="http://ontology.eil.utoronto.ca/GCI/Innovation/GCI-Innovation.owl">        http://ontology.eil.utoronto.ca/GCI/Innovation/GCI-Innovation.owl       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:OWL-Time:_http://www.we.org/2006/time_icontact:_http://ontology.eil.utoronto.ca/tove/icontact.owl&amp;action=edit&amp;redlink=1" title="Submissions:OWL-Time: http://www.we.org/2006/time icontact: http://ontology.eil.utoronto.ca/tove/icontact.owl (not yet written)">        Submissions:OWL-Time: http://www.we.org/2006/time  icontact: http://ontology.eil.utoronto.ca/tove/icontact.owl       </a></li> |



  





# 

 Elements



_The
 __City Resident Pattern__ 
 Content OP locally defines the following ontology elements:_ 




# 

 Additional information



# 

 Scenarios




__Scenarios about City Resident Pattern__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about City Resident Pattern__ 


 There is no review about this proposal.
This revision (revision ID
 __13842__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:City_Resident_Pattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:City_Resident_Pattern&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about City Resident Pattern__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2020](../WOP/2020.1 "WOP:2020")  |
| --- | --- |