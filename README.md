# 日常随记
## 2018年2月1日
### js重写date方法
```javascript
Date.prototype.toLocalString = function(){
  retrun this.getFullYear()+'年'+(this.getMonth+1)+'月'+this.getDate()+'日'+this.getHours()+':'+this.getMinutes()+':'+this.getSeconds()
}
