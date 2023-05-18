# Rust-shell
Rustでシェルを作る。以下の書籍を参考にします。

www.amazon.co.jp/dp/4065301955

## シグナル
基本的なシグナル

| 番号 | シグナル    | 正称                            | デフォルトの挙動 |
|----|---------|-------------------------------|:---------|
| 2  | SIGINT  | Signal Interrupt              | 終了       |
| 9  | SIGKILL | Signal Kill                   | 終了       |
| 11 | SIGSEGV | Signal Segmentation Violation | 終了       |
| 15 | SIGTERM | Signal Terminate              | 終了       |
| 17 | SIGCHLD | Signal Child                  | 無視       |
| 18 | SIGCONT | Signal Continue               | 復帰       |
| 20 | SIGTSTP | Signal Terminal Stop          | 停止       |
| 21 | SIGTTOU | Signal Terminal Output        | 停止       |
