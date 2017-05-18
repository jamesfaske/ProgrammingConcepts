1. User Sends Request
2. ASP.NET Environment is created to serve the request
  1. IIS 
    1. determines which ISAPI extension can server the request
  2. Application
    1. ApplicationManager - creates a domain where the website can run
    2. HttpRuntime
      1. HttpContext
      2. HttpRequest
      3. HttpResponse
    3. HttpApplication
    4. HttpApplication object is assigned to the core ASP.NET objects to process the page
3. Request is processed using Module, handler, page, and Module event
