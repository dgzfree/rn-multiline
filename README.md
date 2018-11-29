# rn-multiline

install
--------
npm i multiline-dugz

------
base usage
----
```javascript
 <MultiLineView
      lineHeight={30}
      numberOfLines={2}
      style={{
        backgroundColor: "pink"
      }}>
      {
        data.map((v, i) => {
          return <Text key={i} style={{ height: 30, color: "skyblue", padding: 5 }}>{v}</Text>;
        })
      }
    </MultiLineView>;
```
--------
API
-----
```javascript
    children: PropTypes.node.isRequired,//子视图
    lineHeight: PropTypes.number,//行高
    numberOfLines: PropTypes.number.isRequired
 ```
