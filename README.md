# spicy-scripts

This repo contains basic custom networking protocol parsers written in spicy (https://docs.zeek.org/projects/spicy/en/latest/).

- Just HTTP for now, will add DNS soon


## Dependencies
- Spicy (https://docs.zeek.org/projects/spicy/en/latest/installation.html)

## Run the script
- Clone the repo
- Create a custom HTTP request & response (or use example tests)
- From the root directory, run
```
spicy-driver -p SimpleHTTP::Requests http.spicy < tests/req1.txt
spicy-driver -p SimpleHTTP::Responses http.spicy < tests/res1.txt
```
