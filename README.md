# ChatGPT APIを用いた翻訳,発話Androidアプリ

このプロジェクトは、WhisperAPIとOpenAI APIを用いた翻訳を,TTSを用いて発話することのできるアプリです。CameraAndTranslateGPTAppの翻訳機能のみを取り出し使いやすくしました.
以下は実際の画面です,
![音声認識と翻訳機能](https://github.com/Shun0212/CameraAndTranslateGPTApp/blob/f8eadbe7e3ffd324caf924daced0d1d3ea7ba855/Screenshot_20240925-013203.png)

## 主な機能. 音声認識と翻訳機能
- Androidデバイスのマイクで音声録音
- Whisper APIでテキスト化
- ChatGPTで翻訳
- TTS（Text-to-Speech）で音声再生

## Androidアプリの設定方法

1. このリポジトリのmaster branchをクローン
2. Android Studioでプロジェクトを作る
3. xmlファイル,ktsを適切な場所にコピーする
4. 実際の環境に合わせる、そのままでは動かない可能性があるため,ChatGptに質問しデバッグして動かしてください、具体的にはOPENAI_API_KEYの設定の仕方,AndroidManifestについて聞くといいと思います.
5. 実行する

# Android App for Translation and Speech Using ChatGPT API

This project is an app that can translate using Whisper API and OpenAI API and speak out using TTS. It extracts and simplifies only the translation functionality of CameraAndTranslateGPTApp.
Below is the actual screen,
![Speech Recognition and Translation Feature](https://github.com/Shun0212/CameraAndTranslateGPTApp/blob/f8eadbe7e3ffd324caf924daced0d1d3ea7ba855/Screenshot_20240925-013203.png)

## Main Features: Speech Recognition and Translation
- Record audio using the microphone of an Android device
- Transcribe audio to text using Whisper API
- Translate using ChatGPT
- Play back translated text using TTS (Text-to-Speech)

## How to Set Up the Android App

1. Clone the master branch of this repository.
2. Create a project in Android Studio.
3. Copy the XML files and `.kts` to the appropriate locations.
4. Adjust it to your environment. It may not work right away, so ask ChatGPT for help debugging. Specifically, you may need to ask about how to set up the `OPENAI_API_KEY` and configuring the `AndroidManifest`.
5. Run the app.
