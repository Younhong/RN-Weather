전반적으로 flutter와 유사하다.
View는 처음에 Container 역할로 알았으나 컨테이너, row, column, flexible 역할까지 한다.

* Row
```javascript
<View style={{ flex: 1, flexDirection: 'row' }}>
    <View></View>
    <View></View>
</View>
```

* Column
```javascript
<View>
    <View></View>
    <View></View>
</View>
```

* Flexible
```javascript
<View style={{ flex: 1 }}>
    <View style={{ flex: 1 }}></View>
    <View style={{ flex: 2 }}></View>
</View>
```
