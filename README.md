Crawling Results of my favorite Posts & Podcasts URLs 

## Podcasts: How to download mp3 files from podcast URLs in mp3-urls.txt

Run the following CURL download with a file with URLs to batch download files:

`xargs -n 1 curl -O -L --retry 5 --retry-max-time 60 -C - < ./mp3-urls-unique-id-fix.txt`


### Explaination of CURL command

-O: download file

-L: follow redirects

--retry: retry x times

--retry-max-time: retry x seconds at most

## Blogs: How to generate ebook from blog RSS feed in feeds.txt

See [README](https://github.com/goooooouwa/blog2kindle/blob/master/README.md) of [blog2kindle](https://github.com/goooooouwa/blog2kindle/tree/master).