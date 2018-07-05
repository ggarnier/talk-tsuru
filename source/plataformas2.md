```sh
$ tsuru platform-list
- elixir
- go
- java
- nodejs
- php
- python
- ruby
- static

$ tsuru app-create myapp python
App "myapp" has been created!

$ tsuru app-deploy -a myapp app.py Procfile requirements.txt
```
