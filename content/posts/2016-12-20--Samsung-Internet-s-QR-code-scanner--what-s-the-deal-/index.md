---
title: "Samsung Internet’s QR code scanner: what’s the deal?"
category: "Qr Code"
cover: img.jpg
author: Peter O'Shaughnessy
---

### Samsung Internet’s QR code scanner: what’s the deal?

Hey, remember QR codes? Those magical black and white squares that convey information and URLs! They can help to bridge the real world and the browser — much like the Physical Web beacon support currently being tested in [our beta](https://medium.com/samsung-internet-dev/beta-d0f988fb77fb).

QR codes sometimes get a bad press, but they can be a handy time-saver and a lot of people use them regularly:

_(Update: If you’d like to learn more about QR code usage in China,_ [_I recommend this_](https://medium.com/chrysaora-weekly/pictures-of-chinese-people-scanning-qr-codes-a564047ec58f)_— discovered via Peter Gasston’s_ [_Surveying the Landscape_](https://medium.com/rehabstudio/surveying-the-landscape-4d7127a7d53f)_)._

The [QR code](https://en.wikipedia.org/wiki/QR_code) has been around for almost as long as the URL. Because QR codes encode information themselves, they are also inherently decentralised, making them a good companion for the web. Unfortunately, in many regions of the globe, phones have generally not been bundled with QR readers, forcing users to download separate reader apps. This is about to change.

In [our new version](https://medium.com/samsung-internet-dev/announcing-samsung-internet-5-0-1ac2bfc14b78) of Samsung Internet, we have an in-built QR code scanner. As long as you have ‘QR code reader’ enabled in the Extensions settings, it’s available in the menu under ‘Scan QR code’:

![](https://cdn-images-1.medium.com/max/600/1*TWbYPptmJz9tRWdHtyXw0A.png)

![](https://cdn-images-1.medium.com/max/600/1*PghFerdymdCxaCLpL0CSEw.png)

Samsung Internet QR code scanner

Now if you scan a QR code representing a URL, that URL will open up directly in the browser. You can try it out with this one that points to Wikipedia, for example:

![](https://cdn-images-1.medium.com/max/800/1*Tb_ZaeHf90_ZyhoIM6Fg8A.png)

[Wikipedia QR code](https://en.wikipedia.org/wiki/QR_code#/media/File:Wikipedia_mobile_en.svg) (public domain)

For QR codes containing text, that will be displayed on a ‘Scan result’ page. You can double-tap or press-and-hold to copy and paste it somewhere, as usual.

![](https://cdn-images-1.medium.com/max/600/1*X0-LFhnvxygncQ7qnTmnNA.png)

![](https://cdn-images-1.medium.com/max/600/1*YVersYpp4P1oyARub_69TA.png)

QR code text result

It also works for barcodes, automatically searching the scanned number in your default search engine.

So why might this be of interest to developers? Well, it’s potentially another way that people could come to your web app, or discover information that you want to share. Please let us know if you find it useful or have suggestions for how we can improve it.

I’m going to leave you with one last QR code that, if you’re brave enough to scan, will lead you somewhere _amazing_:

![](https://cdn-images-1.medium.com/max/800/1*FDqK2wD1euDeauwBXIPWWQ.png)

Scan me! (Generated by [http://goqr.me](http://goqr.me/))

Tagged in [Qr Code](https://medium.com/tag/qr-code), [UX](https://medium.com/tag/ux), [Web Apps](https://medium.com/tag/web-apps), [Samsung Internet](https://medium.com/tag/samsung-internet)

By [Peter O'Shaughnessy](https://medium.com/@poshaughnessy) on [December 20, 2016](https://medium.com/p/20becb76f057).

[Canonical link](https://medium.com/@poshaughnessy/samsung-internets-qr-code-scanner-what-s-the-deal-20becb76f057)