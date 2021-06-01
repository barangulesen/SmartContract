# Binance Smart Chain <br>
 Contract Type - Bep20 <br><br>

# BEP20 Token<br><br>
A BEP20 token must implement the interface IBEP20 in IBEP20.sol. This is a template contract BEP20Token.template. Users just need to fill in _name, _symbol, _decimals and _totalSupply according to their own requirements:

<br><br>
  constructor() public {<br>
    _name = {{TOKEN_NAME}};<br>
    _symbol = {{TOKEN_SYMBOL}};<br>
    _decimals = {{DECIMALS}};<br>
    _totalSupply = {{TOTAL_SUPPLY}};<br>
    _balances[msg.sender] = _totalSupply;<br>
<br>
    emit Transfer(address(0), msg.sender, _totalSupply);<br>
  }<br>
Then users can use Remix IDE and Metamask to compile and deploy the BEP20 contract to BSC.<br>

