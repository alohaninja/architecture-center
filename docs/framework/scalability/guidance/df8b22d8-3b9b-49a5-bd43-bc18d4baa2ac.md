---
uid: df8b22d8-3b9b-49a5-bd43-bc18d4baa2ac
---
## Leverage appropriate caching

<div class="alert is-danger"><p>Caching can improve performance and helps to maintain consistency between data held in the cache and data in the underlying data store.</p></div>

Applications should implement a strategy that helps to ensure that the data in the cache is as up-to-date as possible but can also detect and handle situations that arise when the data in the cache has become stale.

Learn More: [https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside)