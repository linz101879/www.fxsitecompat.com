---
title: "`storage` option for `indexedDB.open()` has been deprecated"
date: "2018-03-07T22:16:00-05:00"
categories: ["dom"]
tags: []
versions: ["60"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1442560"
      title: "Bug 1442560 - Warn about deprecation of storage: persistent"
    - url: "https://groups.google.com/d/topic/mozilla.dev.platform/3b700_oeAzo/discussion"
      title: "Intent to unship: \"storage\" attribute in options for indexedDB.open()"
---
The non-standard `storage` option for the [`indexedDB.open`](https://developer.mozilla.org/en-US/docs/Web/API/IDBFactory/open) method, available since Firefox 26, is now considered deprecated and planned to be removed with Firefox 62. Use the standardized Storage API's [`navigator.storage.persist`](https://developer.mozilla.org/en-US/docs/Web/API/StorageManager/persist) method instead. Given that the option has been implemented only in Firefox, the compatibility risk should be very low.
