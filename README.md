# Entity-Detection-in-Text


Named-entity recognition is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.


Named entity recognition (NER) helps you easily identify the key elements in a text, like names of people, places, brands, monetary values, and more. Extracting the main entities in a text helps sort unstructured data and detect important information, which is crucial if you have to deal with large datasets.


Ex:- This is a paragraph of text:-
     ("Google LLC is an American multinational technology company that specializes in Internet-related services and products, which include online advertising technologies, a search engine, cloud computing, software, and hardware. It is considered one of the Big Five technology companies in the U.S. information technology industry, alongside Amazon, Facebook, Apple, and Microsoft. Google was founded in September 1998 by Larry Page and Sergey Brin while they were Ph.D. students at Stanford University in California. Together they own about 14 percent of its shares and control 56 percent of the stockholder voting power through supervoting stock. They incorporated Google as a California privately held company on September 4, 1998. Google was then reincorporated in Delaware on October 22, 2002.")
     
 With the help of Natural Language Processing detecting entity and type from the above paragraph.
 
Entity        Type

Google        ORG
September 1998  DATE
Larry Page    PERSON
Sergey Brin   PERSON
Ph.D.         WORK_OF_ART
Stanford University  ORG
California    GPE
about 14 percent  PERCENT
56 percent    PERCENT
Google        ORG
California    GPE
September 4, 1998  DATE
Google        ORG
Delaware      GPE
October 22, 2002  DATE


So, Full named-entity recognition is often broken down, conceptually and possibly also in implementations, as two distinct problems: detection of names, and classification of the names by the type of entity they refer to (e.g. person, organization, location and other). The first phase is typically simplified to a segmentation problem: names are defined to be contiguous spans of tokens, with no nesting, so that "Bank of America" is a single name, disregarding the fact that inside this name, the substring "America" is itself a name. This segmentation problem is formally similar to chunking. The second phase requires choosing an ontology by which to organize categories of things. 
