# FaceApp BE

**Very simple backend app build in Express and Typescript**

The server has only one endpoint:

## Get the list of faces  
`GET /api/faces`  
Will return the list of all the faces available in JSON format.  
Example
```JSON
[
  { "id": "1", "avatar": "https://i.pravatar.cc/150?img=1", "name": "Morgan James" },
  ...
]
```

## Use
>Node v12.16.2

```Bash
npm i
npm start
```

## Heroku
This server is ready to run on Heroku.
>https://test-3dmz-be.herokuapp.com/api/faces