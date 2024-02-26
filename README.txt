# npm init -y: Khởi tạo file package.json
# typescript: giúp chuyển đổi ngôn ngữ typescript -> javascript
- Vì trình duyệt chỉ hiểu javascript
# npx tsc --init: Để tạo ra file config cho typescript
# npx tsc src/index.ts: chuyển đổi từ ngôn ngữ typescript về javascript.
# npx tsc src/index.ts -w: theo dõi tự động chuyển đổi code ts -> js
# Cách tạo folder bundler riêng:
- "outDir": "./dist", 
- "rootDir": "./src",

# Trình duyệt không hiểu ngôn ngữ typescript
- phải có một bước trung gian để chuyển đổi từ ts -> js để trình duyệt có thể hiểu được.