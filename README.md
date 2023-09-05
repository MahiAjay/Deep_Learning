#If we want to keep our data safe we can use base64 encoding.
import base64

# Your string
x = "female"

# Encode to Base64
encoded = base64.b64encode(x.encode()).decode()

print(encoded)

which gives the output : ZmVtYWxl
The base64.b64encode() function is used to encode the string, and decode() is used to convert the result from bytes to a string.
