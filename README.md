## install Json Server
- Documentation :: `https://github.com/typicode/json-server`
## Usage
`Create a db.json or db.json5 file`

`{
  "posts": [
    { "id": "1", "title": "a title", "views": 100 },
    { "id": "2", "title": "another title", "views": 200 }
  ],
  "comments": [
    { "id": "1", "text": "a comment about post 1", "postId": "1" },
    { "id": "2", "text": "another comment about post 1", "postId": "1" }
  ],
  "profile": {
    "name": "typicode"
  }
}`

## Start Json server
`json-server --watch db.json`

## Newman Report
![image](https://github.com/user-attachments/assets/625c2dc9-2a04-4b3d-8c76-300ae8d90e64)

