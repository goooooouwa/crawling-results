Crawling Results of my favorite Posts & Podcasts URLs 

# How to download mp3 files from URLs

Run the following CURL download with a file with URLs to batch download files:

`xargs -n 1 curl -O -L --retry 5 --retry-max-time 60 -C - < ./mp3-urls-unique-id-fix.txt`


## Explaination of CURL command

-O: download file

-L: follow redirects

--retry: retry x times

--retry-max-time: retry x seconds at most
