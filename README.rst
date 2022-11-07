Google 圖片下載
######################

Step1. cd google_images_download
=============

example1 . 指令限制200張 並調用chromedriver
python google_images_download.py -k "cucumbet plant in farm" -l 200 --chromedriver="C:/chromedriver"

==========

範例2: 指定限制200張 調用 chromedriver 並限制只取jpg 且指定google url圖片頁面下載連結

python google_images_download.py -k "cucumbet plant in farm" -l 400 --chromedriver="C:/chromedriver" -f  "jpg" -u "https://www.google.ca/search?q=cucumber+plant+in+farm&tbm=isch&hl=en&authuser=0&sa=X&ved=2ahUKEwjS24rY6Zr7AhWSZt4KHXBRD4kQgowBKAB6BAgBEB4&biw=1269&bih=702" -is "test221107"
