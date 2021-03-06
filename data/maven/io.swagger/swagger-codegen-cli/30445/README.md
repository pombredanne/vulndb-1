## Overview
[`io.swagger:swagger-codegen-cli`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22swagger-codegen-cli%22) is a simple yet powerful representation of your RESTful API.
Affected versions of this package are vulnerable to Arbitrary Code Execution via parameter injection. By leveraging this vulnerability, an attacker can inject arbitrary execution code embedded with a client or server generated automatically to interact with the definition of service.

## References
- [Scott Davis Blog](https://community.rapid7.com/community/infosec/blog/2016/06/23/r7-2016-06-remote-code-execution-via-swagger-parameter-injection-cve-2016-5641)
- [Github PR](https://github.com/swagger-api/swagger-codegen/pull/3201)
