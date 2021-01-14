# UE4LeapMotion

## [LeapMotion](https://github.com/leapmotion/LeapUnreal)
- LeapMotionDriver はインストールしておく (Install LeapMotionDriver)
- UE4プラグインをダウンロードしておく (Download UE4 plugin)

## プロジェクトの作成 (Create project)
- UE4 新規プロジェクトを作成 (Create new UE4 project)
- ダウンロードしたものを Plugin という名前のフォルダにリネームしてプロジェクトフォルダへコピー (Download and rename as Plugins folder, copy to project folder)
- .uproject 右クリックから Visual Studio のソリューションを生成 (Right click .uproject and generate visual studio solution)
- Leap Desktop Actor をシーンへ追加する (Add Leap Descktop Actor to the scene)
    - LeapHandsPawn は VR 用 
- 4.26だとビルドが通らない…