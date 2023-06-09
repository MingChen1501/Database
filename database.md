# Cơ Sở Dữ Liệu

## Các bước thiết kế CSDL

1. Thiết kế khái niệm

2. Thiết kế Logic

3. Thiết kế vật lý

## Quy trình thiết kế CSDL (ref: microsoft)

* Xác định yêu cầu:

1. Xác định thực thể (entities)

2. Xác định relationships giữa các entities

* Xây dựng sơ đồ ERM (entity relationship model)

1. Note: entity relationship diagram vs entity relationship model

* Xác định khóa chính PK

* Xác định các mối quan hệ (FK)

1. 1-1
2. 1-n
3. N-n

* Chuyển sơ ERM sang ERD

* Xác định các thuộc tính

* Chuẩn hóa

1. Xác định ràng buộc constrant (unique, check, fk, …)

## Các thuật ngữ

* Database

* Table (danh từ) - blueprint

* Column: field, attribute

* Row: record - instance

* PK

* FK

* Null

* Relationship

1. one to one

2. one to many

3. many to many

        cần junction table (bảng trung gian giữa 2 table)
4. Self referencing relationship

        +-------------------+
        |      Nhân viên    |     
        +-------------------+
        | ID nhân viên      |     
        | Tên               |     
        | Địa chỉ           |     
        | ID người quản lý  |
        +-------------------+
5. composite relationship

## Thực hành phân tích và vẽ ERM trên app.diagram
