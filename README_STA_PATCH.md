# Note to playground patch

This is a playground patch to see where the software works or not for us.
to build the patch execute in the base dir

```
docker build -t matrixdotorg/synapse -f docker/Dockerfile . --no-cache
```

Changes where made in the dockerfile so that it loads the STA from the local dir.
In the STA some changes were made to see if it then the custom flow works.