# Unduck

DuckDuckGo's bang redirects are too slow. Add the following URL as a custom search engine to your browser. Enables all of DuckDuckGo's bangs to work, but much faster.

```
https://unduck-maimunars-projects.vercel.app?q=%s
```

## How is it that much faster?

DuckDuckGo does their redirects server side. Their DNS is...not always great. Result is that it often takes ages.

I solved this by doing all of the work client side. Once you've went to https://unduck-maimunars-projects.vercel.app once, the JS is all cache'd and will never need to be downloaded again. Your device does the redirects, not me.

## Fork

This is a fork of the original project at https://github.com/t3dotgg/unduck.
The reason it exists is that this one uses startpage as a default search engine for privacy reasons and to avoid a lot of the AI bloat of google.
