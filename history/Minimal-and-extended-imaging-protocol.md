# What are the useful imaging sequences and associated metadata?

from the wiki: https://github.com/EN-Brain-Imaging-of-Tumours/doc/wiki/Minimal-and-extended-imaging-protocol

## Minimal structural imaging protocol

Following clinical recommendations: 
* T1w -/+ contrast enhancement (resolution 1mm^3)
* T2w (resolution 1mm^3)
* FLAIR (resolution 1mm^3)
* DWI (resolution 3mm tra)
* DSC perfusion (resolution 3-6mm tra)

If possible, anatomic images should be 3D and isotropic, whilst non-3D images should be planned along the AC-PC line. In any case, there should be no gap between slices.

## Behavioural data

Along with structural imaging, it is interesting to share behavioural data to further understand i) anatomo-functional relationships and ii) changes pre/post treatment.
* clinical assessment
* neuropsychological assessment

(Existing protocols from partner centers to be gathered)

## Extended protocol

If the patient can tolerate it, and depending on utility for treatments, additional imaging can be gathered:
* DTI for structural connectivity, the minimum number of directions is 32
* SWI / T2*
* resting state fMRI
* [task fMRI](https://github.com/EN-Brain-Imaging-of-Tumours/doc/wiki/task-fMRI-for-brain-tumour-presurgical-mapping)
* vascular response mapping (CVR) and/or hrf retrieval

(discuss evidence for each imaging protocol)

## recommended post-processing
* DTI (Motion / EC correction, non-linear / robust fitting)
* Leakage-correction for rCBV estimation (Boxerman et al.)
* fMRI tbd