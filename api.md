## API: `v1` prototype.

```
/v1
|- /users -> List all users
|  |-    /:id -> Get info of user :id
|  |-    /add -> Add a new user
|  |-    /remove -> Remove user
|  |     |-     /:id -> With id
|  |-    /status
|        |-     /:id
|               |-  /lock
|               |-  /unlock
|- /containers
|  |-         /:id
|  |-         /add
|  |-         /remove
|  |          |-     /:id -> With id
|  |-         /
|- /refresh
```
