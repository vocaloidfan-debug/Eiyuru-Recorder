# Eiyuru Recorder 🎙️

> ⚠️ **Geliştirme Notu:** Bu site şu an geliştirme aşaması nedeniyle bazı özellikler çalışmayabilir veya eklenmemiş olabilir; lütfen bunu göz önünde bulundurarak kullanın!

---

## 🇹🇷 Türkçe

**Eiyuru Recorder**, UTAU ve DiffSinger AI ses bankaları için tarayıcı üzerinde çalışan bir kayıt, otomatik etiketleme ve paketleme stüdyosudur.

* **Çevrimdışı / Tarayıcıda Çalışır:** Ekstra bir yazılım veya kurulum gerektirmez.
* **Ücretsiz ve Reklamsız:** Tamamen ücretsizdir ve hiçbir reklam içermez.
* **Geliştirme Aşaması:** Bazı özellikler henüz eklenmemiş veya deneysel aşamada olabilir.

### Özellikler
* **UTAU Modu:** Tekli reclist seçimi, özel reclist oluşturma, `.txt` içe/dışa aktarma, isteğe bağlı AI reclist üretimi ve otomatik SetParam tarzı `oto.ini` hesaplama.
* **DiffSinger AI Modu:** Reclistsiz serbest kayıt veya cihazdan ses yükleme, LabelMaker tarzı RMS enerji tabanlı sessizlik (`SP`), nefes (`AP`) ve sesli bölge ayrıştırma (`.lab` ve `transcriptions.csv`), 10 dakikadan (600 sn) kısa kayıtları otomatik 10 dakikaya tamamlama ve `oto.ini` içermeyen DiffSinger klasör yapısı (`character.txt`, `character.yaml`, `dsconfig.yaml`, `dsdict-*.yaml`, `acoustic.onnx`, `dsdur/dur.onnx`, `dspitch/pitch.onnx`, `dspitch/variance.onnx`, isteğe bağlı `icon.png` / `portrait.png`).
* **Çok Dilli Arayüz ve Okunuş Rehberi:** **TR**, **EN**, **日本語** ve **العربية** arayüz dilleri; seçili dile göre **Hiragana**, **Duolingo İngilizce CVVC**, **Türkçe CVVC** (`ü`, `ö`, `ı`, `ğ`, `ş`, `ç`), **Arapça CV** ve **Osmanlıca CV** (ayrı **Lam** ve **Lamelif `لا`** heceleriyle) okunuş açıklamaları.

### GitHub Pages Kurulumu
1. `index.html` ve `README.md` dosyalarını deponuza yükleyin.
2. **Settings → Pages** menüsünden **Deploy from a branch** seçeneğini ve ana dalı (`main`) seçip kaydedin.

---

## 🇬🇧 English

**Eiyuru Recorder** is a browser-based voicebank recording, auto-labelling, and packaging studio for UTAU and DiffSinger AI.

* **Works Offline / In-Browser:** Requires no installation or local setup.
* **Free & Ad-Free:** Completely free to use with zero ads.
* **In Development:** Some features may not work yet or may still be missing.

### Features
* **UTAU Mode:** Single reclist selection, custom reclist builder, `.txt` import/export, optional AI reclist generator, and automatic SetParam-style `oto.ini` generation.
* **DiffSinger AI Mode:** Reclist-free freestyle recording or device audio upload, LabelMaker-style RMS energy segmentation into silence (`SP`), breath (`AP`), and voiced regions (`.lab` and `transcriptions.csv`), automatic 10-minute (600s) looping for shorter recordings, and DiffSinger folder structure without `oto.ini` (`character.txt`, `character.yaml`, `dsconfig.yaml`, `dsdict-*.yaml`, `acoustic.onnx`, `dsdur/dur.onnx`, `dspitch/pitch.onnx`, `dspitch/variance.onnx`, plus optional `icon.png` / `portrait.png`).
* **Multilingual UI & Pronunciation Guides:** Instant switching between **TR**, **EN**, **日本語**, and **العربية** with localized pronunciations for **Hiragana**, **Duolingo English CVVC**, **Turkish CVVC**, **Arabic CV**, and **Ottoman Turkish CV** (with separate **Lam** and **Lam-Alif `لا`**).

### GitHub Pages Setup
1. Upload `index.html` and `README.md` to your repository.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main`, and save.

---

## 🇯🇵 日本語

**Eiyuru Recorder** は、UTAU および DiffSinger AI 音源のためのブラウザ完結型録音・自動ラベリング・パッケージ作成スタジオです。

* **オフライン / ブラウザ動作:** インストールや事前セットアップは不要です。
* **完全無料・広告なし:** 無料で利用でき、広告は一切ありません。
* **開発中:** 開発段階のため、一部の機能が動作しない場合や未実装の場合があります。

### 主な機能
* **UTAU モード:** 単一リクリスト選択、カスタムリスト作成、`.txt` 読込/書込、任意の AI リクリスト生成、SetParam 風 `oto.ini` 自動計算。
* **DiffSinger AI モード:** リクリスト不要のフリー録音または端末からの音声読込、LabelMaker 風の RMS エネルギー解析による無音（`SP`）・息継ぎ（`AP`）・有声区間の自動分割（`.lab` および `transcriptions.csv`）、10分（600秒）未満の音声の自動10分拡張、`oto.ini` を含まない DiffSinger フォルダ構成（`character.txt`、`character.yaml`、`dsconfig.yaml`、`dsdict-*.yaml`、`acoustic.onnx`、`dsdur/dur.onnx`、`dspitch/pitch.onnx`、`dspitch/variance.onnx`、任意の `icon.png` / `portrait.png`）。
* **多言語 UI と発音ガイド:** **TR**・**EN**・**日本語**・**العربية** の切り替えに対応し、選択中の言語に合わせた **ひらがな**、**Duolingo 英語 CVVC**、**トルコ語 CVVC**、**アラビア語 CV**、**オスマン語 CV**（独立した **ラーム** と **ラームアリフ `لا`**）の発音ガイドを表示します。

### GitHub Pages 公開手順
1. リポジトリに `index.html` と `README.md` をアップロードします。
2. **Settings → Pages** から **Deploy from a branch** を選び、`main` ブランチを指定して保存します。

---

## 🇸🇦 العربية

**Eiyuru Recorder** هو استوديو يعمل داخل المتصفح لتسجيل بنوك الصوت والوسم التلقائي وتجهيز الحزم لبرنامجي UTAU و DiffSinger AI.

* **يعمل دون تثبيت / داخل المتصفح:** لا يحتاج إلى تنصيب أو إعداد محلي.
* **مجاني وبدون إعلانات:** مجاني بالكامل ولا يحتوي على أي إعلانات.
* **قيد التطوير:** قد لا تعمل بعض الميزات أو قد لا تكون قد أُضيفت بعد نظراً لمرحلة التطوير الحالية.

### المميزات
* **وضع UTAU:** اختيار قائمة تسجيل فردية، إنشاء قائمة مخصصة، استيراد وتصدير `.txt`، توليد قائمة اختياري بالذكاء الاصطناعي، وحساب تلقائي لمعاملات `oto.ini` بأسلوب SetParam.
* **وضع DiffSinger AI:** تسجيل حر بدون قائمة تسجيل أو رفع صوت من الجهاز، وتقسيم تلقائي بأسلوب LabelMaker حسب طاقة RMS إلى صمت (`SP`) وتنفس (`AP`) ومقاطع صوتية (`.lab` و `transcriptions.csv`)، وتكرار التسجيلات الأقصر من 10 دقائق (600 ثانية) تلقائياً إلى 10 دقائق كاملة، مع هيكلة ملفات DiffSinger دون `oto.ini` (`character.txt` و `character.yaml` و `dsconfig.yaml` و `dsdict-*.yaml` و `acoustic.onnx` و `dsdur/dur.onnx` و `dspitch/pitch.onnx` و `dspitch/variance.onnx` وملفات `icon.png` / `portrait.png` الاختيارية).
* **واجهة متعددة اللغات وأدلة النطق:** التبديل الفوري بين **TR** و **EN** و **日本語** و **العربية** مع شروحات نطق حسب اللغة المختارة للهيراغانا والإنجليزية CVVC والتركية CVVC والعربية CV والعثمانية CV (مع فصل **اللام** عن **لام ألف `لا`**).

### النشر عبر GitHub Pages
1. ارفع ملفَي `index.html` و `README.md` إلى المستودع.
2. من **Settings → Pages** اختر **Deploy from a branch** وحدد فرع `main` ثم احفظ.
