# Alfred Search Route Workflow
Alfred PowerPackを購入したので、習作としてGoogleMapの経路探索ができるWorkflowを作りました。

AlfredのWeb SearchやCustom URLだと2つ以上のqueryを入力させることができないっぽかったので、bash scriptを使って書きました。

---

You can search a route from place to place by GoogleMap.

## How to use
```
route {place_from} {place_to}
```

## ScreenShots
Search route from place to place:

![スクリーンショットGIF](https://raw.githubusercontent.com/gonshi/alfred-search-route-workflow/master/screenshots/search_route.gif)

## 更新履歴
* 2016/03/24 v1.01
 - コマンド名をmapからrouteに変更しました。
 - クエリに中点を含むと結果が得られないバグを修正しました。
* 2016/03/23 v1.0 Release
