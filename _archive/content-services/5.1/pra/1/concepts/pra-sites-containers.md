---
author: Alfresco Documentation
---

# Containers

A container is a folder or space in a site. There are API calls for getting a list of top-level containers in a site, and for getting a container by its `containerId`.

To see documentation for methods on this entity, and to try them out on our online REST API explorer, go to [https://api-explorer.alfresco.com/api-explorer/\#/sites](https://api-explorer.alfresco.com/api-explorer/#/sites). If you have the REST API explorer running locally, then go to [http://localhost:8080/api-explorer\#/sites](http://localhost:8080/api-explorer/#/sites).

## Container object

|Property|Type|JSON Type|Description|
|--------|----|---------|-----------|
|folderId|string|string|The container's descriptive name.|
|id|id|string|The container identifier. An opaque string which uniquely identifies this container.|

## Example of a container object

```

{
     "folderId":"documentLibrary",
     "id":"7fb6c69b-f462-429a-a168-87762f660c65"
}
```

## List order

Lists of these entities are returned ordered by ascending `folderId`.

**Parent topic:**[Sites](../../../pra/1/concepts/pra-sites.md)

