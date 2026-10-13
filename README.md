# vuln_crawl
Python script using requests and beautifulsoup4
It takes a target URL, crawls linked pages up to a depth you set, collects every external script, stylesheet, and form action it finds, then queries the NVD API for CVEs tied to those components. 
Results land in a timestamped JSON report sorted by CVSS severity, with a plain-text summary on stdout.
