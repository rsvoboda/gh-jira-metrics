# gh-jira-metrics
A docker based stack to collect metrics from GitHub and JIRA

## Configuration
Edit `docker-compose.yml` and set GH_TOKEN and GH_REPOS.

For token details see https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line

## Execution
```
docker-compose up -d

docker-compose stop
docker-compose down
```