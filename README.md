# IOING - 日期选择组件

<table>
 <thead>
  <tr>
   <td>指令</td>
   <td>值</td>
   <td>描述</td>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>type</td>
   <td>datepicker/date/time/month</td>
   <td>设定类型</td>
  </tr>
  <tr>
   <td>theme</td>
   <td>ios/android</td>
   <td>设定皮肤</td>
  </tr>
 </tbody>
</table>

```html
<input type="datepicker" value="2017-06-01" readonly>
<input type="time" value="12:12" readonly>
<input type="month" value="2017-06" readonly>
<date-picker theme="android"></date-picker>
```
将该组件放在有日期选择需求的页面中，该组件能找到所有日期选择类型的 input，在 input foucs 时弹出日期选择控件
