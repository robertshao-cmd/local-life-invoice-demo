# 🌐 local-life-invoice-**DEMO**（公開原型鏡像）

> ## ⚠️ 這裡不是原始碼 repo
> 這個 repo **只放可公開展示的原型**，是由私有主 repo 自動產生的鏡像。
> **不要在這裡改東西**——下次發佈會整個覆蓋掉。
>
> | | repo | 放什麼 |
> |---|---|---|
> | 🔒 **主 repo（私有）** | `local-life-invoice` | 原始碼、產品文件、決策、實驗、規格、內部研究 |
> | 🌐 **本 repo（公開）** | `local-life-invoice-demo` | 只有原型頁面，給主管與商家點開看 |

## 直接點開

| 入口 | 用途 |
|---|---|
| **[總覽導覽頁](https://robertshao-cmd.github.io/local-life-invoice-demo/)** | 所有原型的入口 |
| [到店實測版](https://robertshao-cmd.github.io/local-life-invoice-demo/consumer/nnw-store-test.html?store=nuan) | 真掃碼 → 解析點到桌卡 → 跳正式點餐頁 |
| [暖暖窩活動頁](https://robertshao-cmd.github.io/local-life-invoice-demo/consumer/activity-nnw-gift.html) | 憑發票贈品活動全鏈路 7 畫面 |
| [商家工作台](https://robertshao-cmd.github.io/local-life-invoice-demo/merchant/merchant.html) | 助手／生意參謀／用戶端預覽 |
| [小程序架](https://robertshao-cmd.github.io/local-life-invoice-demo/mini/) | 解毒吧 · 幾歲破產 · 無聊快篩 |
| [用戶體驗版](https://robertshao-cmd.github.io/local-life-invoice-demo/consumer/app.html?v=6.19) | 消費者主線 |

## 怎麼更新

在**主 repo** 改 `prototypes/`，然後：

```bash
python scripts/publish-demo.py
```

發佈前會自動掃描個資與憑證，掃到就中止。

---
*內部示範用途，不含真實個資或憑證。CDN 傳播最長約 10 分鐘，看到舊畫面請加 `?v=` 重試。*
