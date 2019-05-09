### python的内存机制初步理解

- 使用内存图理解

- 理解变量的定义：关联对象的标识符

- 理解“==”和“is”的区别

- 案例1：
  
  ```
  list01 = [1000, "a", ["b", 500]]
  list02 = [1000, "a", ["b", 500]]
  
  print(list01 is list02)  # ? False
  print(list01 == list02)  # ? True
  ```

- 案例2:
  
  ```
  反向遍历列表的两种方法：
  for index in range(len(list01)-1，-1，-1)：
      print(list01[index])
  
  for item in list01[::-1]:
      print(item)
  ```

- 案例3：
  
  - +=   -=    /=   *=
