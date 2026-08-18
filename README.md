# Web Application Security Labs

## About This Repository

This repository documents a series of practical web application security labs I completed using PortSwigger Web Security Academy and Burp Suite.

The labs provided hands-on experience investigating web application vulnerabilities, analysing HTTP traffic and manipulating requests to understand how security weaknesses can be identified and exploited in controlled environments.

Each lab includes a brief explanation of the vulnerability, the methodology used, skills demonstrated, key learning outcomes and evidence of successful completion.

## Tools & Technologies

- Burp Suite
- PortSwigger Web Security Academy
- HTTP
- REST APIs
- Web application security testing
- Web browser developer tools

## Labs

### 1. [Server-Side Parameter Pollution](server-side-parameter-pollution/)

Investigated server-side parameter pollution within a REST API and used Burp Suite to analyse and manipulate HTTP parameters.

**Skills:** REST API testing, HTTP request analysis, parameter manipulation, vulnerability analysis.

---

### 2. [Host Header Authentication Bypass](host-header-authentication-bypass/)

Investigated how improper handling of the HTTP Host header could be used to bypass access restrictions.

**Skills:** HTTP header manipulation, authentication testing, access control testing, Burp Suite.

---

### 3. [Insecure Deserialization](insecure-deserialization/)

Investigated insecure handling of serialized objects and how manipulating user-controlled serialized data could affect application behaviour.

**Skills:** Insecure deserialization testing, serialized object manipulation, HTTP analysis, vulnerability analysis.

---

### 4. [Server-Side Template Injection](server-side-template-injection/)

Identified and exploited a basic server-side template injection vulnerability caused by unsafe processing of user-controlled input.

**Skills:** SSTI testing, input manipulation, HTTP request analysis, Burp Suite.

---

### 5. [Web Cache Poisoning](web-cache-poisoning/)

Investigated web cache behaviour and demonstrated how an unkeyed HTTP header could influence cached responses.

**Skills:** Web cache poisoning, cache behaviour analysis, HTTP header manipulation, request and response analysis.

---

## Skills Developed

Through these practical labs, I developed experience in:

- Intercepting and analysing HTTP requests and responses
- Using Burp Suite for web application security testing
- Manipulating HTTP parameters and headers
- Testing authentication and access control mechanisms
- Investigating REST API security
- Identifying and analysing common web application vulnerabilities
- Understanding the security impact of insecure application behaviour
- Documenting technical findings and security testing methodology
