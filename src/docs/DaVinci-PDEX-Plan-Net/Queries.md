---
title: Queries
---

# DaVinci PDEX Plan Net API Query Examples
## Practitioner
##### Queries to get Practitioner entity with connected entities(PractitionerRole, Organization, Network, Location, Healthcare Service) by practitioner name, practitioner active flag and organization name

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService)

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true)

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA)

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS)

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS&practitionerNetwork=MLTC](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS&practitionerNetwork=MLTC)

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS&practitionerNetwork=MLTC&practitionerSpecialty=PHYSICAL%20THERAPY](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS&practitionerNetwork=MLTC&practitionerSpecialty=PHYSICAL%20THERAPY)

[https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS&practitionerNetwork=MLTC&practitionerSpecialty=PHYSICAL%20THERAPY&practitionerType=SPECIALISTS](https://fhir.villagecare.org/PractitionerRole?\_include=PractitionerRole:organization,PractitionerRole:practitioner,PractitionerRole:network,PractitionerRole:location,PractitionerRole:healthcareService&practitionerActive=true&practitionerName=COSTA%20DANIELA&organizationName=FITNESS&practitionerNetwork=MLTC&practitionerSpecialty=PHYSICAL%20THERAPY&practitionerType=SPECIALISTS)
____

## Organization
##### Queries to get Organization entity with connected entities(Organization Affiliation, Network) by organization name and organization active flag

[https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service](https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service)

[https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true](https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true)

[https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH](https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH)

[https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH&organizationNetwork=MAP](https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH&organizationNetwork=MAP)

[https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH&organizationNetwork=MAP&organizationType=ANCILLARY](https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH&organizationNetwork=MAP&organizationType=ANCILLARY)

[https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH&organizationNetwork=MAP&organizationType=ANCILLARY&organizationSpecialty=HOME%20HEALTH%20AIDE](https://fhir.villagecare.org/OrganizationAffiliation?\_include=OrganizationAffiliation:organization,OrganizationAffiliation:network,OrganizationAffiliation:location,OrganizationAffiliation:service&organizationActive=true&organizationName=INTERGEN%20HEALTH&organizationNetwork=MAP&organizationType=ANCILLARY&organizationSpecialty=HOME%20HEALTH%20AIDE)
____

## Pharmacy
##### Queries to get Pharmacy organization entity with connected entities(Healthcare service, Location) by pharmacy name and pharmacy active flag

[https://fhir.villagecare.org/HealthcareService?\_include=HealthcareService:organization,HealthcareService:location&organizationType=pharmacy](https://fhir.villagecare.org/HealthcareService?\_include=HealthcareService:organization,HealthcareService:location&organizationType=pharmacy)

[https://fhir.villagecare.org/HealthcareService?\_include=HealthcareService:organization,HealthcareService:location&organizationType=pharmacy&organizationActive=true](https://fhir.villagecare.org/HealthcareService?\_include=HealthcareService:organization,HealthcareService:location&organizationType=pharmacy&organizationActive=true)

[https://fhir.villagecare.org/HealthcareService?\_include=HealthcareService:organization,HealthcareService:location&organizationType=pharmacy&organizationActive=true&organizationName=STARSIDE%20DRUGS](https://fhir.villagecare.org/HealthcareService?\_include=HealthcareService:organization,HealthcareService:location&organizationType=pharmacy&organizationActive=true&organizationName=STARSIDE%20DRUGS)
