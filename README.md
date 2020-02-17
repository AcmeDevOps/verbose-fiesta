The purpose of this project is to test different stuff in CircleCI. Make sure the organization *AcmeDevOps* has been granted access in your CircleCI account, this will add an organization SSH key allowing a CircleCI Project to clone the repo code.

#### Create CircleCI API token,
1. [Create a token for CCI API](https://circleci.com/docs/api/#add-an-api-token), name it whatever but copy the API key.
2. Go to the CCI project and add this environment variable, *ACME_CIRCLECI_API_TOKEN* with the value of the token in step 1.

#### Create Github API token,
1. [Generate a new Access Token](https://github.com/settings/tokens) with the following perms:
   - public_repo
   - read:org
   - read:repo_hook
   - repo:status
   - repo_deployment
2. Go to the CCI project and add this environment variable, *GITHUB_TOKEN* with the value of the token in step 1.
3. [Generate a machine user](https://circleci.com/docs/2.0/gh-bb-integration/#controlling-access-via-a-machine-user) follow the steps in this stanza

Uses,
[Go github-release](https://github.com/aktau/github-release)
