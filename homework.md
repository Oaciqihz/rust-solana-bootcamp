# 1 Module One Homework

```
一、题目描述
请尝试设计并实现一个简易的图书管理系统，该系统允许用户添加、查询、删除图书，同时支持根据自定义条件对图书进行排序和搜索。每本图书包含书名、作者、ISBN号、出版年份和状态（在库、借出）。系统应提供以下高级功能：

1 添加图书：允许用户输入图书的详细信息并保存。
2 泛型查询功能：根据书名、作者或ISBN号查询图书。使用泛型函数支持不同类型的查询标准。
3 删除图书：根据ISBN号删除图书记录。
4 借出与归还：更改图书的状态为借出或在库。
5 自定义排序：允许用户根据自定义条件（如按出版年份、书名）对图书集合进行排序。使用闭包实现排序逻辑。

二、知识点覆盖
基础和复合数据类型：利用整数、字符串等存储图书信息。
字符串处理：管理图书的书名和作者等信息。
引用：在处理图书信息时，使用引用以提高效率。
结构体和枚举：通过结构体定义图书信息，使用枚举表示图书状态。
集合：采用Vec或HashMap存储所有图书信息，便于管理和查询。
泛型：实现一个泛型查询函数，支持根据不同的标准搜索图书。
闭包：实现一个接受闭包参数的函数，根据用户定义的逻辑对图书进行排序。
模式匹配
注释

三、实现提示
定义Book结构体和Status枚举来存储图书信息和状态。
使用Vec<Book>或HashMap<String, Book>来存储图书馆中的图书。
实现添加、查询、删除、借出与归还图书的功能。
使用泛型函数来实现灵活的查询功能，该函数应能接受不同类型的搜索标准。
使用闭包来实现自定义排序功能，允许用户根据不同的逻辑来排序图书。

四、题目要求
使用Rust编程语言完成设计和实现。
代码应具有良好的结构和注释，易于理解和维护。
确保代码能够正确执行上述功能，并通过简单的命令行界面进行交互。
大家可以组团实现，实现主要逻辑或者实现部分功能即可，可以参考其他书籍以及使用ChatGPT辅助完成。
```
