# Cross-Site Scripting (XSS) Test Case

### Test Case

| Test Case Name | Reflected Cross-Site Scripting Test Case (Authenticated User) |
| --- | --- |
| Precondition |  User is logged into the system |
| Inputs | Cross-Site Script payload list |
| Expected result | tesx show in web page normally not execute JavaScript (eg. pop-up alert not show up) |


| Test Case Name | Reflected Cross-Site Scripting Test Case (Unauthenticated User) |
| --- | --- |
| Precondition |  User is not logged into the system |
| Inputs | Cross-Site Script payload list |
| Expected result | tesx show in web page normally not execute JavaScript (eg. pop-up alert not show up) |


### Cross-Site Scripting (XSS) Payload list
XSS Payload List
* [xss-payload-list!](https://github.com/payloadbox/xss-payload-list)
* [SecLists](https://github.com/danielmiessler/SecLists/tree/master/Fuzzing/XSS)







![Image of payload](https://ahictf.github.io/xsstestcase/imgs/payload.PNG)

### Team Author
```
Nipitpon Doungyai
Saran Kaewnang
```