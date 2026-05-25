# Network Analysis

## Successful login
Method: POST
Status code: 302 Found
Redirect: /secure
Session cookie created: yes

## Invalid login
Method: POST
Status code: 200 OK
Error message returned in response body
No session cookie created

## Observations
- Authentication handled via POST request
- Session managed via cookies
- Redirect used after successful login
