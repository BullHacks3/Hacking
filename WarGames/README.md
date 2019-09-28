### Personal Guide To OWASP TOP 10 ###

OWASP TOP 10 Vulnerabilities
[ IBS XBS CIU I]
1. Injection (SQL injection ,LDAP injection)
2. Broken Authentication and Session Management
3. Sensitive Data Exposure
4. XML external Entity
5. Broken Access Control
6. Security Misconfigurations
7. Cross Side Scripting 
8. Insecure Deserialization
9. Using Components with known vulnerabilities
10. Insufficient logging and monitoring


1. Injection :- 
```
Includes flaws such as SQL injection,LDAP injection and CRLF injection
Causes :-
Occurs when an attacker sends untrusted data to an interpreter
Prevention :-
Application security testing

Due to SQL injection vulnerability an attacker can control the database (that means all the information, including administrator and users’ confidential information) and can execute commands on the server (that means they have full access).

To exploit the SQL injection vulnerability an attacker can use automatic tools or manual techniques. The most common tools are:
SQLmap
SQLninja


```

2. Broken Authentication and Session Management
```
Cause :- Improperly configured user and session authentication could allow attackers to compromise
passwords,keys or session tokens etc.
Prevention:-
Multi-factor authentication



```

3. Sensitive Data Exposure
```
Cause :-
Applications and Apis that don't properly protect sensitive data 
Prevention :-
Encryption of data at test and in transit
```

4. XML External Enitity
```
Cause :-
Poorly configured XML processors evaluate external entity references within XML
Remote code execution and to disclose internal files and SMB file shares
```

5. Broken Access Control
```
Cause:-
Improperly configured or missing restrictions on authenticated users
Prevention:-
Penetration testing
```

6. Security Misconfiguration
```
Improper implementation of controls such as misconfiguration of security headers,error messages ,not patching the systems'
Prevention :
Dynamic Application Security Testing
```

7. Cross-Side Scripting
```
XSS vulnerability gives access to attackers the capability yo inject client-side scripts into the applications
   7.1 Reflected XSS
   7.2 Stored XSS
Prevention :
By proper validation and sanitization of the inputs
The risk factor of XSS is high because user information can be stolen via XSS vulnerability. Session hijacking, cookies stealing, phishing (redirecting users to another malicious website), website defacement and an attacker can control the victim’s web browser and then their operating system

There are different ways and techniques to exploit the XSS vulnerability, like phishing and others discussed above. Besides manual technique, these common tools can be helpful:
XSS Shell
BeEF XSS Framework  
```

8. Insecure Deserialization
```
Enable an attacker to execute code in the application remotely,conduct injection attacks and elevate privileges.
Prevention :
Application security tools can detect deserialization flaws
```

9. Using Components with known vulnerabilites
```
Less information about the third party components involve in the application
Prevention:
Software Composition Analysis
```

10. Insufficient Logging and Monitoring
```

```
