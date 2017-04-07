# How to replicate issue

* Clone repo
* `jekyll serve -w`
* Browse `http://localhost:4000/admin` (*causes error*)
* Update source (*resolves error*)
  * Comment out `index.html` line `#38`
  * Uncomment `index.html` line `41`
* Browse `http://localhost:4000/admin`
