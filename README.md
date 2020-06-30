# BPDTS 34.20 Technical Test - Hussain Ashraf 

## Run tests

Instructions for setting up environment to run tests

- [Download soapUI](https://www.soapui.org/downloads/soapui/)
- Clone repository [BPDTS-technical-test-](https://github.com/MancLad89/BPDTS-technical-test-.git) from GitHub
- In soapUI import project by following `File` > `Import Project` and select `bpdts-tech-test-soapui-project.xml` from cloned repository

## Possible Improvements

- First test step to query `/users` to obtain `longitude` and `latitude` of a random user to a location instead of current hardcoded to London
- Assert `/city/{city}/users` only returns users to specified city
- Assert `/user/{id}` only returns one user
- Test for invalid scenarios and as a minimum assert for status codes other than 200
- Assert response headers


