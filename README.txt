Cấu hình <config> cho  tailwind
- npm init -y
- npm install -D tailwindcss postcss autoprefixer vite
- npx tailwindcss init -p
sửa file config papcket.json thành dev:"vite"
- npm run dev

add thêm thư mục css
- Thêm ở file tailwind.css: 
@tailwind base;
@tailwind component;
@tailwind utilities;    

chạy dòng lệnh npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css