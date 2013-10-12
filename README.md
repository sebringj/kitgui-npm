# kitgui npm - by Emerald Code Inc.

## Summary

npm package to consume kitgui.com CMS SAAS

$ npm kitgui

## Demo

[http://api.emeraldcode.com/demo/products.htm](http://api.emeraldcode.com/demo/products.htm)

## API Documentation

var kitgui = require('kitgui');
kitgui.getContents({

    // CDN host
	host : String,
	
	// CDN base path
	basePath : String,
	
	// "items" consist of objects with the following.
	// "id" which is requires html id attribute format
	// "kind" which is "ids", "seo", or "vars"
	// "editorType" which is "INLINE", "HTML", "IMAGE-ROTATOR", "RAW", "TEAM" (so far)
	items : [{ id: String, kind : String, editorType : String }],
	
	// cache is plain object with name-value pairs
	cache : {},
	
	// disables reading cache on the request, useful when in edit mode, default is true
	cacheNoRead : Boolean,
	
	// disables cache, default is true
	cacheDisable : Boolean
});

## License

This npm is dual licensed under the MIT and GPL licenses.

The KitGUI.com is privately owned by Emerald Code Inc. 

See [Pricing Details](https://www.kitgui.com)

## Thanks to�

* [Hubsoft](http://www.hubsoft.com/) and its clients

_� [Emerald Code](http://www.emeraldcode.com/)_