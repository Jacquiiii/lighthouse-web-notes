## Day 10 Lecture Notes: Nov 23, 2022

* JS is event driven and was made to be asynchronous
* Synch code prints first, then asynch
* breakdown of the parts of a Web URL: [Example](http://example.com:8080/path/to/resource.html?first=Paul&last=Simon#photo)
* the http is the protocol. you'll also see https there if the connection is encrypted.
* the example.com is the domain name.
* the colon separates the domain name from the protocol. that part is optional. Usually you don't see that part, and in that case it's implied by the protocol.
* http -> port = 80 https -> port = 443
* the /path/to/resource.html is called the "path"
* the '?' character separates the previous parts from the 'query'. in this case the query is "first=Paul&last=Simon" and it represents a set of ampersand separated name/value pairs.
* Lastly we have the # (hashtag) character. The part that follows that is called the fragment (photo, in this case).

### Links

* [Code demo](https://github.com/ChristianNally/web-2022-Nov-14-Telus)
* Lecture recording: Coming soon.