# my-flop-game
<h3><strong>學期 2-2：軟體開發實務入門課程_ S4 翻牌遊戲：微型專案設計</strong></h3>
<ol>
<li>章節介紹<a href="http://example.com/](https://lighthouse.alphacamp.co/courses/99/units/20666" title="Title">
an example</a> _優化程式碼品質 _模組化程式碼MVC _思考與設計</li>
<li>任務：翻牌遊戲</li>
<li>定義必要資料 _遊戲規則描述 _必要的資料</li>
<li>拆解遊戲流程 _列出所有必要動作 _調整粒度大小 _排列先後順序</li>
<li>UI 規格 _13 x 4 排列 _卡片樣式 _圖檔連結 _預設字型 </li>
<li>第一張牌 _flex-basis、flex-grow、flex-shrink 設定卡片比例 _:last-child選擇器和transform屬性製作倒轉的卡片數字</li>
<li>動態產生卡片元素 _ view模組處理顯示畫面 _分拆函式 _卡片花色與數字的換算邏輯</li>
<li>產生 52 張牌 _Array.from(Array(52).keys())生成連續數字陣列</li>
<li>現成的洗牌演算法 _Fisher-Yates Shuffle 洗牌演算法 _ES6 的解構賦值語法 _不可省略的分號 _utility模組存放專案的工具函式</li>
<li>點擊時翻牌 _querySelectorAll 和 forEach 產生事件監聽器 _構思並實作「翻牌」邏輯 _釐清data-set設置資料的位置 _分工函式</li>
<li>「狀態」是什麼？ _狀態管理 (state management) _判斷遊戲流程，並抽取出不同的遊戲狀態</li>
<li>程式碼模組化 _程式碼模組化的概念與重要性</li>
<li>設定遊戲狀態 x 建立 MVC 架構 _設定遊戲狀態 _建立 model 模組統一管理資料</li>
<li>Controller 統一發派動作 _controller 統一發派任務給 view 和 model</li>
<li>配對成功 / 失敗 _遊戲狀態控制遊戲流程 _資料的程式碼歸類在 model _視覺的程式碼歸類在 view _由controller 統一調度動作</li>
<li>重構函式 _介面優化 _減少重複動作 _展開運算子…改寫 flipCard 和 pairCard _this和 setTimeout 搭配使用的問題</li>
<li>介面加入標頭</li>
<li>分數與嘗試次數</li>
<li>配對失敗加入 CSS 動畫</li>
<li>遊戲結束畫面</li>
</ol>
