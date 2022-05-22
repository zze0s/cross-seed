# `cross-seed` API

```http
POST /api/announce
Content-Type: application/json
{
  "title": "string", // the name of the torrent
  "guid": "string", // ideally the torrent's comments/listing url, would be for caching purposes
  "link": "string", // download link, will be retrieved with a GET request
  "size": "number", //optional
  "tracker": "string" // this would probably just be for logging purposes
}
```
