<h1>Hello, World!</h1>

Deploy:
- Tạo repository trên Docker Hub để setup github workflow trên Github.
- Tạo Slack Webhook để setup github workflow trên Github.
- Setup variable cho repository trên Github.
- Push code lên Github.
- Chuẩn bị trước khi build:
    - Tạo folder/file life_replay/traefik chứa các cấu hình cần thiết trước cho Traefik.
    - Tạo folder/file life_replay/be_admin_service/config/config.json chứa cấu hình port internal là 8000.
    - Tạo folder/file life_replay/be_notification_service/config/config.json chứa cấu hình port internal là 8000.
- Build từng service từ trên xuống (vì đây là bản demo nên dùng domain free).