## Overview
[`org.apache.struts:struts2-core`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22struts2-core%22)
Apache Struts 2: Classloader manipulation via CookieInterceptor
CookieInterceptor in Apache Struts before 2.3.16.2, when a wildcard cookiesName value is used, does not properly restrict access to the getClass method, which allows remote attackers to "manipulate" the ClassLoader and execute arbitrary code via a crafted request.  NOTE: this vulnerability exists because of an incomplete fix for [CVE-2014-0094](https://snyk.io/vuln/SNYK-JAVA-ORGAPACHESTRUTS-30053).

## References

- [NVD](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-0113)
- [Vulnerability Summary](http://struts.apache.org/docs/s2-021.html)
