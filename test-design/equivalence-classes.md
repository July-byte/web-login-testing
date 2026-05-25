# Equivalence classes
## Username field
Valid:
- Correct username (tomsmith)

Invalid:
- Incorrect username
- Empty value
- Very long string
- Special characters
- SQL injection (' OR 1=1 --)
- XSS (<script>alert(1)</script>)

## Password field
Valid:
- Correct password (SuperSecretPassword!)

Invalid:
- Incorrect password
- Empty value
- Very long string
- Leading/trailing spaces
