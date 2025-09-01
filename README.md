# module1-codexes-claims-analysis
Source Data: https://data.cms.gov/collection/synthetic-medicare-enrollment-fee-for-service-claims-and-prescription-drug-event

Code Guide: https://www2.ccwdata.org/documents/10280/19022436/codebook-ffs-claims.pdf 

Note: Use Inpatient.csv file from csv and utilize code book for definitions

ICD CODEX: https://www.icd10data.com/


Focus codes utilized: ICD diagnosis, HCPCS, Principal Diagnosis code, Claim Admitting Diagnosis Code, Claim Inpatient Admission Type Code, Claim Source Inpatient Admission Code, NCH Patient Status Indicator Code, Claim Diagnosis Related Group Code.

See Below for descriptions of codes based on the source. 

| Focus Code | Label | Description | 
|------------|-------------| ---------------| 
|ICD Claim diagnosis Code | icd_dgns_cd1 | The diagnosis code identifying the beneficiary's diagnosis |
| HCPCS or Healthcare Common Procedure Coding System (HCPCS) Code | hcpcs_cd | Collection of codes that represent procedures, supplies, products, and services which may be provided to Medicare beneficiaries and to individuals enrolled in private health insurance programs |
| Claim Principal Diagnosis Code | principal_dgns_cd | The diagnosis code identifying the diagnosis, condition, problem, or other reason for the admission/encounter/visit shown in the medical record to be chiefly responsible for the services provided. This is also known as the first occurence of diagnosis code variable as ICD diagnosis Code 1 |
|  Claim Admitting Diagnosis Code | admit_cd | The code indicating the type and priority of an inpatient admission associated with the service on an intermediary submitted claim |
| Claim Inpatient Admission Type Code | CLM_IP_ADMSN_TYPE_CD | The code indicating the type and priority of an inpatient admission associated with the service on an intermediary submitted claim
| Claim Source Inpatient Admission Code | clm_src_ip_admsn_cd | The code indicating the source of the referral for the admission or visit |
| NCH Patient Status Indicator Code | nch_pnt_stus_ind_cd | This variable is a recoded version of the discharge status code
| Claim Diagnosis Related Group Code | clm_drg_cd | The diagnostic related group to which a hospital claim belongs for prospective payment purposes |
