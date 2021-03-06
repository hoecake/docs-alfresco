---
author: [Alfresco Documentation, Alfresco Documentation]
audience: 
category: api
option: api
---

# Sites

An Alfresco site is a project area where you can share content and collaborate with other site members. There are API calls for getting a list of sites, and for getting information on a single site.

## Site object

|Property|Type|JSON Type|Description|
|--------|----|---------|-----------|
|title|string|string|The site's name \(used in the site's list and on the sites dashboard\).|
|description|string|string|The description of the site|
|visibility|string|string|The visibility of the site, `PRIVATE`, `PUBLIC`, or `MODERATED`.|
|id|id|string|The site identifier. An opaque string which uniquely identifies this site.|

## Example of a site object

```

{
      "title":"Fred Bloggs's Home",
      "description":"Fred Bloggs's private home site.",
      "visibility":"PRIVATE",
      "id":"fred-bloggs-yourcompany-com"
}        
         
```

-   **[Methods](../../../pra/1/concepts/pra-sites-methods.md)**  
Methods for site objects.
-   **[Containers](../../../pra/1/concepts/pra-sites-containers.md)**  
 A container is a folder or space in a site. There are API calls for getting a list of top-level containers in a site, and for getting a container by its `containerId`.
-   **[Members](../../../pra/1/concepts/pra-sites-members.md)**  
Members are the people who collaborate on a site. There are API calls for getting a list of the members of the site, getting the site membership information for a person, adding a person to a site, and updating a person's site membership information.

**Parent topic:**[API reference](../../../pra/1/concepts/pra-resources.md)

