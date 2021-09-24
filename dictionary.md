Participant.tsv could/should include the following  
(each time, we need a reference, explanation why this matters)

participant_ID
Gender  
Handedness (for example using Edinburgh Handedness Inventory, range -1 [left] to 1 [right]) 
  
Age at scanning    
Age of radiological diagnosis  
Estimated age of 1st symptomes  
RANO score https://radiopaedia.org/articles/rano-criteria-for-glioblastoma  
KPS https://virtualtrials.com/karnofsky.cfm  
  
Tumour histopathology WHO 2007  
Tumour grade  
Tumour molecular classification WHO 2021 ([Louis et al. (2021). The WHO 2021 Clasification of Tumours of the central nervous system:a summary. Neuro-Oncology, 23, 1231-1251](https://doi.org/10.1093/neuonc/noab106))  

Tumour volume (for example calculated from tumour lesion mask)  
Tumour location in [x,y,z] coordinate mm mni space  
resection none full or partial resection  
pre-surgical interventions chemotherapy/radiotherapy  
overall survival time in weeks from radio diagnosis to death  
progression free survival time in weeks from radio diagnosis to 1st recurrence  
follow-up time time in weeks from radio diagnosis to last data collection if no death  

  
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
