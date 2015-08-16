Sour based on the default template for JSDoc 3 and [JSDoc-DataTables](https://github.com/DataTables/JSDoc-DataTables) uses: [the Taffy Database library](http://taffydb.com/) and the [Underscore Template library](http://documentcloud.github.com/underscore/#template).

```sh
	npm install jsdoc --glabal
	cd $YOUR_SRC_DIR
	jsdoc --template ../../jsdoc3-sour-template/ -d ../dist/docs -r -R ../README.md -P ../package.json  *
	cd ../dist/docs
	python -m SimpleHTTPServer
```

This template needs cleanup. I hacked it to work for my use case and do realize it will not work for everybody. If something is not working for you let me know and maybe I(or you) can fix it.
