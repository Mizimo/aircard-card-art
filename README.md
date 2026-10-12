# AirCard Card Art

收錄好看的 Apple Wallet 卡面，分享 PNG、分層 PSD 與製作方法。卡面可搭配 [AirCard](https://github.com/Mak5er/AirCard) 使用。

## 卡面

| Suica · DeepSeek 鯨魚娘 | PASMO · 千早愛音 |
| :---: | :---: |
| ![DeepSeek 鯨魚娘](artwork/suica-deepseek-whale-maid/deepseek-whale-maid-suica-layered-3c3fe760.png) | ![千早愛音](artwork/pasmo-chihaya-anon/pasmo-chihaya-anon-layered-20261012.png) |
| [PNG](artwork/suica-deepseek-whale-maid/deepseek-whale-maid-suica-layered-3c3fe760.png) · [PSD](artwork/suica-deepseek-whale-maid/deepseek-whale-maid-suica-layered-3c3fe760.psd) | [PNG](artwork/pasmo-chihaya-anon/pasmo-chihaya-anon-layered-20261012.png) · [PSD](artwork/pasmo-chihaya-anon/pasmo-chihaya-anon-layered-20261012.psd) |

[下載全部](https://github.com/Mizimo/aircard-card-art/releases/latest) · PNG 用來套用卡面，PSD 用來繼續修改。

## 製作方法

這兩款採用「分層生成，再手動排版」的方式：

1. **找參考**：準備原卡面與角色圖片，確認標誌排版和角色特徵。
2. **分開生成**：用 ImageGen 製作透明背景的人物層與獨立背景，預留標誌的位置。
3. **組合圖層**：在 Photoshop 建立橫向畫布（本作為 1579 × 996 px），分別放入背景、人物、標誌及裝飾。標誌從參考圖提取，保留字形比例。
4. **調整排版**：Suica 的玻璃梯形另外繪製，校正水平邊和圓角；PASMO 保留三行標誌，加入淡白漸層讓文字清楚。位置、大小與透明度在 PSD 裡調整。
5. **實機確認**：保留分層 PSD，匯出 PNG，透過 AirCard 套用後檢查圓角裁切、文字與人物是否被擋住。

<details>
<summary>生成提示詞範例</summary>

**人物層**

> 參照附圖的角色，保留髮型、服裝、表情與主要配件。製作橫向卡面的人物圖層，人物放在右側，左側預留卡片標誌的位置。輸出真正透明的背景，不要文字、標誌、卡片邊框或場景背景。

**背景層**

> 製作與角色配色相符的橫向卡面背景。左半保持簡潔、低對比，方便放標誌；右半可加入柔和光線與流動線條。只輸出背景，不要人物、文字、標誌或實體卡片樣機。

若已有喜歡的完整插畫，也可以要求分離人物、補齊背景，再把標誌與幾何形狀獨立重建。

</details>

## 實機效果

<details>
<summary>查看兩款卡面的實機演示</summary>

<table>
  <tr><th>Suica · DeepSeek 鯨魚娘</th><th>PASMO · 千早愛音</th></tr>
  <tr>
    <td valign="top"><img src="docs/demos/suica-deepseek-whale-maid-device.png" alt="Suica 實機效果" width="360"></td>
    <td valign="top"><img src="docs/demos/pasmo-chihaya-anon-device.png" alt="PASMO 實機效果" width="360"></td>
  </tr>
</table>

</details>

製作與整理：[Mizimo](https://github.com/Mizimo) · [AirCard 使用說明](https://github.com/Mak5er/AirCard) · [授權](LICENSE) · [來源與權利說明](NOTICE.md)
