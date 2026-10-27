# HDBank · Xếp hạng app

Dashboard thứ hạng lượt tải và rating của app HDBank so với các app ngân hàng (nhóm Banking, Việt Nam) trên App Store và Google Play.

Trang: https://hdb-digital.cloud/app-ranking/

- Nguồn: Sensor Tower API. Lượt tải là số ước tính của Sensor Tower.
- `data.json` chỉ chứa bản mã (AES-256-GCM, khóa từ mật khẩu bằng PBKDF2-SHA256); trang giải mã trên trình duyệt sau khi nhập mật khẩu.
- Dữ liệu được dựng và đẩy lên từ máy của đội Digital Marketing (`update.py --push`).
