# bl
bibliographic data from the British Library (BL)

The example provided here was generated from MARC 21 bibliographic record (014469082) viewable in our online catalogue here: 
http://explore.bl.uk/primo_library/libweb/action/search.do?vid=BLVU1&fn=search&vl(freeText0)=014469082 

It has been transformed according to the data model illustrated here:
http://www.bl.uk/bibliographic/pdfs/bldatamodelbook.pdf

Three things to bear in mind:
1. We have not FRBRized at this stage; our bibliographic resource corresponds to a composite W-E-M to use FRBR terminology.
2. We have no access to authority data when transforming the data; all information relating to entities such as persons, organizations, etc. is generated from each bibliographic record
3. Use of foaf:focus. The model makes extensive use of the foaf:focus property to relate the "thing" as a concept to its corresponding "thing" as RWO. The model assumes that entities are RWOs; consequently the entity as concept is only generated when it appears as a subject (6XX) in the MARC bibliographic record. The file TolkienJRR(JohnRonaldReuel)1892-1973_concept.ttl is provided for illustration of how a Person as concept is described; it is not generated for the particular example provided.

Further information about the Linked Open BNB is available here: http://bnb.data.bl.uk/docs
