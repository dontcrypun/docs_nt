# Cài đặt GitBook

🧰 Bước 1: Cài đặt môi trường
## 1.1. Cài Node.js phiên bản 10 (nên dùng nvm để dễ quản lý):
 
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

```bash
nvm install 10
```

```bash
nvm use 10
```
## 1.2. Cài GitBook CLI

```bash
npm install -g gitbook-cli
```
## 1.3. Kiểm tra phiên bản GitBook CLI đã cài đặt

```bash
gitbook -V
```
## 1.4. Cài đặt GitBook

```bash
gitbook install
```

## 1.5. Sử dụng GitBook

```bash
gitbook serve
```
