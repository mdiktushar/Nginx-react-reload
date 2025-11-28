# Nginx-react-reload

  # 👇 Add this block to fix React reload errors
  location / {
    try_files $uri /index.html;
  }
}
