# Search Engine Scraper
This is a simple command line tool to scrape subdomains from popular search engines like Google, Bing, DuckDuckGo, Yandex, Yahoo, and Baidu.

## Usage
bash
```
./search_engine_scraper SEARCH_ENGINE QUERY
SEARCH_ENGINE should be one of the following:
```


google

bing

duck

yandex

yahoo


baidu

QUERY is the string to search for.

Example


```
./search_engine_scraper google "example query"
```

Available Search Engines

Google

Bing

DuckDuckGo

Yandex

Yahoo

Baidu

Output
The program will output a list of matched subdomains in the format:

```javascript
Copy code
Response from https://www.google.com/search?q=example+query :
Matched subdomains:
subdomain1
subdomain2
...

```


## Deployment Guide
This guide provides the steps to deploy the code on a system.

Requirements
Go programming language installed on your system
Steps
Clone the code repository from Github to your system
bash

```
git clone https://github.com/<username>/<repo-name>.git
```

Go to the code directory

```
cd <repo-name>
```
 
Build the code using the Go compiler
  
```

go
go build
Run the compiled binary to start the code
```

 

