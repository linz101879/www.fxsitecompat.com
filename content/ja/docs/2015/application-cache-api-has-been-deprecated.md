---
title: "Application Cache API が廃止予定となりました"
date: "2015-09-25T01:55:00-04:00"
categories: ["networking"]
tags: []
versions: "44"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1204581": "Bug 1204581 - Add a deprecation notice for AppCache if service worker fetch interception is enabled"
---
Web アプリケーションの [オフライン対応](https://developer.mozilla.org/ja/Apps/Build/Offline) を可能にする HTML5 の [Application Cache API](https://developer.mozilla.org/ja/docs/Web/HTML/Using_the_application_cache) (AppCache) が廃止予定と見なされ、将来的に Firefox から削除されることとなりました。Web 開発者の皆さんには、代替策として [Service Workers](https://developer.mozilla.org/ja/docs/Web/API/Service_Worker_API) を学ぶことをお勧めします。それによって、よりリッチでシームレスなオフラインユーザ体験を近いうちに提供できるようになります。この新しい API は、まだすべての機能が実装されているわけではありませんが、既に [Firefox Developer Edition](https://www.mozilla.org/ja/firefox/developer/) でテスト可能となっています。