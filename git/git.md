# Sử dụng git

* Xử lý `CONFLICT`
    - lấy code của người khác
    ```sh
    git checkout --theirs /path/of/file.php
    ```
    - lấy code của mình
    ```sh
    git checkout --ours /path/of/file.php
    ```
Sau đó `add` file và `commit` như bình thường