# 验证码按钮
##传入参数

```js
props: [
  'phoneNum',
  'required',
  'fn'
]
```

- phoneNum 电话号码
	- 字符串
- required 是否必须电话号码
	- 布尔
	- 如果必须，必须传入电话号码，号码不通过会弹窗提醒
	- 如果非必需，则不传入不验证
- fn 点击按钮触发函数
	- 函数

## 样式
和 ele 组合自适应位置。

![-w300](media/14617459933347/14617490038442.jpg)
![-w300](media/14617459933347/14617490978921.jpg)

## 用法
组件引入。
点击自动倒计时，无法重复点击。
