# URL Investigator

**Objective**

Understand the concept of URL, URI, and their components.

**Concepts**

These concepts are the main used concepts in the project solution, kindly read the provided resources if any is new to you.

| Concept   | Resources                                                                                                                                                                    |
|:----------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| URI | [Java documentation of URI class](https://docs.oracle.com/javase%2F7%2Fdocs%2Fapi%2F%2F/java/net/URI.html) , [RFC 2396 (Section 1.2)](https://www.ietf.org/rfc/rfc2396.txt)  |
| URL | [Java documentation of URL class ](https://docs.oracle.com/javase%2F7%2Fdocs%2Fapi%2F%2F/java/net/URL.html) , [RFC 2396 (Section 1.2)](https://www.ietf.org/rfc/rfc2396.txt) |
| URI and URL Differences | [Auth0 Post](https://auth0.com/blog/url-uri-urn-differences/), [Hostinger Post](https://www.hostinger.com/tutorials/uri-vs-url)                                              |



**Problem**

Develop a method that takes a URL as an input and prints its properties.

**Implementation**

Your implementation should be inside the `printURLInfo` provided to you in the project main class.
<br/>
When you start, follow the following steps.
1. Create a new URL object using URL Class and pass it to `printURLInfo` method.
2. Print the host name of the URL.
3. Print the port number ( if no port specified in the URL, -1 will return ).
4. Print the protocol name.
5. Investigate what other properties are stored in the URL and choose one to print.
```Java
public static void printURLInfo(URL url){
    /* Your code here */
}
```
