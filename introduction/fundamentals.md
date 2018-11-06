# Fundamentals

The Image API allows the retrieval and manipulation of image files referenced from assets.

The JSON for an asset looks like this:

```json
"fields": {
    "title": "Playsam Streamliner",
    "file": {
      "fileName": "quwowooybuqbl6ntboz3.jpg",
      "contentType": "image/jpg",
      "details": {
        "image": {
          "width": 600,
          "height": 446
        },
        "size": 27187
      },
      "url": "//images.ctfassets.net/yadj1kx9rmg0/wtrHxeu3zEoEce2MokCSi/cf6f68efdcf625fdc060607df0f3baef/quwowooybuqbl6ntboz3.jpg"
    }
  }
```

This reference covers the parameters you can add to the URL specified in the `url` field to manipulate and convert images.