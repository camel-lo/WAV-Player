# WAV音效檔播放器

## 專案簡介
這是一個基於 C# Windows Forms 開發的簡易 WAV 音效播放器，為「視窗程式設計 (II)」課程的實作練習。程式主要透過`System.Media.SoundPlayer`類別來控制與播放`.wav`格式的音效檔。

## 功能特色
* **檔案瀏覽**：使用`OpenFileDialog`讓使用者能從本機選擇`.wav`檔案。
* **單次播放**：載入音訊並完整播放一次。
* **重複播放**：以迴圈方式持續播放音訊。
* **停止播放**：透過檔案串流控制並隨時中止音訊播放。
* **安全防護**：綁定`FormClosing`事件，在關閉視窗前會跳出MessageBox進行防呆確認。

<img width="421" height="188" alt="image" src="https://github.com/user-attachments/assets/1d406a38-f41a-4f82-8cf8-3b1f07fd6839" />
