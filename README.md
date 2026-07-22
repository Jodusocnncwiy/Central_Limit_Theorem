**Jodus中央極限定理 \(Central Limit Theorem\) 互動視覺化模擬器**

這是一個專為學生與統計學初學者設計的互動式網頁模擬器。透過動態視覺化，幫助使用者直觀地理解**中央極限定理 \(Central Limit Theorem, CLT\)** 的核心意義與統計特性。

**🌟 網頁特色**

1. **多元的母體分佈選擇**：
    - 常態分配 \(Normal Distribution\)
    - 均勻分配 \(Uniform Distribution\)
    - 指數分配 \(Exponential Distribution / 偏態\)
    - 雙峰分配 \(Bimodal Distribution\)
    - *證明無論母體的原始形狀如何，抽樣平均數皆會收斂為常態分配。*
2. **靈活的樣本數調整**：
    - 提供滑桿自由調整每次抽樣的樣本數 $n$（範圍：10 至 200，預設 30）。
    - 觀察樣本大小如何影響標準誤與分佈的集中程度。
3. **高效的重複抽樣按鈕**：
    - 支援抽樣 1 次、10 次、100 次、1,000 次及快速抽樣 10,000 次，即時見證大數法則與常態分佈的形成。
4. **即時數據與理論比對**：
    - 動態計算並顯示母體理論值（平均數 $\\mu$、標準差 $\\sigma$）與實驗樣本平均數。
    - 提供理論常態曲線疊加比對（$\\mu\_\{\\bar\{x\}\} = \\mu$，$\\sigma\_\{\\bar\{x\}\} = \\frac\{\\sigma\}\{\\sqrt\{n\}\}$）。

**🚀 快速開始與部署 \(GitHub Pages\)**

本模擬器採用純前端技術開發（**HTML5, Tailwind CSS, Chart\.js**），不需要安裝任何複雜的後端環境。

**方法一：直接線上遊玩 \(GitHub Pages\)**

1. 將本專案上傳至您的 GitHub 儲存庫（Repository）。
2. 進入該 Repository 的 **Settings** > **Pages**。
3. 在 **Build and deployment** 的 Branch 選擇您的主分支（例如 main 或 master）並點擊 **Save**。
4. 幾秒鐘後，GitHub 會提供您一個公開網址，點擊即可線上開啟模擬器！

**方法二：本機執行**

1. 將此儲存庫 Clone 或下載至您的電腦：
2. git clone https://github\.com/jodusocnncwiy/Central\_Limit\_Theorem\.git
3. 直接用瀏覽器（如 Chrome、Edge、Safari）開啟 index\.html 檔案即可開始互動！

**🛠️ 使用技術**

- **HTML5 / CSS3** \(結構與樣式\)
- **Tailwind CSS** \(介面排版與現代化設計\)
- **Chart\.js** \(高效能動態統計圖表渲染\)

**📄 授權條款**

本專案採用 [MIT License](LICENSE) 授權條款。歡迎自由取用、修改與分享！