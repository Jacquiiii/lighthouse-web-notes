## Day 24 Lecture Notes: Dec 7, 2022

* app.use(express.static('folder')) for middleware to use all frontend files
  * index is always the main file
  * if anyone makes a get request to /, it will automatically go to index.html if there are no get requests defined
* go to cdn site to get jquery
  * make sure to use latest version
* jQuery.ajax(): has to at least have a method, a url, and a success message (can also add error message)
  * jQuery.get() is a shorthand of this (can do it with promises .then)
* jQuery cannot deprecate old methods, reason is to avoid breaking old code
* .serialize(), .post(), .empty()


### Links

* [Code demo](https://github.com/andydlindsay/telus-nov14-2022/tree/master/w04d03/public)
* [Lecture recording](https://us02web.zoom.us/rec/play/bkbzt8MGFACPTm06EHBQ56C7tj-oQWT_P4xdVFhPUNoycVFCDBWb51QUqoAUm33y9-o6GnB3eF_22FbS.jK68AoWiGRZtn3Ks?continueMode=true&_x_zm_rtaid=K49CAccASe2MbTXJB8E6pg.1670482938280.9ee8f53418558e1a2eadd4381a307669&_x_zm_rhtaid=94)