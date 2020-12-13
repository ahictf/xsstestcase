# Cross-Site Scripting Test Case

### Cross-Site Scripting (XSS) Payload list

```
<script>alert(1);</script>
<IMG onmouseover="alert('xxs')">
```




## Cross-Site Scripting Test Case
| Use Case Name | |
| --- | ---|
| Precondition | User is not logged into the system |
|  | User is logged into the system |
| Inputs | Cross-Site Script payload list |
| Expected result | tesx show in web page normally not execute JavaScript (eg. not pup up alert show up) |
