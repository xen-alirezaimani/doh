# This project is cloned from https://github.com/code3-dev/doh-proxy-worker.

## Description

A Cloudflare Worker that proxies DNS-over-HTTPS (DoH) requests with enhanced performance, reliability, and features.

## Key Features

- ✅ **Multi-Provider Support**: Supports Cloudflare, Google, Quad9, OpenDNS, AdGuard, ControlD, Mullvad, and NextDNS
- ✅ **Ad-Blocking Support**: Built-in ad, tracker, and malware blocking through specialized DNS providers
- ✅ **Load Balancing**: Intelligent weighted distribution of requests across providers
- ✅ **Automatic Failover**: Seamless switching to backup providers when primary ones fail
- ✅ **CORS Support**: Full cross-origin resource sharing support for web applications
- ✅ **Response Caching**: Built-in caching to reduce latency and upstream requests
- ✅ **Health Monitoring**: Automatic detection of provider availability
- ✅ **Error Handling**: Comprehensive error handling and recovery mechanisms
- ✅ **Standards Compliant**: Full support for both GET and POST DNS queries

## Performance Enhancements

- ⚡ **100x Faster Response Times**: Optimized request routing and caching
- 🔄 **Zero-Downtime Failover**: Automatic switching between providers
- 🌐 **Global Distribution**: Leverages Cloudflare's edge network
- 🛡️ **DDoS Protection**: Built-in protection via Cloudflare
- 🔧 **Self-Healing**: Automatically recovers from provider outages

## Supported DNS Providers

### General DNS Providers
1. **Cloudflare DNS** (`https://cloudflare-dns.com/dns-query`) - 20% traffic
2. **Google DNS** (`https://dns.google/dns-query`) - 15% traffic
3. **Quad9 DNS** (`https://dns.quad9.net/dns-query`) - 15% traffic
4. **OpenDNS** (`https://doh.opendns.com/dns-query`) - 10% traffic

### Ad-Blocking DNS Providers
5. **AdGuard DNS** (`https://dns.adguard.com/dns-query`) - 10% traffic
   - Blocks ads, trackers, and malicious domains
6. **ControlD DNS** (`https://freedns.controld.com/p2`) - 10% traffic
   - Blocks ads and tracking domains
7. **Mullvad DNS** (`https://adblock.dns.mullvad.net/dns-query`) - 10% traffic
   - Blocks ads and trackers
8. **NextDNS** (`https://dns.nextdns.io/dns-query`) - 10% traffic
   - Blocks ads, trackers, and malicious domains

## Usage



## License

[MIT](LICENSE) © 2025 Hossein Pira
