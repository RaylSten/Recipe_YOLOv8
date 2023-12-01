# Recipe_YOLOv8

## 目的說明
可以參考 Recipe.pdf 檔案中的說明。

## 資料夾說明
runs 用來存放訓練好的模型(.pt檔)：
路徑 >> runs/detect/train13/weights/best.pt

## app說明
app.py 是用來架網站的 code，裡面的 cfg_model_path 是用來導向模型的路徑。

如果要打開網站，需要先從 cmd 打開這份資料夾(Recipe_YOLOv8)，然後輸入 `python -m streamlit run app.py`，之後就可以上傳照片，並跑出偵測後的結果。

## 重要事項
requirements 是用來跑 YOLOv8 模型的套件配置，在跑程式之前要確定 python 環境有安裝符合版本需求的套件。# Recipe_YOLOv8
