# Bossbars
A Bossbar Plugin used By DctxGamesMC
NOTE: CREDITS TO THE ORIGNAL OWNER OF THIS PLUGIN @thebigsmileXD / @XenialDan

Any issues with this pop me and issue at the issue tab:D
# Features:
- creating a bossbar
- Virion Support
# How to create a bossbar?
Usage:
```php
<?php

use xenialdan\apibossbar\DiverseBossBar;
use xenialdan\apibossbar\BossBar;
```
Usage 2:
```php
<?php

$api = new BossBar();

```
Creating The Bossbar:
```php
    public function bossbarText($player) {
        $api = new BossBar();
        $name = "§l§eYour §cMinigame";
        $api->setTitle($name);
        $api->setPercentage(100);
        $api->addPlayer($player);
    }
```

Removing The Bossbar:
```php
    public function removeBossBar($player) {
        $api = new BossBar();
        $api->removePlayer($player);
    }
```
-------------------------------
By XenialDan

- DanteDev
- XenialDan
