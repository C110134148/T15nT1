## 112-1 系統分析與設計
### 甲班第十五組 ＋ 乙班第一組
### 專題名稱： **智慧零售系統**
### 專題簡介：
在現今科技當道的世代，隨著電商、行動購物、D2C（Direct to Customer）等銷售模式崛起，讓消費者期待在線上、線下都能獲得更好的服務，這樣令到許多傳統零售品牌的地位受到挑戰。加上 2020 年疫情爆發，台灣實體零售的整體業績僅成長0.2%，電商銷售卻逆勢成長16.1%，讓品牌不得不轉型智慧零售，加強服務全通路消費者。另外，A公司是在即食肉品零售市場發展已成熟時才進入市場的競爭者，通路銷售平台及產品數量卻都不及目前市場上的主要競爭者，難以在市場上立足。而且A公司現時使用較低成本的手動記帳及貨物盤點已經過時，過慢的流程也不合乎成本效益。為了方便A公司能靈活善用科技帶來的好處及提升該公司的品牌知名度，我們這次為A公司制定行銷策略，導入智慧銷售系統提升銷售競爭力。

---
### 本組組員名單：
|班別|學號|姓名|帳戶名稱|
|:-----:|:-----:|:-----:|:-----:|
|三甲|C110134148|**梁詩敏**（甲班組長）|C110134148|
|三乙|C110118260|李俊賢（乙班）|C110118260|      
|四丙|B111118301|**司徒嘉略**（乙班組長）|Ssutu|

---

 # <Center> 
|      任務   |     說明      |  需時(天) | 前置任務|人員|
|:-------------:|:-------------| :-----:|:-----:|:-----:|
| 1 |尋找動機 | 1 | - |李俊賢 |
| 2 |研擬計畫 | 2 | 1 |司徒嘉略 |
| 3 |任務分配 | 1 | 2 |梁詩敏 |
| 4 |資料蒐集 | 7 |  3 |全員 |
| 5 |資料整合 | 1 |  4 |梁詩敏 |
| 6 |系統開發 | 21  | 5 | 梁詩敏、李俊賢 |
| 7 |系統界面設計 | 5  | 6 | 司徒嘉略 |
| 8 |系統測試和修改 | 14 |  7 |全員 |
| 9 |撰寫使用者手冊 | 3 |  8 |李俊賢、司徒嘉略 |
| 10 |使用者訓練 | 14 |  9 |全員 |
| 11 |最終使用者測試 | 14|  10  |全員 |

## 甘特圖
```mermaid
    gantt
        title 甘特圖
        研擬主題     : a1, 2023-10-1 ,1d
        研擬計畫     : a2, after a1 , 2d
        任務分配     : a3, after a2 , 1d
        資料蒐集     : a4, after a3 , 7d
        資料整合     : a5, after a4 , 1d
        系統開發     : a6, after a5 , 21d
        系統界面設計 : a7, after a6 , 5d
        系統測試     : a8 ,after a7 , 14d
        撰寫使用者手冊: a9 ,after a8 , 3d
        使用者訓練   : a10 ,after a9 , 14d
        使用者測試   : a11, after a10 ,14d
```
## PERT圖
![pert](https://github.com/C110134148/T15nT1/blob/320b17b1985d9397d66003bce753a1a331252cf0/PERT_Group_version1.jpg)

## 關鍵路徑
關鍵路徑： 1 → 2 → 3 → 4 → 5 → 6 → 10 → 11


```mermaid
    gantt
        title 即食雞胸肉探索——尋覓創新商機
第一階段    : c1, 2023-09-15 ,42d
第二階段    : c2, 2023-11-15 ,51d
探索    : b1, 2023-09-15 ,12d
探索    : b5, 2023-10-25 ,9d
定義    : b2, after b5,14d
發展    : b3, after b2 ,28d
實行    : b4, after b3 ,21d
        研擬主題     : a1, 2023-09-15 ,2d
        田野調查     : a2, after a1 , 3d
        初步討論     : a4, after a2 , 2d
        整合提案     : a5, after a4 , 5d

        提案延長修正  : a25, after a5 , 30d

        初步資料蒐集    : a3, after a1 , 10d
        分向討論     : a6, 2023-10-25 , 2d
        初步領域分析     : a8 ,after a6 , 7d
        蒐集數據及資料 : a7, 2023-10-25 , 22d

        現況領域延伸     : a9, after a8 , 8d
        會合討論     : a10, after a9 , 1d
        現況領域整合     : a11, after a9 , 5d
        現況定義 : a12, after a11 , 1d

        創作資料蒐集     : a13 ,after a12 , 18d
        創作領域分析: a14 ,after a12 , 9d
        會合討論     : a16, after a14 , 1d
        創新領域延伸   : a15, after a14 ,9d
        會合討論: a18 ,after a15 , 1d
        創作領域整合: a17 ,after a15 , 9d
        創作展示討論: a19 ,after a17 , 1d

創新領域篩選: a20 ,after a19 , 2d
方案設計: a21 ,after a20 , 10d
方案篩選: a22 ,after a21 , 2d
方案調整: a23 ,after a21 , 4d
整合計劃: a24 ,after a23 , 5d
```
