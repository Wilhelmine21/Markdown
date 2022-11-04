# Markdown 簡介
* 特色: 易讀易寫
* 部分可使用html語法
## 目錄
1. [Markdown 基本語法](https://github.com/Wilhelmine21/Markdown#1-Markdown-基本語法)  
    1-1. [標題](https://github.com/Wilhelmine21/Markdown#1-1-標題)  
    1-2. [字體效果](https://github.com/Wilhelmine21/Markdown#1-2-字體效果)  
    1-3. [引用](https://github.com/Wilhelmine21/Markdown#1-3-引用)  
    1-4. [標號](https://github.com/Wilhelmine21/Markdown#1-4-標號)   
    1-5. [段落](https://github.com/Wilhelmine21/Markdown#1-5-段落)  
    1-6. [換行](https://github.com/Wilhelmine21/Markdown#1-6-換行)  
    1-7. [圖片](https://github.com/Wilhelmine21/Markdown#1-7-圖片)  
    1-8. [Link](https://github.com/Wilhelmine21/Markdown#1-8-Link)  
    1-9. [轉義字符](https://github.com/Wilhelmine21/Markdown#1-9-轉義字符)  
2. [Markdown 擴充語法](https://github.com/Wilhelmine21/Markdown#2-Markdown-擴充語法)    
    2-1. [表格](https://github.com/Wilhelmine21/Markdown#2-1-表格)    
    2-2. [程式碼](https://github.com/Wilhelmine21/Markdown#2-2-程式碼)

## 1. Markdown 基本語法
### 1-1. 標題
* 第一種方式:
    * 在標題文字後加上`===`或`---`來表示主副標題
    ```Markdown
    主標題
    ======
    副標題
    ------
    ```
* 效果如下:

    主標題
    ======
    副標題
    ------

* 第二種方式:
    * 使用`#`來表示標題與標題的級別
    ```Markdown
    # Heading Level 1(字體最大)
    ## Heading Level 2(字體次大)
    ### Heading Level 3(字體適中)
    #### Heading Level 4(字體較小)
    ##### Heading Level 5(字體次小)
    ###### Heading Level 6(字體最小)
    ```
* 效果如下:

    # Heading Level 1(字體最大)
    ## Heading Level 2(字體次大)
    ### Heading Level 3(字體適中)
    #### Heading Level 4(字體較小)
    ##### Heading Level 5(字體次小)
    ###### Heading Level 6(字體最小)

### 1-2. 字體效果
* *斜體字* or _斜體字2_
    ```Markdown
    *斜體字* or _斜體字2_
    ```
* **粗體字**
    ```Markdown
    **粗體字**
    ```
* ***斜體 and 粗體字*** or ___斜體 and 粗體字2___  
    ```Markdown
    ***斜體 and 粗體字*** or ___斜體 and 粗體字2___
    ```
* ~~刪除線~~
    ```Markdown
    ~~刪除線~~
    ```
<!-- * 文字^上標^ or 文字~下標~
    ```Markdown
    文字^上標^ or 文字~下標~
    ```
* ++底線++
    ```Markdown
    ++底線++
    ``` -->
* ==螢光標記== (**此效果github無法顯示**)
    ```Markdown 
    ==螢光標記==
    ```
### 1-3. 引用
```Markdown 
>第一層
>>第二層
>>>第三層
```
* 效果如下:
    >第一層
    >>第二層
    >>>第三層
* 綜合效果引用:
> ### 標題
> * 原點  
> *斜體*   
> **粗體**  
### 1-4. 標號  
```Markdown 
1. 數字
2. 數字
3. 數字
* 其他
+ 其他
- 其他
```
* 效果如下:
    1. 數字
    2. 數字
    3. 數字
    * 其他
    + 其他
    - 其他
### 1-5. 段落
* 直接使用換行來分段

這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段這是第一段

這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段這是第二段
### 1-6. 換行&分隔線
* 換行
    * 行末加上兩個以上的空格
    * 行末加上`<br>`
* 分隔線
    * 連續三個以上的 `---` or `***` or `___`
    * 前後空一行
### 1-7. 圖片
```Markdown 
![FigName](img.png "顯示名稱")
```
* 效果如下:  
![FigName](img.png "顯示名稱")

* 圖片+連結: 
```Markdown 
[![FigName](img.png "顯示名稱")](https://github.com/Wilhelmine21/Markdown)
```   
* 效果如下:   
[![FigName](img.png "顯示名稱")](https://github.com/Wilhelmine21/Markdown)
### 1-8. Link
* 一般網址:
    ```Markdown 
    [LinkName](https://github.com/Wilhelmine21/Markdown "滑鼠停留顯示名稱")  
    ```
    * 效果如下:  
    [LinkName](https://github.com/Wilhelmine21/Markdown "滑鼠停留顯示名稱")  
* 直接顯示網址並可點選:
    ```Markdown 
    <https://github.com/Wilhelmine21/Markdown>
    ```
    * 效果如下:  
        <https://github.com/Wilhelmine21/Markdown>
* 引用式網址:
    ```Markdown 
    [Markdown說明][1]

    [1]: <https://github.com/Wilhelmine21/Markdown>
    ```
    * 效果如下:  
        [Markdown說明][1]  

        [1]: <https://github.com/Wilhelmine21/Markdown#markdown-%E7%B0%A1%E4%BB%8B>
### 1-9. 轉義字符
|Character|	Name|
|:--:|:--:|
|\ |backslash|
|`	|backtick (see also escaping backticks in code)
|*	|asterisk|
|_	|underscore|
|{ } |curly braces|
|[ ]	|brackets|
|( )	|parentheses|
|#	|pound sign|
|+	|plus sign|
|-	|minus sign (hyphen)|
|.	|dot|
|!	|exclamation mark|
|\|	|pipe (see also escaping pipe in tables)|
## 2. Markdown 擴充語法
### 2-1. 表格
```Markdown 
| 名稱 | 說明 |  
| --- | --- |  
| High | 高 |  
| Low | 低 |  
```
* 效果如下:  

    | 名稱 | 說明 |  
    | --- | --- |  
    | High | 高 |  
    | Low | 低 |  

* 內容對齊  
    ```Markdown 
    | 對齊對齊對齊 | 對齊對齊對齊 | 對齊對齊對齊 |
    | :-- | :--: | --: | 
    | 靠左 | 置中 | 靠左 |
    ```
    * 效果如下:  

        | 對齊對齊對齊 | 對齊對齊對齊 | 對齊對齊對齊 |
        | :-- | :--: | --: | 
        | 靠左 | 置中 | 靠左 |

* Html的`&#124;`來代替Markdown的`|`
### 2-2. 程式碼
* 使用\`\`\`將程式包起來，並將語言標註在第一個\`\`\`後
```
    ```python 
    for i in range(100):
        print(i)
    ```
```
* 效果如下:
    ```python 
    for i in range(100):
        print(i)
    ```
<table align="center">
  <tr>
    <td><a href="https://github.com/Wilhelmine21">Home</a></td>
    <td><a href="https://github.com/Wilhelmine21/Markdown#Markdown-簡介">TOP</a></td>
    <td><a href="https://github.com/Wilhelmine21/Markdown-Mermaid">Markdown-Mermaid</a></td>
  </tr>
</table>