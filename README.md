###  Command
* プロジェクト作成
```
cordova create ImageRecoginiter com.sora.demo image-recogniter
```

* iOS用のプラットフォーム作成
```
cordova platform add ios
```

* もし削除したい場合は・・
```
※cordova platform rm ios
```

* プラットフォームの確認
```
cordova platform ls
```

* iOS用のプロジェクトビルド
```
cordova build ios
```

```
cordova build ios --buildFlag=-UseModernBuildSystem=0 --device --no-update-notifier
```

### Reference
* [ハイブリッドプロジェクト開発(三)Cordovaプロジェクトを作ってXCode上に動かします](https://qiita.com/gakuseikai/items/08f32fbaef55b8999309)
* [Visual Studio CodeとCordovaで作るハイブリッドアプリ開発環境](https://qiita.com/yama-take/items/8c6434efbcd4bece6310)