# Smart-TV-Blocklist
A Pi-Hole Blocklist for blocking smart TV telemetry and ads

### A note for Roku users
I would also recommend adding the following Regex blacklists:
```
(ads|logs)\.roku\.com$
(ads|logs|cloudservices).roku.com$
(^|\.)ads\.roku\.com$
```