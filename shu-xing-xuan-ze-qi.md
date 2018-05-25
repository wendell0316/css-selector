### 属性选择器
> CSS 属性选择器通过已经存在的属性名或属性值匹配元素。

* [attr]
    表示带有以 attr 命名的属性的元素。
    
* [attr=value]
    表示带有以 attr 命名的，且值为"value"的属性的元素。
    
* [attr~=value]
    表示带有以 attr 命名的属性的元素，并且该属性是一个以空格作为分隔的值列表，其中至少一个值为"value"。
    
* [attr|=value]
    表示带有以 attr 命名的属性的元素，属性值为“value”或是以“value-”为前缀（"-"为连字符，Unicode编码为U+002D）开头。典型的应用场景是用来来匹配语言简写代码（如zh-CN，zh-TW可以用zh作为value）。
    
* [attr^=value]
    表示带有以 attr 命名的，且值是以"value"开头的属性的元素。
    
* [attr$=value]
    表示带有以 attr 命名的，且值是以"value"结尾的属性的元素。
    
* [attr*=value]
    表示带有以 attr 命名的，且值包含有"value"的属性的元素。
    
* [attr operator value i]
    在带有属性值的属性选型选择器表达式的右括号（]括号）前添加用空格间隔开的字母i（或I）可以忽略属性值的大小写（ASCII字符范围内的字母）
    

