# Brandis: End-to-end encryption for everyone

Try it online: https://brandis.io

This app is intended to illustrate the ease with which secure, end-to-end
encryption can be achieved in modern web browsers, using only a small amount of
JavaScript code.  Brandis does not implement encryption itself; instead, it
relies on the [Web Cryptography API](https://www.w3.org/TR/WebCryptoAPI/)
provided by your browser, and simply exposes a user interface to this API that
enables its use by non-programmers.

To get started, generate a public/private keypair using the button at the top,
and follow the instructions from there.

The source code for this app is in the public domain, and can be accessed on
[GitHub](https://github.com/brandis-project/brandis). We recommended that you
download this page to your computer and use it offline. If you're a programmer,
you can inspect the source code to check for backdoors.

**Note**: Currently the app only works on the latest desktop versions of
Firefox, Google Chrome, and Microsoft Edge.

Brandis is primarily intended as a demonstration; it was put together in less
than a day.  For real-world usage, we recommend more established software such
as [GnuPG](https://www.gnupg.org).
