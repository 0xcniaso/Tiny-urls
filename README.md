# Tiny urls

Tiny urls is a simple URLs shortener API.

## Generating short URLs

To generate a short URL, simply pass in a `url` query parameter to the website:

    https://tinyurls.gq/?url=http://www.google.com

This will return a shortened URL such as:

    https://tinyurls.gq/9xq

When a user opens the short URL they will be redirected to the long URL location.

By default, it will generate an HTML response for all saved URLs.
You can alter the response format by passing in a `format` query parameter.

    https://tinyurls.gq/?url=http://www.google.com&format=text

The possible formats are `html`, `xml`, `text`, and `json`.
