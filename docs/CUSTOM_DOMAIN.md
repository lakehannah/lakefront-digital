# Custom Domain Setup

## Step 1: Add CNAME file to repo ✅
File: `CNAME` contains: `www.lakefrontdigital.org`

## Step 2: Configure DNS (Google Domains)

Go to https://domains.google.com → DNS → Custom Resource Records

Add these records:

```
Type: A
Name: @
TTL: 1H
Data: 185.199.108.153
Data: 185.199.109.153
Data: 185.199.110.153
Data: 185.199.111.153

Type: CNAME
Name: www
TTL: 1H
Data: lakehannah.github.io.
```

## Step 3: Enable HTTPS in GitHub

1. Go to repo Settings → Pages
2. Under "Custom domain" enter: `www.lakefrontdigital.org`
3. Check "Enforce HTTPS"
4. Save

## Step 4: Wait

- DNS changes: 5 minutes to 24 hours
- HTTPS certificate: 24-48 hours (automatic from GitHub)

## Final URLs

- http://lakefrontdigital.org → redirects to www
- https://www.lakefrontdigital.org ← main site

Done!
