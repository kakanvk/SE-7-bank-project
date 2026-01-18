FROM nginx:alpine

# Xóa config mặc định
RUN rm /etc/nginx/conf.d/default.conf

# Copy cấu hình nginx hỗ trợ SPA
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy static files
COPY . /usr/share/nginx/html

EXPOSE 80
