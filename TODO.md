
Next steps:

* why does the browser open in its own toplevel window?  -- fix
** look at browser in Inspector and check out the various attributes (eg message="true")
** might be related to varius assertions in full-dbg build (ThirdPartyUtil, BasePrincipal, nsGlobalOutWindow, frame stuff..

* get something rendering
* get CSS loading and rendinger


sec
--
* set to remote="true"?


* if spotlight.html loads chrome://...spotlight.js, that's allowed.  why?  should it be?
* limit entire dialog to one https site (probably using CORS)
* is this any way that using Subresource Integrity (or something related) could be helpful
* force fission this origin
