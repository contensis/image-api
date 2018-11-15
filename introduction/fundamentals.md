---
description: The fundamentals of the Image API combining query string parameters with the uri of an image.
---

# Fundamentals

Image transformations work by applying the query parameters of the transformation  to the `uri` of an image. The `uri` for the image can be found in the `uri` attribute of an [image](https://developer.zengenti.com/contensis/api/delivery/http/model/image.html) sys object, returned in the JSON response.

Transformations set against the image from the UI or [Management API](https://developer.zengenti.com/contensis/api/management/http/model/image-transformations.html) are appended as query string parameters to the sys.uri, so that when requested the transformations are applied using the Image API.

When the entry is requested without a linkDepth, the uri is not set however the transformations are still returned.

The simplified JSON for an asset looks like this:

```json
{
    "asset": {
        "title": "Fight Club Poster",
        "description": "Fight Club main poster artwork",
        "altText": "Fight Club",
        "sys": {
            "id": "a83c9fcc-51ef-41aa-878f-af5a33ba4b2f",
            "projectId": "movieDb",
            "contentTypeId": "Image",
            "dataFormat": "asset",
            "language": "en-GB",
            "uri": "/images/1999/drama/fight-club.jpeg?w=1920&h=1080",
            "properties": {
                "filename": "fight-club.jpeg",
                "fileSize": 6033,
                "width": 300,
                "height": 450
            },
            "version": {
                "createdBy": "c.alahniuk",
                "created": "1999-11-02T17:30:31.73",
                "modifiedBy": "b.pitt",
                "modified": "1999-11-02T17:30:31.73",
                "publishedBy": "d.fincher",
                "published": "1999-11-02T17:30:31.73",
                "versionNo": "1.0"
            }
        }
    },
    "caption": "Fight club is a great film!",
    "altText": "The 1999 Fight Club movie poster.",
    "transformations": "w=1920&h=1080"
}
```

