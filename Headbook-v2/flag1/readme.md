The app displayed an encrypted message after submitting a login form.
### Solution:
I used Burp Suite to capture the API request and identified the flag hidden in the response.

```bash
# Intercept the HTTP request using Burp Suite
GET /analytics HTTP/1.1
Host: ctf.ivrodriguez.com

# Capture and view the response
HTTP/1.1 200 OK
Content-Type: application/octet-stream
flag-4056CEF3-DCCB-4D9B-9D0E-64428E9A50E3
```
### Flag Found:
`flag-4056CEF3-DCCB-4D9B-9D0E-64428E9A50E3`
