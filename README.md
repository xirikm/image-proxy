# Image Proxy

A simple image proxy for no insecure content warnings or disappearing images on https sites.

## How to use

Just create a https website with php runtime environment,and put the file `proxy.php` in your web directory.

Then you can use it by constructing a link like `https://youdomain.com/proxy.php?url=the-url-you-want-to-proxy`.

The url you want to proxy could be in the following format：

```
domain.com/your-image-path
http://domain.com/your-image-path
https://domian.com/your-image-path
```

I created it for my rss subscriber, but I don't know php at all, so the code may be a bit bad, forgive me.