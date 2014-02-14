[![NPM version](https://badge.fury.io/js/mercadobitcoin.png)](http://badge.fury.io/js/mercadobitcoin)

#Mercado Bitcoin API client package

## Exemplos

```javascript

var mb = new MercadoBitcoin({'moeda': 'BTC'});

mb.ticker(function (response) {
	console.log(response);
});
```


```javascript
var mbt = new MercadoBitcoinTrade({
    'chave': '<CHAVE>', 
    'codigo': '<CODIGO>', 
    'pin': '<PIN>'
});

mbt.getInfo(function (response) {
    console.log(response);
});

mbt.orderList({'pair': 'btc_brl'}, function (response) {
    console.log(response);
});
```

