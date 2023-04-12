IMPORANT PLEASE READ:
My code does work, you must first upload an image, then proceed to upload a profile image, and then click the menu button. Upon doing this it will load the picture. If this doesn't work you probably should just refresh the page. 


## S3 bucket to use:

https://bucket470570.s3.us-west-2.amazonaws.com

## Tokens 

See Canvas


## S3 bucket CORS config

```
[
    {
        "AllowedHeaders": [
            "*"
        ],
        "AllowedMethods": [
            "HEAD",
            "GET",
            "PUT",
            "POST",
            "DELETE"
        ],
        "AllowedOrigins": [
            "*"
        ],
        "ExposeHeaders": [
            "ETag"
        ]
    }
]
```
