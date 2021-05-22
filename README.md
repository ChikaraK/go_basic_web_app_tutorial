 ## Go-Basic-Web-App
 こちらのチュートリアルをdocker環境でこなしただけです。
https://golang.org/doc/articles/wiki/

 ### 手順
 $docker-compose build
 $docker-compose up -d
 $docker-compose exec go go run main.go

 ブラウザから
 localhost:8888/view/yourFavoriteName
 ->/edit/yourFavoriteNameへリダイレクトされます
 ->適当な内容でsaveボタンをクリック
 ->/go_basic_web_app/app/yourFavoriteName.txtが作成されます
 ->localhost:8888/edit/yourFavoriteNameで変更できます
