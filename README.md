# yolo5-line

virtualenv
- pip install virtualenv
- virtualenv line-yolo-api-venv
- line-yolo-api-venv\Scripts\activate.bat

install
- pip install -r requirements.txt
- pip install torch
- pip install torchvision

ngrok
(download : https://ngrok.com/download )
- ngrok http -region jp 8000

.env (file)
- LINE_CHANNEL_SECRET='<<Your Line Channel Secret>>'
- LINE_CHANNEL_ACCESS_TOKEN='<<Your Line Channel Access Token>>'

docker
- docker build --tag line-yolo-api:latest .
- docker run -p 8000:8000 -d --name line-yolo-api line-yolo-api

refference
- http://thannob.com/articles/%e0%b8%aa%e0%b8%a3%e0%b9%89%e0%b8%b2%e0%b8%87-API-%e0%b8%95%e0%b8%a3%e0%b8%a7%e0%b8%88%e0%b8%88%e0%b8%b1%e0%b8%9a%e0%b8%a7%e0%b8%b1%e0%b8%95%e0%b8%96%e0%b8%b8%e0%b8%94%e0%b9%89%e0%b8%a7%e0%b8%a2-YOLOv5-%e0%b8%9c%e0%b9%88%e0%b8%b2%e0%b8%99-LINE-(%e0%b8%95%e0%b8%ad%e0%b8%99%e0%b8%97%e0%b8%b5%e0%b9%88-1-deploy-%e0%b8%9a%e0%b8%99%e0%b9%80%e0%b8%84%e0%b8%a3%e0%b8%b7%e0%b9%88%e0%b8%ad%e0%b8%87%e0%b8%95%e0%b8%99%e0%b9%80%e0%b8%ad%e0%b8%87)/?fbclid=IwAR1jZysW0xCLBRYtiJ4ACsWA4PpzEQMRXHUMXB38aD_id-jO-0RBPy_dbxQ
- https://karnyong.medium.com/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-api-%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B8%88%E0%B8%B1%E0%B8%9A%E0%B8%A7%E0%B8%B1%E0%B8%95%E0%B8%96%E0%B8%B8%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-yolov5-%E0%B8%9C%E0%B9%88%E0%B8%B2%E0%B8%99-line-%E0%B8%95%E0%B8%AD%E0%B8%99%E0%B8%97%E0%B8%B5%E0%B9%88-2-deploy-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-docker-%E0%B8%82%E0%B8%B6%E0%B9%89%E0%B8%99-heroku-cloud-93aebc543bb7
