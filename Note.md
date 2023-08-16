# Ưu điểm
- Code UI tách biệt với gameplay
# Nhược điểm
- Code cần tối ưu hơn. VD hàm GetPotentialMatches()
# Cây thư mục
- Assets
    - _Root
        - Scripts
            - Controllers
            - Editors
            - UIs
            - Utils
        - Textures
        - Scenes
        - Prefabs
        - Settings
# Đề xuất
- Dùng singleton pattern cho controller
- Dùng lớp static riêng cho PlayerPrefs