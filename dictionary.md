Participant.tsv

[Age of radiological diagnosis]  
[Age at scanning]  
[Estimated age of 1st symptomes]  
[Gender]  
Handedness (for example using Edinburgh Handedness Inventory, range -1 [left] to 1 [right])  
Tumour histopathology WHO 2007  
Tumour grade  
Tumour molecular classification WHO 2016  
Tumour volume (for example calculated from tumour lesion mask)  
Tumour location in [x,y,z] coordinate mm mni space  
resection none full or partial resection  
pre-surgical interventions chemotherapy/radiotherapy  
[overall survival] time in weeks from radio diagnosis to death  
[progression free survival] time in weeks from radio diagnosis to 1st recurrence  
[follow-up time] time in weeks from radio diagnosis to last data collection if no death  
RANO score https://radiopaedia.org/articles/rano-criteria-for-glioblastoma  
KPS https://virtualtrials.com/karnofsky.cfm  
  
Standard reporting ??
 
Dataset_description.json
  
Values must be from
http://www.ontobee.org/ontology/DOID?iri=http://purl.obolibrary.org/obo/DOID_3073  

{
"tumour_histology": {
"Description": "xxxxxxxxx",
"Grade":
{ "1": "Well differentiated",
"2": "Moderately differentiated",
"3": "Poorly differentiated",
"4": "Undifferentiated"
"X": "undetermined"}
}
"tumour_genetics": {
"Database": "xxx",
}

}
