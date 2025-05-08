
# Hướng dẫn cài đặt và chạy chương trình

Để clone và chạy chương trình, cần phải cài đặt **Git LFS** vì dự án này có các tệp lớn (như hình ảnh, video) được theo dõi bởi Git LFS.

## Bước 1: Cài đặt Git LFS

1. **Tải Git LFS**:
  Mở Git Bash và chạy:
  git lfs install

## Bước 2: Clone Project


### Lưu ý: Sau khi clone, Git LFS sẽ tự động tải các tệp lớn (như hình ảnh, video) vào thư mục .

## Bước 3: Mở và chạy chương trình

1. Mở tệp **`start.html`** trong Visual Code.
   - Vào Visual Code, chuột phải vào 'start.html' và chọn  Open with Live Server

2. Nếu bạn thấy các tệp bị thiếu hoặc không thể hiển thị đúng, hãy chắc chắn rằng bạn đã cài đặt Git LFS và clone dự án đúng cách.

## Các bước phát triển thêm

- Nếu bạn muốn phát triển thêm tính năng, hãy chắc chắn rằng bạn có Git LFS cài đặt để có thể theo dõi các tệp lớn.
- Để thêm tệp mới vào Git LFS, sử dụng lệnh:
  ```bash
  git lfs track "*.mp4"
  git lfs track "*.jpg"
  git lfs track "*.png"
  ```

