# FileInterceptor

The script is a file interceptor tailored for HTTP traffic, specifically designed to detect and prevent .exe file downloads by redirecting clients to a different URL. While effective for its narrow use case, it would need significant enhancements for broader or more complex interception tasks.

**NOTE:**
>'HTTP/1.1 301 Moved Permanently\r\nLocation: http://facebook.com\r\n\r\n '

make sure to replace the url in the location of the above in the code befor e running the code, you could replace it with url redirecting to webpages were you have hosted your payload.

keep in mind to make use of this code while you are man in the middle.

*use it wisely*
