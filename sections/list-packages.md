## List Packages

### Description
This call returns information for the list of [packages](https://github.com/xplenty/xplenty-api-doc-v2/blob/master/resources/package.md) that were created by users in your account.
You can use this information to monitor your packages.

### Input Parameters
None

### Request (Curl Call) Syntax
```shell
curl -X GET -H "Accept: application/vnd.xplenty+json" -u <APIkey>: "https://api.xplenty.com/<accountID>/api/packages"
```

### Response Example
```HTTP
HTTP/1.1 200 OK
```

```json
[
  {
    "id": 2373,
    "name": "AWS CloudFront Log Analysis",
    "description": "This package processes AWS CloudFront logs and extracts traffic information by time, geography and URIs",
    "variables": {},
    "owner_id": 8,
    "created_at": "2014-03-12T07:09:18Z",
    "updated_at": "2014-04-13T19:38:04Z",
    "url": "https://api.xplenty.com/xplenation/api/packages/2373"
  },
  {
    "id": 2374,
    "name": "AWS CloudFront Log Analysis 2",
    "description": "This package processes AWS CloudFront logs and extracts traffic information by time, geography and URIs",
    "variables": {},
    "owner_id": 8,
    "created_at": "2014-03-12T08:09:18Z",
    "updated_at": "2014-04-13T20:38:04Z",
    "url": "https://api.xplenty.com/xplenation/api/packages/2374"
  }
]
```
