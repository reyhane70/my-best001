# my-best001
just testing github  
import random, string

chars = string.ascii_letters + string.digits + "!@#$%^&*()"
password = "".join(random.choice(chars)  _for in range(12))
print("Generated password:",password )
