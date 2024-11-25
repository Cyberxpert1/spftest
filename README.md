SPF RECORD TESTING TOOL
Overview
These tools are meant to help you deploy SPF records for your domain. They use an actual RFC 7208 compliant library (pyspf) for tests and will dynamically test for processing limit errors (no other testers I'm aware of do this). This site uses a caching DNS resolver, so for tests that use live DNS, results will be cached for the Time To Live of the DNS record. For most basic uses, these tests should be reasonably self explanatory. Advanced users may need, and probably want, some additional information on how these tools work. It can be found.
