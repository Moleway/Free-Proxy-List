# Moleway Free Proxy List

Fresh public proxies, independently checked and continuously revalidated by [Moleway](https://moleway.com/free-proxy-list).

**Last updated:** 2026-09-06 22:15 UTC  
**Current LIVE endpoints:** **1638**

| List | Contents | Current count |
| --- | --- | ---: |
| [`all.txt`](https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/all.txt) | All LIVE proxies with protocol prefix | 1638 |
| [`http.txt`](https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/http.txt) | LIVE HTTP proxies | 937 |
| [`https.txt`](https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/https.txt) | LIVE HTTP proxies verified to support HTTPS tunnelling | 298 |
| [`socks4.txt`](https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/socks4.txt) | LIVE SOCKS4 proxies | 231 |
| [`socks5.txt`](https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/socks5.txt) | LIVE SOCKS5 proxies | 471 |

## Formats

`all.txt` includes the protocol:

```text
http://203.0.113.10:8080
socks4://203.0.113.20:1080
socks5://203.0.113.30:1080
```

The protocol-specific files contain only:

```text
IP:PORT
```

`https.txt` is **not a separate proxy protocol**. It is the subset of LIVE HTTP proxies for which Moleway successfully verified end-to-end HTTPS capability.

## Quick use

All protocols:

```bash
curl -fsSL https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/all.txt
```

HTTP:

```bash
curl -fsSL https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/http.txt
```

HTTPS-capable HTTP:

```bash
curl -fsSL https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/https.txt
```

SOCKS4:

```bash
curl -fsSL https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/socks4.txt
```

SOCKS5:

```bash
curl -fsSL https://raw.githubusercontent.com/Moleway/Free-Proxy-List/main/socks5.txt
```

## Validation

Moleway continuously checks proxies rather than publishing source lists unchanged.

Validation includes protocol-specific connectivity, observed exit behavior, latency, and regular rechecks. HTTPS capability is tested separately over a real TLS connection.

The complete interactive list, including country, anonymity, HTTPS capability, latency, filtering and downloads, is available at:

**https://moleway.com/free-proxy-list**

## Important

Public proxies are volatile. A proxy that worked during Moleway's latest validation can stop working at any time.

Use public proxies responsibly and comply with the laws, policies and terms that apply to your use.
