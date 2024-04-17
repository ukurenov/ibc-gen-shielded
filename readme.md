### Install dependens:
```
pip install -r requirements.txt
```

### Start:

```
python main.py
```


### Config.py

##### LEDGER_ADDRESS_B = RPC
##### PORT - server port

## RPC config for generate 
##### POST - https://gen-shielded.namada.guru
#### Body:
```
{
    "target": "IBC ZNAM address receiver",
    "token": "Token address",
    "amount": "Amount",
    "channel": "Channel-id"
}
```

### Response: String
