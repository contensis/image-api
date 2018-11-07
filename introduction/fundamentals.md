# Fundamentals

The Image API allows the retrieval and manipulation of image files referenced from assets.

The simplified JSON for an asset looks like this:

```json
{
    "posterImage": {
        "asset": {
            "title": "Batman-Begins",
            "altText": "Batman-Begins",
            "sys": {
                "id": "fa640664-6101-48bc-a1e0-80b9e7ce1280",
                "uri": "/images/Movies/Batman-Begins.x12dfb762.jpg",
                "baseUris": [
                    "https://live.contensis.com",
                    "https://preview.contensis.com"
                ],
                "projectId": "website",
                "contentTypeId": "image",
                "dataFormat": "asset",
                "language": "en-GB",
                "properties": {
                    "filename": "Batman-Begins.jpg",
                    "fileSize": 35403,
                    "fileId": "fa640664-6101-48bc-a1e0-80b9e7ce1280",
                    "width": 342,
                    "height": 513
                }
            }
        },
        "caption": "",
        "altText": "",
        "transformations": null
    }
}
```

