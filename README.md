# spicy-scripts

This repo contains basic custom networking protocol parsers written in spicy (https://docs.zeek.org/projects/spicy/en/latest/).

- Just HTTP for now, will add DNS soon


## Dependencies
- Spicy (https://docs.zeek.org/projects/spicy/en/latest/installation.html)

## Run the script
- Clone the repo
- Create an HTTP request in request.txt & an HTTP response in response.txt
- From the root directory, run
```
spicy-driver -p SimpleHTTP::Requests http.spicy < request.txt
spicy-driver -p SimpleHTTP::Responses http.spicy < response.txt
```
