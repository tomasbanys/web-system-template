# WEB system
- [ ] VirusTotal analysis

## Description
- [ ] Lets you upload and scan files, submit and scan URLs.

## Entity definition
Name: Scan:
- [ ] ID: Scan ID, mandatory ,(number, 0 < ID < 100)
- [ ] Name: Scan name, mandatory, (String < 100 chars)
- [ ] Malicious: True/False, (Boolean)
- [ ] Result: The scan result itself, (String < 1000 chars)
- [ ] Date: The date of the scan, (String < 9 chars)
- [ ] File: File ID, mandatory, (number, 0 < ID < 100 integer)
- [ ] URL: URL, mandatory, (String < 1000 chars)
 
## API definition
- [ ] Add and scan a file by ID Method POST, /v2/file{id}/scan | possible error 404 (not found)
- [ ] Rescan a file by ID Method POST, /v2/file{id}/rescan | possible error 404 (not found)
- [ ] Scan a URL Method POST, /v2/url/scan | possible error 404 (not found)
- [ ] Retrieving file scan reports Method POST, /v2/file/report | possible error 404 (not found)
- [ ] Retrieving URL scan reports Method POST, /v2/url/report | possible error 404 (not found)
- [ ] Retrieving IP address reports Method GET, v2/ip-address/report | possible error 404 (not found)
- [ ] Retrieving domain reports Method GET, /v2/domain/report | possible error 404 (not found)

## UI definition
Two windows:
   
First
- Import a file
- View scan reports
- Add a URL
   
Second
- Scan file by ID
- Scan URL
 
Link to wireframe: https://wireframe.cc/pro/pp/67ec4dd2d243764

