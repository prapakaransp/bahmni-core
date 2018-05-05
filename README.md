AppServe provides application as a service(AaS). AppServe strongly believes application development cost as O(1). It means zero development cost for applications. 

Patient care platform
Bahmni is core application for hosptial management App.


Installation steps
# OpenMRS module bahmnicore

This module provides necessary services for running Bahmni

## Build


[![Build Status](https://travis-ci.org/Bahmni/bahmni-core.svg?branch=master)](https://travis-ci.org/Bahmni/bahmni-core)

Clone the repository and build the omod
   
    git clone https://github.com/bahmni/bahmni-core
    cd bahmni-core
    mvn clean install
    
## Deploy

Copy ```bahmni-core/bahmnicore-omod/target/bahmnicore-omod-VERSION-SNAPSHOT.omod``` into OpenMRS modules directory and restart OpenMRS
