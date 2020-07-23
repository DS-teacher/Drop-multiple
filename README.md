# 带有搜索框、全选按钮的多选下拉框
+ input search属性自带一个删除按钮，非文档流内元素  
  删除方法
  ```
  input[type="search"]::-webkit-search-cancel-button {
    display: none;
  }
  ```
