## Building

built by github workflow, just commit

## backup (manually)

in <india032>/docker/codex-docs run createBackup.sh, then downloadBackup.sh

## restarting

In <india032>/docker/codex-docs

docker-compose down
docker-compose up -d

## creating release

git tag -a v0.0.5 -m "my version v0.0.5"
git push origin --tags

### upgrade

docker-compose down (with old version)

in <india032>/docker/codex-docs, check docker-compose.yml and update version
