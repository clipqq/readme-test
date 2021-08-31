# readme-test
# Methodology:
- Did Github tutorial: `https://docs.github.com/en/actions/quickstart`
- Located a swagger.json file by Googling `https://petstore.swagger.io/v2/swagger.json` based on the API URL. Redirected to `https://petstore.swagger.io/#/`
- Assumed api key was `special-key`
- Used pipeline template from `https://support.atlassian.com/bitbucket-cloud/docs/get-started-with-bitbucket-pipelines/` to setup `bitbucket-pipelines.yml` file
- Created new ReadMe project: `https://dash.readme.com/project/sa-project/v1.0/overview`
- Pasted in Github Action template with API key from ReadMe admin dash
- Pointed local repo to new Bitbucket repo
- Committed new Bitbucket `.yml` file with fixed npm script command to trigger Pipeline job

# Issues
- Had to hunt for Swagger JSON file
- Initially unclear that a ReadMe login and new ReadMe project to be created to get the API key
- Initially unclear that objective was for API specs to be uploaded via both Github and Bitbucket
- API version was not an optional attribute in Github `.yml` file
- Bitbucket script command was outdated, need to be corrected to `npm rdme openapi`