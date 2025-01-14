
# Web Dashboard for Azure AI OCR Service


### [描述]

本專案是一個基於 Flask 和 Azure AI OCR 建立的 Web 服務，用於單據辨識。

### [雲端部屬架構]
![OCR Flow Diagram](https://github.com/mythzaizai/AcerAEB_OCR_Service/blob/main/OCR_flow.jpg)
ps.本專案亦可在本地執行

## Download & Installing

1. 下載此專案並切換至根目錄:
```bash
cd web_dashboard
```
2. 確保你已經安裝了 Python 3.9。
3. 安裝所需的 Python 套件：

```bash
pip install -r requirements.txt
```

## Usage

1. 運行 Flask 應用：

```bash
python -m flask run
```

2. 打開瀏覽器並訪問 [http://127.0.0.1:5000](http://127.0.0.1:5000) 來訪問 Web 服務的主頁面。

## Docker

如果你想使用 Docker 來運行這個服務，你可以使用以下命令來建立和運行一個 Docker 容器：

1. 確保你已經安裝了 Docker 。
2. 執行以下命令：
```bash
docker build -t web_dashboard .
docker run -p 80:80 web_dashboard
```

打開瀏覽器並訪問 [http://127.0.0.1](http://127.0.0.1) 來訪問 Web 服務的主頁面。

## Demo Video
[OCR-service Demo](https://www.youtube.com/watch?v=ZOiamGDrQxI)

## References
- [Azure OCR - Optical Character Recognition](https://learn.microsoft.com/zh-tw/azure/ai-services/computer-vision/overview-ocr)
- [Azure web app (Flask)](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-cli%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli)

## Contact

如果有任何問題或建議，請聯繫專案開發者:

- **Email**: mythzaizai@gmail.com


