![源樣黑體/源様ゴシック](https://buttaiwan.github.io/font/pics/genyog.png)

# 繁體中文

「源樣黑體」是基於[思源黑體](https://github.com/adobe-fonts/source-han-sans/)的開放原始碼中文字型。
採用思源黑體韓文（KR）版本為主的字符，配合繁體中文慣用的置中標點，可排版傳統印刷體風格的文件。

## 特徵

### 傳統印刷體

思源黑體預設的台灣版本（TW）採用教育部標準字體，雖然適合教育用途，但不盡符合傳統印刷體審美觀。
例如點、挑、撇筆畫太多，文件排列時的的跳動感較大。
此專案採用KR版本的字符為主，較接近傳統印刷體習慣，排列感較為整齊。

> Note: 本專案並沒有造新的字符，所有字符都是來自思源黑體本身。所以KR版本未收錄的罕用字或簡化字，仍然會是TW、CN風格。

### 漢字不缺字

保留思源宋體所支援之所有漢字（包或日、韓文漢字與簡體字），一般會用到的漢字幾乎不會有缺字問題。
同時也保留了所有日文假名。（但刪除了高達1萬字的韓文字，有效降低字型檔大小。）

> Note: 本專案並沒有造新的字符，簡體字等當然會是CN風格。

### 標點符合繁體中文習慣

直接使用思源黑體KR版本排中文，會有標點置於左下的問題。
此版本的標點符號仍採用繁體中文習慣，逗號、句號等都置於正中央。
並且系統能正確識別為繁體中文字型。

另外，思源黑體的標點符號如「，」「。」設定有比例寬度的壓縮字寬，在Illustrator、InDesign等環境下預設會壓縮50%顯示。這往往會讓標點顯得過窄。
此版本移除了部分符號的壓縮字寬資訊，讓這些標點符號字寬原則上保持全形。

### TrueType格式

字型已經轉換成TrueType格式（.ttf）。
在Word、PowerPoint等軟體支援都較為完整（例如可以正常內嵌在投影片裡）。
對一些老舊的應用程式相容性都較高。

### Ver 1.200　更新 (2018/8/19)

* 解決Word等環境直排時標點符號無法正常旋轉的問題。 （Word 2007 / Word 2016 測試成功。轉成PDF亦正常。）

### Ver 1.300　更新 (2018/9/24)

* 修改部分KR版本不理想的文字對應，並統一部份文字的部件。

### Ver 1.500 更新 (2020/4/11)

* 支援台客語漢字
* 支援台客族語羅馬拼音
* 整合思源黑體V2注音符號，並支援注音直排格式
* 假名與引號類橫排時改為比例寬
* 修改數字 1 、假名さざきぎ為較習慣的形式
* 改以 ttc 形式釋出雙語版本

### Ver 2.000 更新 (2024/7/25)

* 新增源起黑體系列（源樣黑體之楷化轉折重新斷筆的版本）。
* 中文分為現代通用寫法的月版(TW)與傳統鉛字寫法的丹(TC)版，標點改回等寬。
* 日文版分為等寬版本(JP)與比例寬版本(PJP)。
* 新增jf7000當務字集與HKSCS2001漢字。
* 除 ttc 之外，另釋出 otf 版本。
* 修復一些 issues 內的累積問題，如直排時破折號無置中、缺少白話字大寫ᴺ。

### Ver 2.100 更新 (2024/8/22)

* 中文月、丹版，人工重製約百字常用字的寫法，讓寫法稍微統一。
* 新增KS X 1001編碼範圍內的韓文音節2350字與相容字母（輸入法顯示用）。
* 提供傳統粗體模式，讓軟體的B按鈕生效。（實作上是新增X版，內容與B相同，附屬於B版的ttc檔案中一併安裝，作為R版的粗體。otf版未提供）

### 解決一些其他思源宋體使用上的雜問題

* ‘’“” 四個符號，改用半形版本，讓 It’s 之類英文排列正常。（因台灣多用「」引號，少用“”）
* 解決在Illustrator中，文字行高過高，不容易選到正確行的問題。
* 解決在Word中，文字佔兩倍行高的問題。（12pt仍然會占2倍行高，但11pt就能在1倍行高內顯示了。）

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」。

## 此為公測版

目前仍是Beta公測版本，未來本專案不排除有大幅更改規格的可能性。
歡迎提供測試反饋，請直接反饋在GitHub的Issues中。
未來亦不保證持續跟隨思源黑體升版。

## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造Adobe所開發、發表的「[思源黑體](https://github.com/adobe-fonts/source-han-sans/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 本字型可自由使用在印刷、影像、網路或任何媒體上，不限個人或商業使用。
    * 您可基於 SIL Open Font License 1.1 的規定再散佈或改造本字型。

----

# 日本語

「源様ゴシック」は[源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans/)から派生されたフリーフォントです。

## 特徴

### 源ノ角ゴシックをそのままTrueType化

* 日本語ver.は源ノ角ゴシックをほぼそのままTrueType化しただけ。OpenTypeに対応していないアプリケーションでの利用を想定しています。
* Illustratorで、文字選択用のバウンディングボックスがすごく高くなっている問題を解消しました。（すごく高い→やや高いｗ）
* Wordで、行間がすごく高い問題をある程度解消しました。
* まあ一応源真ゴシックはずいぶん前から存在していたため、源様ゴシック日本版の需要は少ないおと思うが……

### 文字セット

日本語サブセットではなく、繁体字中国語セット（Big5）の漢字も入っています。
漢字なら比較的文字化けはしないと思います。
簡体字・ハングルなどはありません。

### Ver 1.200　更新 (2018/8/19)

* WordなどGDI環境で、句読点などが正しく回転できない問題を解決しました。（Word 2007 / Word 2016 テスト済み。PDF保存もOK。）

### Ver 1.300　更新 (2018/9/24)

* 一部の漢字を八屋根のある字形に変更。
![image](https://user-images.githubusercontent.com/5418570/45957251-2d4c8280-c047-11e8-8747-c686f26241fe.png)

### Ver 1.500　更新 (2020/4/11)

* かな・かぎかっこのデフォルトを全角からプロポーションに変更。
* 数字 1 とひらがなの「さざきぎ」を見慣れるスタイルに
* リリースファイル形式を ttc に変更

### Ver 2.000 更新 (2024/7/25)

* 源起ゴシックシリーズ（TW、CN、HK由来の漢字のエレメントをJP、KR風に直すバージョンで、主にTWとTCだけに関わる）。
* 日本語フォントをテキスト向けの等幅(JP)と映像向けのプロポーション(PJP)に分けた。
* 中国語フォントの字形を現代風の月(TW)と伝統活字風の丹(TC)に分け、約物は等幅に。
* ttcのほかに、otfファイルも公開。
* 縦組みのダッシュが真ん中にない問題などを解決。

### Ver 2.100 更新 (2024/8/22)

* 中国語フォントの文字字形を一部修正。
* KS X 1001範囲内のハングル（2350字）とIME用ハングル字母を追加。
* 太字バージョンを提供（ソフトのBボタン）。（ウエイトBのttcにRの太字にあたるウエイトXを追加。ttcバージョンのみ）

## ダウンロード

このGitHubページの右上の「Clone or download」ボタンから、「Download ZIP」をクリックしてください。

## ベータバージョンです

これはベータバージョンです。
予告なく大幅に仕様が変わる可能性あり。

## ライセンスと著作権

* このフォントは、Adobe社が開発・公開している「[源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans/)」を SIL Open Font License 1.1 のもとで改変したフォントです。
* このフォントは SIL Open Font License 1.1 のもとで無償にて公開します。免責条項などに関してはライセンスをご確認ください。
    * 利用者はこのフォントを使用した制作物を有償・無償を問わず自由に公開・配布することが出来ます。 　
    * このフォントに対して SIL Open Font License 1.1 で定められた制限のもとで再配布や改変を行うことが出来ます。
