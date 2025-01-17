# PanzerFPVUnity
![PanzerFPVUnity](https://user-images.githubusercontent.com/1827523/61180969-4a942100-a65a-11e9-9fb7-ec49b1311b26.PNG)

* Oculus Rift Sでカメラ映像を見ながら操作するUnity製ラジコン戦車操作プログラム。
* Motion JPEGで送られてくる魚眼画像を球面上へ投影→シェーダー [UnityVR220Shader](https://github.com/xeno14/UnityVR220Shader)
* gRPCで命令を送信→ラジコン側のプログラム [panzerserver](https://github.com/misakahi/panzerserver)

# Setup

1. リポジトリをクローンする。
2. 依存ライブラリをAssets以下にインストール
    1. [Oculus Integration for Unity](https://developer.oculus.com/downloads/package/unity-integration/)
    2. [gRPC](https://github.com/grpc/grpc/tree/master/examples/csharp/HelloworldUnity) ※2019年6月時点でEXPERIMENTAL ONLY
    3. [id:hammmさん作Motion JPEGストリーミングを低遅延で再生するAsset](http://hammmm.hatenablog.com/entry/2016/12/15/204514)
3. 素材をAssets以下に配置
    1. Assets/Sounds ... [エンジン音](http://www.orangefreesounds.com/tank-sound-effect/), [キャタピラの音](https://commons.nicovideo.jp/material/nc140616)
    1. Assers/Fonts ... [Octin Stencil](https://www.dafont.com/octin-stencil-free.font)



天球のデフォルトの画像[（C）Entaniya](http://products.entaniya.co.jp/)
