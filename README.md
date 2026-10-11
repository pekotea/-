# -
關鍵字:YOLO 非接觸式 機器學習 影像辨識 幼兒照護

幾個參考資料
Predicting physical activity types in children aged 3–6 from video data using computer vision
https://link.springer.com/article/10.1186/s12889-026-26495-1?utm_source=chatgpt.com#Abs1

運用影像與深度學習技術的嬰幼兒安全監視系統 王賀群
https://hdl.handle.net/11296/qwm29w

工作方向
使用影像辨識幼兒行為並對相關資料進行分析，進而辨別出幼兒的需求
ex:當幼兒大哭時可能需要：進食、更換尿布、拍嗝、睡覺、陪伴...
我遇到的問題：時間不夠、實作上困難(找不到實驗對象)

# Plan B:基於機器學習進行未來就業人口模擬以及量化行業風險

## 可使用資料集:
台灣
人力資源調查勞動力人數:https://data.gov.tw/dataset/6796
就業者之行業:https://data.gov.tw/dataset/34113

美國
https://fred.stlouisfed.org/tags/series?t=bls%3Bemployment

## 分析方法與模型建置
時間序列分析：運用 ARIMA、SARIMA 等模型，針對歷史失業率進行短期內的季節性與趨勢預測。

計量經濟與因果推論模型：建構向量自我迴歸模型（VAR）或面板資料分析（Panel Data），評估總體經濟變數對特定產業就業率的落後衝擊與關聯性。

"機器學習與深度學習"：使用 XGBoost、Random Forest 或長短期記憶網路（LSTM），處理高維度的非線性特徵，以捕捉複雜的經濟結構轉變與失業率轉折點。

## 變數建置與特徵工程
宏觀經濟指標：加入 GDP 成長率、消費者物價指數（CPI）、利率、匯率及景氣對策信號燈，作為影響就業市場的外部環境變數。

勞動市場領先指標：計算如「平均失業週數」、「初次申請失業給付人數」或「職缺填補率」，這些往往比失業率本身更能預兆未來的趨勢反轉。

結構性指標：量化產業數位化程度、自動化風險或特定新興技術（如 AI 相關職缺佔比）的成長曲線。

## 研究目的
國外已經有相關的研究跟商業平台，以HR或是決策制定的立場出發進行分析，但我想要做的是以民眾的立場出發對台灣的未來就業趨勢進行預測跟分析。
