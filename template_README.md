# Table_AI_ML_Codespaces_template
GitHub CodespacesでJupyter Notebookを使うときのテンプレート（テーブルデータのAI/MLコンペ用）

[github/codespaces-jupyter](https://github.com/github/codespaces-jupyter) を参考に改変し、TableデータのAI/MLコンペ用のテンプレートを作成

## github/codespaces-jupyterとの違い

* サンプルデータ、サンプルノートブックがない
* 参考元 : CPU数 4以上、本テンプレート : CPU数 2以上
* Tableデータを扱うときに使いそうなPythonモジュールを `requirements` フォルダ以下に分割して記載
* おすすめのライブラリのみ `requirements/recommended.txt` に記載し、`updateContentCommand` でインストールする運用に変更
* VSCode拡張を追加
