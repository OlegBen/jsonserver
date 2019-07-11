## JSON Server
**Get user with login 'oleg'**
```
fetch('https://my-json-server.typicode.com/OlegBen/jsonserver/users?id=oleg')
    .then(response => response.json())
    .then(user => {
        console.log(user[0].id) // oleg
    })
```

**Get user (oleg) albums**
```
fetch('https://my-json-server.typicode.com/OlegBen/jsonserver/userAlbums?id=oleg')
    .then(response => response.json())
    .then(userAlbums => {
        console.log(userAlbums[0]) //Albums list
    })
```