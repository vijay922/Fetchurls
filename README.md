# Fetchurls
Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl. Originally built as a microservice.

sage:
▻ printf 'example.com' | gau
or

▻ gau example.com


install:
▻ go build -o $GOPATH/bin/gau getallurls.go
