crypto-js
=========

JavaScript implementations of standard and secure cryptographic algorithms

##Replication of the work to github
by: https://plus.google.com/101493569234247152523/
from: https://code.google.com/p/crypto-js/



# Quick-start Guide
## Hashers
### The Hasher Algorithms
#### MD5
MD5 is a widely used hash function. It's been used in a variety of security applications and is also commonly used to check the integrity of files. Though, MD5 is not collision resistant, and it isn't suitable for applications like SSL certificates or digital signatures that rely on this property.
```html
<script src="http://crypto-js.googlecode.com/svn/tags/3.1.2/build/rollups/md5.js"></script>
```
```ruby
var hash = CryptoJS.MD5("Message");
```