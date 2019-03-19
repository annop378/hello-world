#  公告
課程:107-2資料科學程式設計 學生:蕭妤安 學籍:土木系交通組碩一 學號:R07521509
    
### 20190317-學習R
小語法

>1. trycatch

    類似python的 try except

>2. paste0

    如果不想要有任何分隔符號，可以使用 paste0 這個函數
    paste0("Hello", "World")--> HelloWorld
    
>3. grepl

    grepl(pattern, x, ignore.case = FALSE, perl = FALSE,fixed = FALSE, useBytes = FALSE
    grepl 使用二分法 TRUE 或者 FALSE 表達在指定條件”pattern”下，指定範圍 x 裡是否有符合的字元。
    
>4. readLines()

     用在一筆一筆讀入這份資料，函數回傳的物件是一個文字的向量，每個索引值就是原始文字檔中的一筆資訊，假使原始文字檔非常龐大，我們可以加入參數 n 來限      定讀入的筆數：
     readLines(file_path,n=2)
     
>5. replace_non_ascii 

    - Replaces common non-ASCII characters
    replace_non_ascii(x, replacement = "", remove.nonconverted = TRUE, ...)
    x:The text variable.、replacement:Character string equal in length to pattern or of length one which are a replacement for matched         pattern.、remove.nonconverted、logical. If TRUE unmapped encodings are deleted from the string.
    
>6. lapply

     
    


