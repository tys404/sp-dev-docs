---
title: GetById REST method
description: GetById REST method
ms.date: 2/26/2018
---

# GetById

> [!IMPORTANT]
> The hub sites feature is currently in preview and is subject to change. It is not currently supported for use in production environments.

Gets information about a hub site.

## HTTP request

```
GET /_api/GetById
POST /_api/GetById
```

## URI Parameters

|Name |In |Required|Type|Description|
|-----|---|--------|----|-----------|
|hubSiteId|query|True|string|The ID of the hub site to get information about.|

## Request headers

| Header | Value |
|--------|-------|
|Accept|application/json;odata=verbose|
|Content-Type|application/json;odata=verbose;charset=utf-8|
|x-requestdigest|The appropriate digest for current site|

## Request body

For GET, no request body is needed. When using POST to update a hub site with new information, use the following body.


## Responses

| Name   | Type  | Description|
|--------|-------|------------|
|200 OK|SPHubSite |OK|


## Examples

### Get a hub site

#### Sample Request

```HTTP
GET
https://contoso.sharepoint.com/_api/GetById
```

#### Sample Response
**Status code:** 200

```JSON
```