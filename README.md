#  公告
課程:107-2資料科學程式設計 學生:蕭妤安 學籍:土木系交通組碩一 學號:R07521509
### Week3
>1. 狄利克雷分析
>2. 探勘對象
		離群值?藥品多給屬性(性別、年齡、多寡...)?
>3. LDA
		Hightly(分類)
		
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

    lapply函数是一个最基础循环操作函数之一，用来对list、data.frame数据集进行循环，并返回和X长度同样的list结构作为结果集，通过lapply的开头的第一个     字母’l’就可以判断返回结果集的类型。
    lapply(X, FUN, ...)
    X:list、data.frame数据、FUN: 自己定義的函數、…: 更多参数，可选
     
>7. unlist

    unlist(x, recursive = TRUE, use.names = TRUE)
    
>8. slappy

    sapply(X=1:10, FUN=function, ..., simplify = TRUE, USE.NAMES = TRUE)
    
>9. order

    order()即排序的函數，根據value值，返回值則是index。
    
>10. Sys.setlocale(category = "LC_ALL", locale = “UTF-8")

    中文轉換為英文
   
>11. Sys.setlocale(category = "LC_ALL", locale = "cht")

    英文轉換為中文

--------------------------------------------------------------------------------------------------------------------------------------

爬蟲

>1. read_html()

    使用 read_html 函數先將整個網頁的原始 HTML 程式碼抓下來：
    page.source <- read_html("https://en.wikipedia.org/wiki/R_(programming_language)")
    
>2. html_nodes 函數

    配合 CSS 選擇器將指定的資料取出來：
    

    


