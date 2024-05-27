# DRAFT / WIP

# setup

- you may need to `direnv allow` for the Python virtual env to work
- you can configure VS code to use the virtual env

- copy `env.example` as `.env` 
- copy `app/.aws/config.example` as `app/.aws/config`
- edit it with your AWS access key id and AWS secret access key

# Running with docker

```
docker compose build
# may take a while - issue with dependencies >10GB

docker compose up
```

http://localhost:8080

- Check with RedisInsight that the embedding are created.
- Note that they will be kept persisted in a docker volume for later use

# TODO

error for Bedrock chat

todo update images from bedrock to openai

explore what can be made more lightweight

change this readme

validate with Redis Cloud and add docs

