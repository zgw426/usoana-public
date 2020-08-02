## ウソ穴 - "のぞく"体験を提供する動画再生システム

- 動画やライブ映像を、穴からのぞくように見れます。
- "のぞく→全て見えない→気になる"と心理変化するのが狙いです。
- ユーザーはアプリなどインストール不要、`ウソ穴`のWebサイトを開くだけ

## バージョン情報

- ウソ穴 Ver 5
    - ARにA-Frameを使用
    - 動作確認結果
        - Windows10(Chrome, Firefox) → OK:動いた
        - iPhone (iOS 13.6 + Safari) → OK:動いた
        - Android 9 + Chrome         → NG:動かず
    - **usoana5TypeA-GStreamer**
        - ライブ配信と組み合わせたウソ穴
        - 作り方: Qiita [ウソ穴 Ver 5 Type A / GStreamer](https://qiita.com/zgw426/items/39fd3973ab8ce0a7e69c)
        - ライブ配信はGStreamerを使用
        - Windows10(Chrome, Firefox)で動作実績あり
        - スマホ(iPhone,Android)非対応
        - 映像遅延 : ライブ配信の遅延に依存
    - **usoana5TypeB-時雨堂 sora**
        - ライブ配信と組み合わせたウソ穴
        - 作り方: Qiita [ウソ穴 Ver 5 Type B / 時雨堂 Sora](https://qiita.com/zgw426/items/4a1f9ef19ab41a67c9b3)
        - ライブ配信は[`時雨堂`](https://shiguredo.jp/)さんの [`sora`](https://sora-labo.shiguredo.jp/) を使用
        - 映像遅延 : ほぼゼロ
        - Windows10(Chrome, Firefox)で動作実績あり
        - スマホで動作実績あり
            - iPhone : iOS13.x + Safari
    - **usoana5TypeC-movie**
        - 動画と組み合わせたウソ穴
        - 作り方: Qiita [ウソ穴 Ver 5 Type C / MP4動画](https://qiita.com/zgw426/items/0116d7f4331dcf0ac29d)
        - Windows10(Chrome, Firefox)で動作実績あり
        - iPhone (iOS 13.6 + Safari)で動作実績あり
        - Android 9 + Chrome 非対応
- ウソ穴 Ver 6
    - ARにThreejsを使用
    - 動作確認結果
        - Windows10(Chrome, Firefox) → OK:動いた
        - iPhone (iOS 13.6 + Safari) → OK:動いた
        - Android 9 + Chrome         → OK:動いた
        - ※Ver 5 ではできなかった Android端末での動作を確認
    - Version 5 と同様に Type A,B,C の3種類ある
    - **usoana6TypeA-GStreamer**
    - **usoana6TypeB-時雨堂 sora**
    - **usoana6TypeC-movie**






