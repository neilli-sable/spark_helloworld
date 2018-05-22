# spark_helloworld

## 概要
- Apache Sparkを動作確認用プロジェクトです
- 公式ドキュメントに書かれたコードを動かします
  - https://spark.apache.org/docs/latest/quick-start.html

## 依存ライブラリなど
- Spark2.3
- Java8
- Scala2.11

## 実行方法
- (前提: Sparkのインストール)
- cd ./spark_helloworld
- (ビルド) mvn packge
- (実行) $SPARK_HOME/bin/spark-submit --class "info.escesc.Main" --master local target/Main-0.0.1.jar
