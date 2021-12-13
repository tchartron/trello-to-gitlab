# Import your Trello cards as Gitlab issues

This CLI utility allows you to use Trello and Gitlab API to create issues in your gitlab projects from your trello cards.

### Usage
```bash
composer install
# Run from host directly
./trello-to-gitlab
# Run in a docker container
docker run -it --rm -v $(pwd)/:/app php:7.4-cli ./app/trello-to-gitlab
```
