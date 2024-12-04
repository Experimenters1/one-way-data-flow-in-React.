# [one-way-data-flow-in-React.](https://chatgpt.com/c/675011ac-bc5c-8003-b273-a290be5d4768) <br><br>

## one-way data flow in  React
#### Cha → Con: Props.
#### Con → Cha: Callback data (Dữ liệu trả về từ hàm callback). 
### Component Cha (Parent Component): 
+ )Là component chứa một hoặc nhiều **component con** bên trong nó.<br><br>
**+ )Trách nhiệm chính:** <br><br>
    - ) Quản lý logic chính, dữ liệu (state), hoặc xử lý giao tiếp giữa các component con.
    - )Truyền dữ liệu xuống component con thông qua **props.**
  
### Component Con (Child Component):
+) Là component được bao bọc hoặc được gọi từ một component cha.
**+ )Trách nhiệm chính:** <br><br>
     - ) Quản lý logic chính, dữ liệu (state), hoặc xử lý giao tiếp giữa các component con.
    - )Truyền dữ liệu xuống component con thông qua **props.**
