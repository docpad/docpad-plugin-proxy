# Docpad Proxy Plugin

### Usage & Setup
Add the appropriate proxies to your [docpad configuration file](http://docpad.org/docs/config):

``` coffee
# ...
plugins:
	proxy:
		proxies: 
			someProxy:
				path: /^\/some\-path\/.+/
				domain: 'http://proxy-domain.com'
			anotherProxy:
				path: '/another/path'
				domain: 'http://another-proxy.com'
# ...
```