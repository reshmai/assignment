This module will help you to provide a URL that responds with a JSON representation of a given node with the content type "page" only if the previously submitted API Key and a node id (nid) of an appropriate node are present, otherwise it will respond with "access denied"

Step to check
1. Install module
2. Go to site information page
3. Add site api key and Update form
3. In url, type page_json/[siteapikey]/[nid of page content type]
4. It will show the json format of node data
5. If apikey and nid not valid then it will show not found page, also only content of page content type  will be accessible