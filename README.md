# i3investor_scrape

--------------------

/usr/lib/python3.7/urllib/request.py in http_error_default(self, req, fp, code, msg, hdrs)
    647 class HTTPDefaultErrorHandler(BaseHandler):
    648     def http_error_default(self, req, fp, code, msg, hdrs):
--> 649         raise HTTPError(req.full_url, code, msg, hdrs, fp)
    650 
    651 class HTTPRedirectHandler(BaseHandler):

HTTPError: HTTP Error 403: Forbidden

--------------------

Caution, you access to the site later will get denied. :(
