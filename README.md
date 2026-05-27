# Lab8-Starter

Hien Tran

GitHub URL: https://tmhiennn.github.io/Lab8_Starter_HienTran

Question: How are graceful degradation and service workers related?

- Graceful degradation means that an app still functions even when something is missing or failing, rather than breaking completely. Service workers are a tool for implementing graceful degradation. With a full internet connection, the user gets the best experience with fresh data loaded directly from the network. With a slow connection, the service worker can serve cached resources instantly instead of making the user wait. With no internet at all, the app still works only if the browser support service worker because the service worker serves everything from the cache. And if the browser doesn't support service workers at all, the app will just be like a normal browser and won't have offline capabilities. Each level loses a little functionality, but the app never completely breaks.

![PWA ](pwa.png)
