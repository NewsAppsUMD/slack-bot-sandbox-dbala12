[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/0EbNa5xO)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=14157896)
# slack-bot-sandbox

A repository for experimenting with the Slack API in Python by students in JOUR328, News Application Development.

## March 11 
Notes on Congress API Keys

Rate Limit
The rate limit is set to 1,000 requests per hour.

Limit and Offset
By default, the API returns 20 results starting with the first record. The 20 results limit can be adjusted up to 250 results. If the limit is adjusted to be greater than 250 results, only 250 results will be returned. The offset, or the starting record, can also be adjusted to be greater than 0.

Choose json instead of xml. To do so, follow this https://api.congress.gov/v3/committee-report/118?api_key=kqGbMNXmLpj8ZpwCcnfAidioFgmQdNLo8oErWpie&format=json

118 is the congress. Then, ?api_key="the api we requested". &format=json to change xml to json.

