# FatSecret API Proxy

A request proxy for FatSecret API.

[FatSecret](https://platform.fatsecret.com/) requires you to whitelist the IP from the machine you are going to make requests to them. With a home dynamic IP that's a no-go. So this is just a tiny proxy to be hosted on a machine with a permanent IP address, so you can query it and it will forward request to FatSecret and return the answer back to the original requester.
