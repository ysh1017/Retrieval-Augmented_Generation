# 檢索增強生成（Retrieval-Augmented Generation, RAG）

[![](https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/Squirtle007/Retrieval-Augmented_Generation/blob/main/Retrieval_Augmented_Generation.ipynb)

**只需幾分鐘，即可在 NVIDIA GPU 上免費體驗 RAG 模型推論！**
*請依照下方第 1～5 步驟操作，然後開啟這個 [**Colab**](https://colab.research.google.com/github/Squirtle007/Retrieval-Augmented_Generation/blob/main/Retrieval_Augmented_Generation.ipynb)。*
我的個人 [**Colab**](https://colab.research.google.com/drive/1Pgzs1T_Jlf5b5G9P1axBeD8u0Aunsteq)。*
---

<img src="https://github.com/Squirtle007/Retrieval-Augmented_Generation/assets/66664309/8a84417f-f600-4917-9e33-63bf770234e9" width="800">

---

## 步驟 1：

前往 [Try NVIDIA NIM APIs](https://build.nvidia.com/explore/discover) 頁面，點選右上角的 `Login` 登入或註冊（建議使用公司信箱）：

<img src="https://github.com/Squirtle007/Retrieval-Augmented_Generation/assets/66664309/63fcccf5-bd36-45ef-a681-90a63c82f0ff" width="800">

## 步驟 2：

在主頁選擇一個可用模型（例如 [`llama3-70b-instruct`](https://build.nvidia.com/meta/llama3-70b)）：

<img src="https://github.com/Squirtle007/Retrieval-Augmented_Generation/assets/66664309/86a9b1d1-cbbd-4db3-b255-0de006453f8a" width="800">

## 步驟 3：

產生該模型的 API 金鑰，並妥善保存。我們稍後會使用這個 API 金鑰透過 NVIDIA 雲端 LLM 進行推論：

<img src="https://github.com/Squirtle007/Retrieval-Augmented_Generation/assets/66664309/b696ab2c-ae5a-4f4d-b190-1a752073d8f4" width="800">

## 步驟 4：

開啟 [colab](https://colab.research.google.com/github/Squirtle007/Retrieval-Augmented_Generation/blob/main/Retrieval_Augmented_Generation.ipynb)，確認選擇 `Runtime > Change runtime type > T4 GPU`。

<img src="https://github.com/Squirtle007/Retrieval-Augmented_Generation/assets/66664309/9f8feb46-1d4a-4013-b4de-2f71333b9300" width="600">

<img src="images/colab-change-runtime-type-t4-gpu.png" width="500">

## 步驟 5：

將你的 API 金鑰貼到 notebook 開頭的程式格中，並執行該程式格以連接 NGC 上的模型：

<img src="https://github.com/Squirtle007/Retrieval-Augmented_Generation/assets/66664309/0ef8cefd-b946-4310-8b98-96232616e59f" width="800">
