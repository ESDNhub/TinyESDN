TinyESDN
========

Single-page HTML app using [jQuery](http://www.jquery.com) and [Bootstrap](http://www.getbootstrap.com) that searches the [DPLA](http://dp.la) API and
return results from [Empire State Digital Network.](http://empirestate.digital) You need an DPLA API
key for this to work, see
[http://dp.la/info/developers/codex/policies/#get-a-key.](http://dp.la/info/developers/codex/policies/#get-a-key)
Once you have a key, create a file named `apikey.js` containing this one line:

	var DPLA_API_KEY = "YOUR API KEY"; // Your API key here

and save it in the same directory as the index.html file. You should now be good to go.
