# My old webpage

## Configuration in GitHub

- Set `www.tarod.net` as custom domain in Settings::Page.

## DNS configuration

- Configure the `CNAME` with name `www` and value `ftena.github.io`. Then, check it's working using `dig www.tarod.net +nostats +nocomments +nocmd`
- Add the following `A` records with name `@` 

````    
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
````

- Confirm that the DNS record were configured correctly using `dig tarod.net +noall +answer -t A`
