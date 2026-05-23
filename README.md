# psychrise-reels

Video assets for the [@the.psychrise](https://instagram.com/the.psychrise) Instagram Reels auto-posting pipeline.

Reels are served through the jsDelivr CDN, which delivers them with the correct `video/mp4` content type required by the Instagram Graph API:

```
https://cdn.jsdelivr.net/gh/BrockAImusic/psychrise-reels@main/<filename>.mp4
```

> ⚠️ jsDelivr caches for ~12 h. After pushing a new reel, wait a few minutes before scheduling it for posting.
