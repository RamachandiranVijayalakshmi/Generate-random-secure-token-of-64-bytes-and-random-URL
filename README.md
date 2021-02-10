## Generate-random-secure-token-of-64-bytes-and-random-URL
## Sample code to check the datas
```sh
import secrets

print("Random secure Hexadecimal token is ", secrets.token_hex(64))
print("Random secure URL is ", secrets.token_urlsafe(64))
```
## Example Output
Nil
