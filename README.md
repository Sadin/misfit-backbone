# mifsit-backbone
### a jsonrpc 2.0 server to handle requests from misfit
---

## About
this jsonrpc server handles requests from the misfit bot as a midway between the bot and blizzards API. The idea is to utilize this application in conjunction with misfit but to offload some of the computational tasks of the bot onto another application.

At a high level:
``` user(issues command) -> misfit(bundles request as json, sends request to backbone) -> backbone(request data from blizzard, calculate, return result) -> misfit(catch result request, display) -> user(is happy)```

### Important Links
* [jsonrpc Specification](http://www.jsonrpc.org/specification) - *specification this project follows*
* [misfit](https://github.com/Sadin/misfit) - *bot that will regularly make calls to this service*
* [Discord Server](https://discord.gg/TCdkxgC) - *discord server the misfit bot and this service aim to serve ( We play wow come join ^^)*

#### Contributors
* [Zach Snyder](https://github.com/Sadin) - *code*
* [The Misfit Toys Guild ( WoW - Maflurion/Trollbane )](https://discord.gg/TCdkxgC) - *Testing, Feedback, Feature Requests*

#### Special Thanks
* The ***GANGGANG*** bois and grils
* My mentor at PJM
* One hastey boi
* And a partridge in a pear tree
* *"Its snowing on Mt Fuji"* - Dan Avidan 
