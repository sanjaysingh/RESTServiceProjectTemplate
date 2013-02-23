RESTServiceProjectTemplate
==========================

This is a WCF Service Application project template to help create RESTful services. It shows how you can have user friendly URLs for your REST service. It also shows how you can support different HTTP verbs like POST, GET, PUT and DELETE.

After installing this template, you will find its entry under WCF section name as "REST WCF Service Application". Try to search for "REST" from the template search box if you do not find it.

Projects created based on this template can be run without requiring any other change. Just F5 and guess what you have WCF based RESTfull service up and running. You can browse to following URLs (preferably from Chrome because it handles JSON/XML really well - without any nag box).

1. List of books in JSON

    http://localhost:9999/book/

2. List of books in XML

    http://localhost:9999/book/xml

3. Get a book with ID of 1 in JSON

    http://localhost:9999/book/1

4. Get a book with ID of 1 in XML

    http://localhost:9999/book/xml/1

You can use Fiddler to test POST, PUT and DELETE verbs.
