# formatDate
时间格式化插件

```
/**
 * 日期格式化函数
 * @param  {Date}  dateTime 日期和时间
 * @param  {String}  format   日期的格式，形式类似于'yyyy-MM-dd H:i:s',
 * @param  {Boolean} pm       24小时制
 * @return {String}           格式化时间
 */
function dateFormat(dateTime, format, {pm = false, str = 'pm'} = {}) {
	
}
```
- 第三个参数为对象，pm表示是否开启24小时制，false表示24小时制， str表示下午的定制字符串表示形式

*通过CommonJS的风格导入，需要使用Babel等编译器将ES6编译成ES5*
