The purpose of this project is to test different stuff in CircleCI. Make sure the organization *AcmeDevOps* has been granted access in your CircleCI account, this will add an organization SSH key allowing a CircleCI Project to clone the repo code.

Todo,
1. [Create a token for CCI API](https://circleci.com/docs/api/#add-an-api-token), name it whatever but copy the API key.
2. Go to the CCI project and add this environment variable, *ACME_CIRCLECI_API_TOKEN* with the value of the token in step 1.

Uses,
[Go github-release](https://github.com/aktau/github-release)
