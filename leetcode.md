# 数据结构

## 所有思路

前缀和  滑动窗口 双指针 贪心 单调栈 双向队列

## 注意点

对于包装类

对 Java 包装类进行比较时要尤为小心，`Integer`，`String` 等类型应该用 `equals` 方法判定相等，而不能直接用等号 `==`，否则会出错。所以在缩小窗口更新数据的时候，不能直接写为 `window.get(d) == need.get(d)`，而要用 `window.get(d).equals(need.get(d))`，之后的题目代码同理。

## 数组

```java
//长度
nums.length //属性拿值
//排序
    Arrays.sort();
Arrays.sort(nums,(p,q)->p-q)按照
```



## hash

```java
//创建
HashMap<Integer,Integer> map=new HashMap<>();
//API
//插入
map.put();
//插入
List<String> list = map.getOrDefault(key, new ArrayList<String>());
//查找
map.containsKey()
//取map的key
map.keySet()
//取map的value
map.value()
```

## String

```java
String str；
//转数组
str.toCharArray();
//char[].toString()和new String（）区别
因为数组没有重写tostring所以返回的不是一个String对象而是一个内存地址的字符串  应该用new string

```

## 栈

```java
//入栈
s.push()
//出栈
s.pop()
//栈顶
s.peek()
```

## 队列

```java
//声明
Deque<Integer>d=new LinkedList<>();
//对头操作
addFirst()
removeFirst()
getFirst()
//对尾部操作

    
```

