**Project requirements**

**1. Introduction**

Nowadays, cryptocurrency is the most progressive tool for online money transactions. Cryptocurrency provides you with anonymity and gives you an opportunity of tracking your "digital money" on it's way from deliver to receiver. 
Cryptocurrency uses cryptography to secure the transactions and to control the creation of additional units, so, the main task of this project is to make choosing of cryptocurrency for mining more convenient and apprehensible.
This application will be used for:
* controlling actual rate of ETH Ethereum, ETC Ethereum Classic and ZEC ZeroCash
* receiving information about currency per hour mining based on model of GPU
* transferring cryptocurrency to US dollar.  


**2. User requirements**

**2.1 User interface**

![interface](https://github.com/YevgeniMakarovich/TransCrypt/blob/master/%D0%9C%D0%9E%D0%9A%D0%90%D0%9F.jpg "Interface")

**2.3 User characteristics**

The target audience - people of all ages, who want to start mining of cryptocurrency or to keep in touch with latest rates.

**2.4 Assumptions and dependencies**

Without internet connection application can not be able to refresh rates and make transfering without it. Also, there are a lot of differences of cryptocurrencies and GPUs, so, this application can not provides you with a great choice of cryptocurrencies, but amount of supported cryptocurrencies and GPU's will become wider in next updates.


**3. System requirements**

1. Windows 7/8/10
2. MSBuild 15.0
3. .NET Framework 4.5.1



**3.1 Functional requirements**

1. When choosing a crypto currency, in the corresponding field the current rate of this crypto currency relative to USD and its rate for yesterday must be displayed.
2. The ability to choose not only  models of GPUs, but also the amount of connected devices.
3. When choosing a crypto currency and GPUs, the amount of received crypto currency per hour and the value of this amount of crypto currency in USD must be displayed in the corresponding field.

**3.2 Non-functional requirements**

**3.2.1 Software quality attributes**

Completeness of provided information - all rates will be updated after every single launch. GPU’s characteristics are static and already published.