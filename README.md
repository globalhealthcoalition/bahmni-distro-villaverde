![alt tag](readme/GHC_and_flag_banner.png)
# Bahmni Villa Verde distribution

_A community health clinic distribution to support standardized terminology, clinical processes, and reporting analytics at the mobile clinic of Villa Verde, Dominican Republic_

-----

This repository maintains the 'distro POM' for Global Health Coalition's Bahmni distribution in use at the Villa Verde mobile clinic, Dominican Republic.
It downloads and brings in one place all artifacts needed by the distribution, simply run:
```
mvn clean package
```
### Target inventory:

* `bahmni_emr/`
<br/>The target version of the front-end apps that makes 'Bahmni EMR'.
* `bahmni_config/`
<br/>The bespoke Bahmni configuration (more [here](https://github.com/globalhealthcoalition/bahmni-config-villaverde)) to be consumed by Bahmni Apps.
* `openmrs_modules/`
<br/>The required set of OpenMRS modules.
* `openmrs_config/`
<br/>The OpenMRS bespoke configuration (more [here](https://github.com/globalhealthcoalition/openmrs-config-villaverde)) to be processed by the [Initializer module](https://github.com/mekomsolutions/openmrs-module-initializer).
* `openmrs_core/`
The target version of OpenMRS Core.
