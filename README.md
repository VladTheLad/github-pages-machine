github-pages-machine (virtual box + vagrant)
==================================================================

Software required to be installed before:
------------------------------------------------------------------
**Windows:**
* VirtualBox - https://www.virtualbox.org/wiki/Downloads
* Vagrant - http://downloads.vagrantup.com/
* Putty - http://www.putty.org
* GitHub - https://windows.github.com/

**Tested with:** VirtualBox 4.3, Vagrant 1.6.5

Cookbooks & receipts based on the requirements defined on:
------------------------------------------------------------------
https://help.github.com/articles/using-jekyll-with-pages

Cookbooks:
------------------------------------------------------------------
* apt
* github-pages
* nodejs
* make
* ruby
* rubygems

Useful Commands:
------------------------------------------------------------------
```
jekyll --help
sudo jekyll serve --port 80 --verbose --watch
```

Useful Links:
------------------------------------------------------------------
* https://www.virtualbox.org/
* http://www.vagrantbox.es/
* http://jekyllrb.com/

Copyright and license:
------------------------------------------------------------------
Copyright 2015 Mathias Latzko

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
