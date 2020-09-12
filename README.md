# Cách chia component trong ReactJS

## Hai loại components

- **Container** : Smart component
    - Quản lý , xử lý dữ liệu
    - Không quan tâm render UI ntn
    - Chỉ quan tâm render cái gì
    - Có thể chứa container con và các components

- **Component** : Dumb component
    - Có gì render đó
    - Không biết dữ liệu đến từ đâu
    - Thường chỉ có props , kongo có state
    - Tái sử dụng , với props khác nhau , render khác nhau