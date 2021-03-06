Grav Random Plugin
================
`Random` is a [Grav](http://github.com/getgrav/grav) Plugin and allows to load a random article based on its taxonomy filters.

Installation
========
To install this plugin, just download the zip version of this repository and unzip it under `/your/site/grav/user/plugins`. Then rename the folder to `random`.

You should now have all the plugin files under

	/your/site/grav/user/plugins/random

Usage
=====
`Random` creates a **route** that you define and based on the **taxonomy** filters it picks a random item.
To customize the plugin you firstly need to create an override config. To do so, create the folder `user/config/plugins` (if it doesn't exist already) and copy the [random.yaml](random.yaml) config file in there.

Now you can edit it and tweak it however you prefer.

For further help with the `filters` settings, please refer to our [Taxonomy][taxonomy] and [Headers](headers) documentation.

Config Defaults
============
```
route: /random
filters:
    category: blog
```

[taxonomy]: http://learn.getgrav.org/content/taxonomy
[headers]: http://learn.getgrav.org/content/headers
