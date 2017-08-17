# REST (FAKE Server to test applications)
JSON Server (sample response)
To be used with https://my-json-server.typicode.com/

Sample Data file github.com/user/repo/master/db.json
{
  "posts": [
    {
      "id": 1,
      "title": "hello"
    }
  ],
  "profile": {
    "name": "typicode"
  }
}


Sample call (and response) my-json-server.typicode.com/user/repo/posts/1
{
  "id": 1,
  "title": "hello"
}
