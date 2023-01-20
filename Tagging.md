# 

 Graphical representation



__Diagram__ 





[![Image:Tagging.png](public/images/0/00/Tagging.png)](../Image/Tagging.png "Image:Tagging.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Tagging  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent a tagging situation, in which someone uses a term, from a list of a folksonomy, to tag something (or the content of something). We might also want to represent the time and the polarity of the tagging.  |
|  Domains:  | [General](../Community/General "Community:General")  , [Web2.0](../Community/Web2.0 "Community:Web2.0")  , [DocumentManagement](../Community/DocumentManagement "Community:DocumentManagement")  |
|  Competency Questions:  | <li>       Who is tagging (the content of) what      </li><li>       by using what term from what folksonomy?      </li><li>       Which polarity has the tagging?      </li> |
|  Solution description:  |  Tagging pattern exploits the [Situation](../Submissions/Situation "Submissions:Situation")  pattern in order to encode Gruber's definition that has tagging as a relation between an agent, a tag from a folksonomy, a content tagged, a polarity.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/tagging.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/tagging.owl&message=OWL building block&from_page_id=2136&update=)  (783)  |
|  Consequences:  |  We are able to represent data about tagging activities from web 2.0 applications, from document annotation projects, or from RDFa documents.  |
|  Scenarios:  |  A Flickr picture showing a leopard, tagged with the Tag 'leopard', A Flickr picture showing a boy surfing with a sombrero hat, tagged with the Tag 'cool', A Flickr picture tagged as 'taken in Sicily'  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="Submissions%253AAgentRole.html" title="Submissions:AgentRole">        Submissions:AgentRole       </a></li><li><a href="Submissions%253ACollectionEntity.html" title="Submissions:CollectionEntity">        Submissions:CollectionEntity       </a></li><li><a href="Submissions%253AIntensionExtension.html" title="Submissions:IntensionExtension">        Submissions:IntensionExtension       </a></li> |
|  Specialization Of:  | <li><a href="Submissions%253ATimeIndexedSituation.html" title="Submissions:TimeIndexedSituation">        Submissions:TimeIndexedSituation       </a></li> |
|  Related CPs:  | <li><a href="Submissions%253ATopic.html" title="Submissions:Topic">        Submissions:Topic       </a></li> |



  





# 

 Elements



_The
 __Tagging__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__byAgent__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[byAgent](../Submissions/Tagging/byAgent "Submissions:Tagging/byAgent") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isTagUsedIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isTagUsedIn](../Submissions/Tagging/isTagUsedIn "Submissions:Tagging/isTagUsedIn") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isTaggingAgentIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isTaggingAgentIn](../Submissions/Tagging/isTaggingAgentIn "Submissions:Tagging/isTaggingAgentIn") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__usingTag__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[usingTag](../Submissions/Tagging/usingTag "Submissions:Tagging/usingTag") 
 page_ 


# 

 Additional information



 The tagging ontology drafted by Tom Gruber in FOL, and formalized here in OWL by Aldo Gangemi with pattern-based design.
A Tag is here classified as a linguistic object that is used in the context of a Tagging Situation, which also involves a (tagged) Entity, an Agent, and a Folksonomy.
 



# 

 Scenarios




__Scenarios about Tagging__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Tagging__ 


 There is no review about this proposal.
This revision (revision ID
 __9129__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Tagging&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Tagging&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Tagging__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References