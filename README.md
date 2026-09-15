# PiHole-SmartTV

Pi-hole blocklists generated from DNS activity observed on real Smart TVs by [HTTP Ninja](https://httpninja.nl/).

The lists in this repository focus on manufacturer-related domains observed from supported Smart TV brands. Third-party services such as Netflix, YouTube, Amazon and other streaming providers are excluded from the manufacturer-specific **Block All** lists.

## Available lists

- **LG Block All** — LG Electronics and Alphonso / LG Ad Solutions related domains
- **Samsung Block All** — Samsung Electronics and Samsung-owned service related domains

The lists use Pi-hole regex rules to block the root domain and all of its subdomains.

## Important

A domain appearing in these lists does **not** automatically mean that it is malicious, advertising or tracking.

These domains were observed during normal Smart TV network activity and were selected based on their relationship with the TV manufacturer.

Blocking manufacturer domains can disable Smart TV features, updates, recommendations, account services, advertising services or other functionality.

Review a list before using it.

## Custom Smart TV blocklists

Want more control?

Use the **HTTP Ninja Pi-hole List Builder**:

https://httpninja.nl/pihole-lists

The builder lets you create a custom list directly from DNS domains observed by HTTP Ninja.

You can choose:

- TV brand
- exact observed hostnames
- root domains
- root domains + all subdomains using regex
- domains or keywords to include
- domains or keywords to exclude

For example, you can create a Samsung list containing only domains with `samsung` in the hostname, or exclude streaming services that you still want to use.

## About HTTP Ninja

[HTTP Ninja](https://httpninja.nl/) is an independent privacy research project that observes Smart TV network behaviour.

The project records DNS activity from real televisions and publishes the observed data to make Smart TV network communication easier to inspect and understand.

A DNS lookup only proves that a hostname was requested. It does not by itself prove that data was transmitted, that tracking occurred, or that a service is malicious.

## Disclaimer

HTTP Ninja is an independent project and is not affiliated with, sponsored by or endorsed by LG Electronics, Samsung Electronics or any other manufacturer or service mentioned in this repository.
