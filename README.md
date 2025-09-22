Converting to MV-HEVC for AIVU

# How to use

1. Export ProRes file as Bundle and Separete Eyes from Davinch.
2. Place the left-eye and right-eye videos in a folder named “videos” as left.mov and right.mov.
3. Run the command below to change directory.
```
cd <path of the unzipped folder>
```
4. Run the command below. You can specify the output file name if you like:
```
./SideBySideToMVHEVC -i videos -o output.mov
```

# 使い方
1. DavinchからProResファイルをバンドル形式&「左右」で書き出します。
2. 左右の映像を「left.mov」「right.mov」にリネームし「videos」フォルダ配下に置きます。
3. 以下のコマンドを実行し、解凍したフォルダに移動します。
```
cd <解凍したフォルダのpath>
```
4. 以下のコマンドを実行します。出力ファイル名は任意で指定できます。
```
./SideBySideToMVHEVC -i videos -o output.mov
```
