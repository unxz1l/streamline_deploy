# 餐飲業財務分析網頁應用

這是一個使用 Streamlit 開發的餐飲業財務分析網頁應用，可以幫助投資者分析台灣主要餐飲上市公司的財務狀況。

## 功能特點

- 多公司財務指標比較
- 互動式趨勢圖表
- 年度財務比較表格
- 風險與亮點分析
- 公司基本資訊展示

## 支援的公司

- 美食-KY (2723)
- 王品 (2727)
- 瓦城 (2729)
- 六角 (2732)
- 漢來美食 (1268)

## 安裝說明

1. 克隆此倉庫：
```bash
git clone [repository-url]
cd streamlit_deploy
```

2. 安裝依賴：
```bash
pip install -r requirements.txt
```

3. 運行應用：
```bash
streamlit run app.py
```

## 使用說明

1. 在側邊欄選擇要分析的公司
2. 選擇時間範圍（近5年或近10年）
3. 選擇要分析的財務指標
4. 查看趨勢圖表和詳細分析

## 技術棧

- Python
- Streamlit
- Pandas
- Plotly
- NumPy

## 授權

MIT License

## 本地運行

1. 安裝依賴：
```bash
pip install -r requirements.txt
```

2. 運行應用：
```bash
streamlit run app.py
```

## 部署到 Streamlit Cloud

1. 將代碼推送到 GitHub 倉庫

2. 訪問 [Streamlit Cloud](https://streamlit.io/cloud)

3. 點擊 "New app"

4. 選擇你的 GitHub 倉庫

5. 選擇 `app.py` 作為主文件

6. 點擊 "Deploy"

## 數據文件

確保在 `output` 目錄下有 `selected_companies_financials.csv` 文件，該文件包含所需的財務數據。

## 注意事項

- 確保所有依賴版本與 `requirements.txt` 中指定的一致
- 數據文件需要定期更新以保持分析結果的時效性
- 建議使用 Python 3.8 或更高版本 