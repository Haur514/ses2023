# 目的
[ソフトウェアエンジニアリングシンポジウム2023](https://ses.sigse.jp/2023/)に投稿した論文の実験データの掲載

# データの見方
`fileName` : 欠陥箇所を含むファイル名<br>
`buggy_line` : 欠陥箇所を含む行<br>
`rank` : 欠陥箇所の順位<br>
`rFail` : 失敗テストに占める例外期待テストの割合<br>
`rPass` : 成功テストに占める例外期待テストの割合<br>
`num_failed_cetest` : 失敗したカスタム例外期待テストの個数<br>
`num_passed_cetest` : 成功したカスタム例外期待テストの個数<br>
`num_failed_stetest` : 失敗した標準/サードパーティ例外期待テストの個数<br>
`num_passed_stetest` : 成功した標準/サードパーティ例外期待テストの個数<br>
`num_fialed_test` : 失敗したテストの個数<br>
`failed_tests_coverage_length` : 失敗テストが実行したプログラム文の数<br>
`num_passed_test_execute_buggy_line` : 欠陥箇所を実行した成功テストの数<br>
`num_failed_test_execute_buggy_line` : 欠陥箇所を実行した失敗テストの数<br>
`bug_id` : 実欠陥のDefects4Jにおける欠陥ID．人工欠陥にはついていない．<br>
`type_reefail` : RQ1における欠陥の区分<br>
`type_reepass` : RQ1における欠陥の区分<br>
