# hello-world-py
This is an repo of Hello World In Python From Easy to Ridiculous Way

😂

current hardest hello world is given below
```python3
#!/usr/bin/env python3
import os
from dotenv import load_dotenv

load_dotenv()  # take environment variables from .env file

msg = os.getenv('MESSAGE')

def display_msg(message):
    print(message)

if __name__ == '__main__':
    display_msg(msg)

```
It is Available at 
