# The Ghost Codebase

#### Location: /var/lib/ghost/current -> /var/lib/ghost/versions/4.33.1

#### Get a copy from container: docker cp container-name:/var/lib/ghost/versions/4.33.1 ./code/ghost

## Notes

'''yaml

      - type: bind
        source: ./code/ghost
        target: /var/lib/ghost/versions/4.33.1

'''
