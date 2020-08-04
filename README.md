# Cloudflare-bypass
Track a website's real ip and bypass cloudflare

## Preparation:

#### 1. CompleteDNS API
- Create an account at [completedns.com](https://completedns.com/) and verify first.
- Input your email and password on `CompleteDNS_Login` variable in `cloudflarebypass.bash`.

#### 2. Dependencies Needed

- curl
- dig
- whois

**Debian Based**

```
apt-get install curl dnsutils whois -y
```

## Installation:
- Clone this repo

```
git clone https://github.com/greycatz/CloudUnflare.git
```

## Command:
- Go to `Cloudflare-bypass` path

```
cd Cloudflare-bypass
```

- Run

```
bash cloudflarebypass.bash
```

### Thank You.

