## About

This is a simple multi-user online editor.

Clients are changing text in the text area and the text is syncronized between all clients.

WebSockets technology is used to communicate between server and client.

Edited text is stored in memory on server side, and would be cleaned after server restart.


## Installation & Usage

1. Install all dependencies via composer:
```
    composer install
```

1. Run server from command line:
```
    php bin/server.php
```

1. Open in browser several clients 'web/index.php'
