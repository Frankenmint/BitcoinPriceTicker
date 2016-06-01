# BitcoinPriceTicker

I used to use BTCquote.com for my price ticker on http://honeybadgerofmoney.com.  For the past few months it has been offline....well I had some time so I figure why not?  So I present you with this lightweight JQuery Price ticker tool with a few improvements.

1. DEAD simple to make this into whatever cryptocurrency you want!  

2. Using Flickr API it finds a random image to fill in the background based on keywords of your choosing.  Want an Ethereum Theme Ticker?  Done!  How about a Litecoin Ticker?  Done!  

3. JQuery was used so I could make easy JSON calls...if you choose, you could replace that portion with vanilla JS instead!

Here is the Ticker in Action:

![](http://g.recordit.co/F2YketW2jT.gif)


# Instructuions

1. Copy the snippet into either an html page (removing my body and html tags - you can save a copy of the page itself and run it standalone to see it in action, though you don't need the header/body/html tags if you are porting it to an existing website, just that empty ticker div and the javascript portion), a php template as an echo out, or even into wordpress as a `text/html` widget.


2. Adjust the background images by filling in your own keywords as shown on line [61](https://github.com/Frankenmint/BitcoinPriceTicker/blob/master/priceTicker.html#L61) in the main file.  Currently it is set to `bitcoin` and `honeybadger` but as you see in the photo, it's only as good as the tags on publicly listed code.  (If you wanted, it would be trivial to create a loop of images to rotate in yourself and instead show those for each pass)
