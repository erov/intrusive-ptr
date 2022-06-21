# intrusive-ptr

Реализация
[intrusive_ptr](https://www.boost.org/doc/libs/1_71_0/libs/smart_ptr/doc/html/smart_ptr.html#intrusive_ptr) 
и [intrusive_ref_counter](https://www.boost.org/doc/libs/1_71_0/libs/smart_ptr/doc/html/smart_ptr.html#intrusive_ref_counter), 
а также некоторых вспомогательных утилит (операторы, API счётчика).

`intrusive_ref_counter` имеет единственную политику потокобезопасности, 
аналогичную (и не уступающую в эффективности) `boost::thread_safe_counter`. 
