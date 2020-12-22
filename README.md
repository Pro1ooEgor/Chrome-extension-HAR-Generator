# Chrome-extension-HAR-Generator

After installing this extension, open any website

Now click on website any link or reload the page to record HAR file.

Basically after you see the top bar notification this means recording was started.

but because it was off before that  it still has nothing, 
that's why after starting you should reload the page or click any website link to navigate.

Opening option popup you can click "HAR" button left bottom to see HAR file on the browser.

You can send HAR file after inputing server url(http), and request method(POST/GET), your computer name and user name

Regarding https it doesn't work.
But there is solution we can solve.
HTTPS issue can only be solved via a valid cert file, because the extension isn't treating the server as local, it's moving via web and there is a thing cross ogirin
We can add a valid SSL/TLS cert file which is certificate file for getting https active and working
