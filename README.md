# How to replicate issue

* Clone repo
* `jekyll serve -w`
* Browse [http://localhost:4000/admin/#/collections/posts/entries/2017-04-07-welcome-to-jekyll](http://localhost:4000/admin/#/collections/posts/entries/2017-04-07-welcome-to-jekyll) (*causes error*)
* Update source (*resolves error*)
  * Comment out `admin/index.html` line `#38`
  * Uncomment `admin/index.html` line `#41`
* Browse [http://localhost:4000/admin/#/collections/posts/entries/2017-04-07-welcome-to-jekyll](http://localhost:4000/admin/#/collections/posts/entries/2017-04-07-welcome-to-jekyll)
