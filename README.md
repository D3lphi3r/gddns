# gddns

## Command line tool for updating the DNS for your domains thru Google DDNS API.

----

By defult the applaction use the JSON file (**config.json**) if these arguments (-r -u -p) are not used, The file should be in the **_same direcotry_** with the application.


## Usage:

_This method can only update a single domain._

./gddns -r example.com -u Username -p Password 

or

_#This method uses the config.json to update multiple domains._

./gddns  


For other options see the help menu using **-h** or **--help** argument.

----

This is a the template of the [JSON file](https://github.com/D3lphi3r/gddns/blob/master/bin/config.json).

