# three.js 插件之 data.gui.js 使用详细
## 设置控制项标签文字
* 默认情况下每个控制项左侧的标签显示的是对应的属性名，我们可以通过 name 方法设置成其他的文字（中文也是支持的）
```javascript
	var FizzyText=function()
	{
		this.rotationSpeed=0;
	}
	var text=new FizzyText();
	var gui=new dat.GUI();
	gui.add(text,'rotationSpeed',0,2).name("旋转速度");
```
* [Source Code](#)
