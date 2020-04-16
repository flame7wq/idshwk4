# idshwk4
### Detect http scan based on 404 response

* The attacker scan the website to look for vulnerabilities
* In the scanning process, a lot of 404 response will be generated because the attacker has no knowledge of the target site before scanning
* So we can detect the attacker through the 404 response
* But there are other scenarios will generate the 404 response,too.
    * site configuration error, user mistype;
    * the spiders repeat crawling the pages not existed
    * downloading tools repeat download the failing url.
