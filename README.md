# ![Icon](https://github.com/burakoner/Chiliz.Net/blob/master/Chiliz.Net/Icon/icon.png?raw=true) Chiliz.Net 

A .Net wrapper for the Chiliz API as described on Chiliz, including all features the API provides using clear and readable objects.

**If you think something is broken, something is missing or have any questions, please open an [Issue](https://github.com/burakoner/Chiliz.Net/issues)**

## CryptoExchange.Net
Implementation is build upon the CryptoExchange.Net library, make sure to also check out the documentation on that: [docs](https://github.com/JKorf/CryptoExchange.Net)

My CryptoExchange.Net implementations:
<table>
<tr>
<td><a href="https://github.com/burakoner/OKEx.Net"><img src="https://github.com/burakoner/OKEx.Net/blob/master/Okex.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/burakoner/OKEx.Net">OKEx</a>
</td>
<td><a href="https://github.com/burakoner/Chiliz.Net"><img src="https://github.com/burakoner/Chiliz.Net/blob/master/Chiliz.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/burakoner/Chiliz.Net">Chiliz</a>
</td>
<td><a href="https://github.com/burakoner/BtcTurk.Net"><img src="https://github.com/burakoner/BtcTurk.Net/blob/master/BtcTurk.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/burakoner/BtcTurk.Net">BtcTurk</a>
</td>
</tr>
</table>

JKorf CryptoExchange.Net implementations:
<table>
<tr>
<td><a href="https://github.com/JKorf/Binance.Net"><img src="https://raw.githubusercontent.com/JKorf/Binance.Net/master/Binance.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/Binance.Net">Binance</a>
</td>
<td><a href="https://github.com/JKorf/Bittrex.Net"><img src="https://github.com/JKorf/Bittrex.Net/blob/master/Bittrex.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/Bittrex.Net">Bittrex</a>
</td>
<td><a href="https://github.com/JKorf/Bitfinex.Net"><img src="https://github.com/JKorf/Bitfinex.Net/blob/master/Bitfinex.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/Bitfinex.Net">Bitfinex</a>
</td>
<td><a href="https://github.com/JKorf/CoinEx.Net"><img src="https://github.com/JKorf/CoinEx.Net/blob/master/CoinEx.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/CoinEx.Net">CoinEx</a>
</td>
<td><a href="https://github.com/JKorf/Huobi.Net"><img src="https://github.com/JKorf/Huobi.Net/blob/master/Huobi.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/Huobi.Net">Huobi</a>
</td>
<td><a href="https://github.com/JKorf/Kucoin.Net"><img src="https://github.com/JKorf/Kucoin.Net/blob/master/Kucoin.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/Kucoin.Net">Kucoin</a>
</td>
<td><a href="https://github.com/JKorf/Kraken.Net"><img src="https://github.com/JKorf/Kraken.Net/blob/master/Kraken.Net/Icon/icon.png?raw=true"></a>
<br />
<a href="https://github.com/JKorf/Kraken.Net">Kraken</a>
</td>
</tr>
</table>

Implementations from third parties:
<table>
<tr>
<td><a href="https://github.com/Zaliro/Switcheo.Net"><img src="https://github.com/Zaliro/Switcheo.Net/blob/master/Resources/switcheo-coin.png?raw=true"></a>
<br />
<a href="https://github.com/Zaliro/Switcheo.Net">Switcheo</a>
</td>
<td><a href="https://github.com/ridicoulous/LiquidQuoine.Net"><img src="https://github.com/ridicoulous/LiquidQuoine.Net/blob/master/Resources/icon.png?raw=true"></a>
<br />
<a href="https://github.com/ridicoulous/LiquidQuoine.Net">Liquid</a>
</td>
</tr>
</table>

## Donations
Donations are greatly appreciated and a motivation to keep improving.

**BTC**:  33WbRKqt7wXARVdAJSu1G1x3QnbyPtZ2bH  
**ETH**:  0x65b02db9b67b73f5f1e983ae10796f91ded57b64  


## Installation
![Nuget version](https://img.shields.io/nuget/v/Chiliz.Net.svg)  ![Nuget downloads](https://img.shields.io/nuget/dt/Chiliz.Net.svg)
Available on [Nuget](https://www.nuget.org/packages/Chiliz.Net).
```
pm> Install-Package Chiliz.Net
```
To get started with Chiliz.Net first you will need to get the library itself. The easiest way to do this is to install the package into your project using  [NuGet](https://www.nuget.org/packages/Chiliz.Net). Using Visual Studio this can be done in two ways.

### Using the package manager
In Visual Studio right click on your solution and select 'Manage NuGet Packages for solution...'. A screen will appear which initially shows the currently installed packages. In the top bit select 'Browse'. This will let you download net package from the NuGet server. In the search box type 'Chiliz.Net' and hit enter. The Chiliz.Net package should come up in the results. After selecting the package you can then on the right hand side select in which projects in your solution the package should install. After you've selected all project you wish to install and use Chiliz.Net in hit 'Install' and the package will be downloaded and added to you projects.

### Using the package manager console
In Visual Studio in the top menu select 'Tools' -> 'NuGet Package Manager' -> 'Package Manager Console'. This should open up a command line interface. On top of the interface there is a dropdown menu where you can select the Default Project. This is the project that Chiliz.Net will be installed in. After selecting the correct project type  `Install-Package Chiliz.Net`  in the command line interface. This should install the latest version of the package in your project.

After doing either of above steps you should now be ready to actually start using Chiliz.Net.
## Getting started
After installing it's time to actually use it. To get started we have to add the Chiliz.Net namespace:  `using Chiliz.Net;`.

Chiliz.Net provides two clients to interact with the Chiliz API. The  `ChilizClient`  provides all rest API calls. The  `ChilizSocketClient`  provides functions to interact with the websocket provided by the Chiliz API. Both clients are disposable and as such can be used in a  `using`statement.

## Release Notes
* Version 1.0.2 - 01 Feb 2020
    * Added DepositHistory

* Version 1.0.0 - 26 Jan 2020
    * First Release