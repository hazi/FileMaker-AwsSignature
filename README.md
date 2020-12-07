# AWS Signature in FileMaker

### AWS Signature Version 4 in FileMaker formula.

This repository exposes the implementation of a signature to access the AWS REST API from FileMaker.

The formula not only creates a signature, but also creates a collection of necessary header information and more.
Using the created header information as a cURL option, AWS access can be easily implemented.

See the sample file for actual usage and more.
It comes with a sample for ready-to-use S3 access.

### AWS署名バージョン4のFileMaker計算式実装

このリポジトリではFileMakerからAWSのREST APIにアクセスするための署名の実装を公開しています。

計算式では、単なる署名の作成だけでなく必要なヘッダー情報などをまとめて作成します。
作成されたヘッダー情報をcURLオプションとして使用することでAWSのアクセスが簡単に実装できます。

実際の利用方法などはサンプルファイルを見てください。
すぐに使えるS3アクセス用のサンプルがついています。

## Files

- Main formula(text)
  [AWS Signature Version 4.fmfn](https://github.com/hazi/FileMaker-AwsSignature/blob/master/AWS%20Signature%20Version%204.fmfn)
- Sample File
  [AWS Signature Version 4.fmp12 (Download)](https://github.com/hazi/FileMaker-AwsSignature/raw/master/AWS%20Signature%20Version%204.fmp12)

## License

Licensed under the [BSD license](./LICENSE).

