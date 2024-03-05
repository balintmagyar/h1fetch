# h1fetch - Fetch data from HackerOne programs

## Requirements

* `curl` and `jq`
* A HackerOne username and API token

## Before use

Set environment variables for your HackerOne username and API token:

```
export H1USER="<username>"
export H1TOKEN="<API token>"
```

## Usage

```
$ h1fetch
Usage: h1fetch <resource> [argument]

Resources:
  programs                      # Fetch and print handles only of all programs with open submissions
  programjson <program handle>  # Fetch and pretty print entire JSON program record
  assets <program handle>       # Fetch and print all in-scope wildcard and URL program assets only
```
