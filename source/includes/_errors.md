# Errors

The Guestbook API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your JWT Authorization token token is invalid/expired.
403 | Forbidden -- The resource requested is outside your application's scope.
404 | Not Found -- The specified account could not be found.
500 | Internal Server Error -- We had a problem with our server. Our development team has been notified, but reach out if the problem persists.
