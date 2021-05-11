| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

# A6 餐廳清單擴充 CRUD 功能

> 💡  在寫這份作業之前，請你務必了解 <a href="https://github.com/Carrot7712/ALPHACamp_assignment_rubrics/blob/main/README.md" target="_blank">ALPHA Camp 作業回饋機制</a>，包括助教會如何批改你的作業，以及你該怎麼使用助教回饋來幫助自己進步

## 題幹
請參考課程平台([連結](https://lighthouse.alphacamp.co/courses/42/assignments/1038))。

## 指定規格與功能

1. 以 To-do List 為範例，建立資料庫並連線餐廳清單，打造完整的 CRUD 功能
2. 把這支 [restaurant.json](https://drive.google.com/file/d/1W-BD9-c8zJRYCwAD8yhqQdLwcUdN8GZi/view) 裡的資料當成種子資料，完成後新增 `npm run seed` 腳本
3. 前端頁面請參考上個章節的樣板 index page 與 show page，可自行發揮創意，優化使用體驗 (例如：點擊餐廳照片可直接進入 show page、或是在執行刪除前會瀏覽器會跳出提醒視窗等)

若成功完成指定規格，代表你能夠做到：

- 能夠跟資料庫 (MongoDB) 建立連線
- 能夠成功導入種子資料
- 能完成 CRUD 功能與路由設計
- 根據指定的設計稿完成畫面

<span style="font-size: 10px; color: #red">Note: 除了完成本章核心驗收標準「能夠設計並在正常情況下運作CRUD」，也期待開始意識到，程式開發不只是能夠運行功能	，且包含異常處理、功能可擴充、可維護性思維，以利後續具備規劃功能、優化功能、有品質交付等能力</span>

## 期待你現階段能做到....

<table>
  <thead style="font-weight: bold; border-bottom: 2px solid #999;">
    <tr>
      <td>觀察角度</td>
      <td>現階段期待你做到⋯⋯</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>開發框架應用</td>
      <td>
        <ul>
          <li>完成 CRUD 功能與路由設計</li>
          <li>建立 Express & MongoDB 的連線</li>
          <li>導入種子資料</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>程式架構與品質</td>
      <td>
        <ul>
          <li>遵守 JavaScript Standard style (建議安裝自動檢查套件)</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與動線</td>
      <td>
        <ul>
          <li>根據指定的設計稿完成畫面</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>開發實務 & 第三方工具應用</td>
      <td>
        <ul>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


若你的作業「指定規格」都完成，「期待結果」也沒有重大問題，助教會判定 `Meet Expectation`，代表你已經掌握了此階段的學習內容，可以繼續前進。

若助教發現你「沒有做到產品該有的規格」或是「犯了重大錯誤」，會給你 `Try Harder` 標記，提醒你停下來釐清問題。修正完成後，可以 tag 助教重新判定。

---
## 行有餘力，可參考優化方向
以下我們蒐集了過去學長姐在行有餘力時，會自行延伸學習的方向，並不是每個人現階段都需要攻略這些項目。

行有餘力時，你可以從下方挑選一些有共鳴的項目來優化作業，也歡迎你接續發想新的優化項目。不過請別忘記先守住上述的基本盤再來挑戰唷！

- 進階規格
- 程式架構與品質
- 視覺與動線
- 第三方 API 和工具應用







### Meet Expectation
若助教看見同學完成這些，會認定這份作業通過：

* 指定規格與功能
  * 能完成 CRUD 功能與路由設計
  * 使用 AC 提供的 templates，作了細微的修改
  * 能否順利跟資料庫 (MongoDB) 連線
  * 成功根據 To-do List 的教案完成一樣的 CRUD 功能
  * 成功導入種子資料
  * 根據指定的設計稿完成畫面
* 程式語法與邏輯
  * 透過 body-parser 從 POST 方法的路由中取得表單資料
  * 設計演算法，用 JavaScript 撰寫出符合產品需求的邏輯
* 資料結構的應用與處理
  * 
* 介面 / 使用者路徑
  * 
  
* Coding Style
  * 有意義的變數與函式命名
  * 符合 JavaScript Standard Style
  * 建立粒度適當的 git commit 與清楚簡潔的 commit message

### Exceed Expectation
當同學達成 Meet Expectation 的標準後，助教可以進一步建議同學：
* 有自己客製化/優化 AC 提供的頁面，設計亮眼，
* 有自己建構新的功能或互動設計，讓使用體驗更良好
* Coding Style
  * 有意義的變數與函式命名
  * 符合 JavaScript Standard Style
