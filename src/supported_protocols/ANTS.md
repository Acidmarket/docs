# ANTS


## Deploy

The deploy operation is a static, unchangeable inscription operation:

data:,{"p":"prc-20","op":"deploy","tick":"ants","max":"2100000000000000","lim":"100000000"}


## Mint

Send the transaction and make sure the JSON fields contain valid content.

| Key | Description |
| -------- | -------- |
| p | protocol name: [prc-20] |
| op | operation: [mint] |
| tick | ticket name: [ants], case-insensitive |
| amt | mint quantity, not exceeding the limit |



Example: data:,{"p":"prc-20","op":"mint","tick":"ants","amt":"100000000"}


## Transfer

Send the transaction and make sure the JSON fields contain valid content.

| Key | Description |
| -------- | -------- |
| p | protocol name: [prc-20] |
| op | operation: [transfer] |
| tick | ticket name: [ants], case-insensitive |
| amt | transfer quantity |



Example: data:,{"p":"prc-20","op":"transfer","tick":"ants","amt":"100000000"}
