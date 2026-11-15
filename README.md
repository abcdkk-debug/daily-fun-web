# 🌍 Daily Fun Web — 每日開放數據趣聞網頁

每日一期，用世界各地**開放數據平台**（open data platforms）的真實數據，整一版有趣網頁：排行榜、互動圖表、冷知識同小測驗。

重點係整**會用到呢啲數據的網頁**：揀真實數據集，將數據本身放入頁面入面用 — 即時讀取官方 API，或者嵌入已核實的數據集快照，再用圖表、排序、篩選等方式呈現同探索。

## 數據應用 Apps

| # | 應用 | 用到的數據 |
|---|---|---|
| 001 | [香港天氣即時版](apps/hk-weather-live.html)（同時係 2026-11-14 當日的 `index.html`） | 香港天文台開放數據 API（經 DATA.GOV.HK）：本港天氣報告 rhrread + 九天天氣預報 fnd，開啟頁面時即時讀取 |
| 002 | [USGS 地震即時版](apps/usgs-earthquakes-live.html)（同時係 2026-11-15 當日的 `index.html`） | USGS 地震 GeoJSON Feed「All Earthquakes, Past Day」：過去 24 小時 191 次地震，即時讀取 + M ≥ 4 快照，震級篩選/搜尋/排序 |

- `index.html` 就係**當日製作嗰一頁**（每日更新取代；今日 2026-11-15 係「USGS 地震即時版」）
- 📚 過往期數總覽：[archive/index.html](archive/index.html) — 網站每一頁開頭都有連結去到呢個總覽頁
- 歷史存檔：`archive/YYYY-MM-DD.html`；數據應用另存 `apps/`
- 🌐 公開網站（GitHub Pages）：https://abcdkk-debug.github.io/daily-fun-web/ — 打開就係當日嗰頁，每日更新

## 期數一覽

| 期 | 日期 | 主題 |
|---|---|---|
| 001 | 2026-11-14 | 全球開放數據大冒險 — 八大平台數據集數量大比拼（歐洲 1,856,048 / 美國 535,191 / 印度 181,444 / 英國 60,037 / 加拿大 47,930 / 日本 18,828 / 香港 5,800 / 新加坡 4,500+） |
| 002 | 2026-11-15 | 地球過去 24 小時震咗幾多次？— USGS 地震即時版（過去 24 小時 191 次，最大 M5.5 北大西洋中脊；M ≥ 4 共 19 次） |

## 資料原則

- 每期數字都注明來源平台同查核日期；各平台統計口徑唔同，數字只作趣味比較
- 來源包括 data.europa.eu、data.gov、data.gov.in、data.gov.uk、open.canada.ca、data.go.jp、data.gov.hk、data.gov.sg 等官方開放數據平台

由 K仔 每日製作。
