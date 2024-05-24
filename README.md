# API-Testing
## Giới thiệu
Mục tiêu của bài tập này là thực hành kiểm thử API bằng cách sử dụng Postman. Bài tập bao gồm các bước từ việc lựa chọn một API kiểm thử, phân tích tài liệu API, viết các trường hợp kiểm thử, thực hiện kiểm thử và ghi lại kết quả kiểm thử.
## API Được Chọn
API được lựa chọn cho bài tập này là Random Data API, một API phổ biến cung cấp dữ liệu cho người dùng.

## Thực Hiện Các Trường Hợp Kiểm Thử với Postman
### Trường Hợp Kiểm Thử 1:
Điểm cuối: https://random-data-api.com/api/v2/users
Phương thức: GET
### Trường Hợp Kiểm Thử 2:
Điểm cuối: https://random-data-api.com/api/v2/beers
Phương thức: GET
### Trường Hợp Kiểm Thử 3:
Điểm cuối: https://random-data-api.com/api/v2/beers?beerType=light
Phương thức: GET
## Kết Quả Kiểm Thử
### Trường Hợp Kiểm Thử 1
![441093586_966868748469783_7529379219081686050_n](https://github.com/thangthanhthien/API-Testing/assets/170683134/c2b2c220-e2b5-4a5f-b6f2-0dafec086b12)

{ "id": 2547, "uid": "f1732e8c-bc0e-49b4-8c0b-9d13d35e1d4f", "password": "JpOFdWjvIa", "first_name": "Amado", "last_name": "Konopelski", "username": "amado.konopelski", "email": "amado.konopelski@email.com", "avatar": "https://robohash.org/quialaboriosamsoluta.png?size=300x300&set=set1", "gender": "Male", "phone_number": "+680 (466) 677-6873", "social_insurance_number": "197915366", "date_of_birth": "1971-01-23", "employment": { "title": "Legal Engineer", "key_skill": "Confidence" }, "address": { "city": "Williamsontown", "street_name": "Wilkinson Expressway", "street_address": "6901 Hand Flats", "zip_code": "35831-2343", "state": "West Virginia", "country": "United States", "coordinates": { "lat": 24.275668381333574, "lng": -97.87772722028215 } }, "credit_card": { "cc_number": "6771-8949-0415-2956" }, "subscription": { "plan": "Premium", "status": "Idle", "payment_method": "Visa checkout", "term": "Payment in advance" } }

## Trường Hợp Kiểm Thử 2
![436714019_821295563247475_5063052654491125407_n](https://github.com/thangthanhthien/API-Testing/assets/170683134/9ad8d21d-5ff3-43ce-8e7e-0aa4b39a575b)
{ "id": 4950, "uid": "686e2916-c615-43ea-a702-ad1f4f90bc7c", "brand": "Lowenbrau", "name": "Samuel Smith’s Oatmeal Stout", "style": "Smoke-flavored", "hop": "Saaz", "yeast": "3278 - Belgian Lambic Blend", "malts": "Victory", "ibu": "50 IBU", "alcohol": "3.1%", "blg": "13.3°Blg" }

## Trường Hợp Kiểm Thử 3
![438171578_459926026531889_7087616726756932720_n](https://github.com/thangthanhthien/API-Testing/assets/170683134/6169b477-2206-4dbb-b542-068be15cbda7)

{ "id": 925, "uid": "b81051ae-7ae4-4354-9b7f-d867553f2cd5", "brand": "Tsingtao", "name": "Maudite", "style": "Amber Hybrid Beer", "hop": "Santiam", "yeast": "2278 - Czech Pils", "malts": "Black malt", "ibu": "15 IBU", "alcohol": "5.9%", "blg": "11.1°Blg" }

## Mục Tiêu Kiểm Thử:
Xác định và xác thực các phản hồi của Random Data API dựa trên các truy vấn khác nhau.

## Kết Quả Kiểm Thử:
Tất cả các trường hợp kiểm thử được thực hiện và kết quả phù hợp với mong đợi.

## Khuyến Nghị:
API hoạt động tốt
