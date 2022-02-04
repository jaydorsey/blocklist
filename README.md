# Jay Dorsey's Block List

A set of rules for [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) (4.1 or higher) and
[Pi-hole](https://pi-hole.net/)

## Installation

Manually add the URL to [jaydorsey.lsrules](https://raw.githubusercontent.com/jaydorsey/blocklist/main/jaydorsey.lsrules) 
as a Rule Group Subscription

Manually add the blocklist to your pi-hole gravity rules

## Adding new rules

Add new hosts to both lists with one command:

```sh
./new_host <domain>
```
