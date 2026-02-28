# CMS-1500 Analyzer Schema
Project: cms-1500-analyzer
Resource: cashafaltz-0206-resource (rg-cashafaltz-2352, East US 2)
API Version: 2025-11-01

## Fields
- InsuranceType, InsuredIdNumber, PatientName, PatientBirthDate, PatientSex
- InsuredName, PatientAddress, PatientRelationshipToInsured
- InsuredAddress, InsuredCity, InsuredState, InsuredZipCode, InsuredTelephone
- OtherInsuredName, OtherInsuredPolicyNumber
- IsPatientConditionRelatedToEmployment (Boolean)
- IsPatientConditionRelatedToAutoAccident (Boolean)
- InsurancePlanName, IsThereAnotherHealthBenefitPlan
- PatientSignature, InsuredSignature, DateOfCurrentIllness
- DatesPatientUnableToWork (Object: StartDate, EndDate)
- ReferringProviderName
- HospitalizationDates (Object: AdmissionDate, DischargeDate)
- AdditionalClaimInformation, IsOutsideLabUsed, OutsideLabCharges
- DiagnosisOrNatureOfIllness, ResubmissionCode, PriorAuthorizationNumber
- ServiceLines (List of Objects)
- FederalTaxIdNumber, PatientAccountNumber
