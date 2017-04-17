### 方法
+ 由顺序入读，不能由全局思考逻辑，不容易把握。
+ 由代码执行顺序入读，这个好
### 具体方法
+ 最后一句

		return Vue$3
		3417,定义Vue$3函数

### vue构造函数扩充
+ initMixin()
+ stateMixin()
+ eventsMixin()
+ lifecycleMixin()
+ renderMixin()
+ initGlobalAPI()

## 第一次执行(其实是第一次实例化)
### initMixin()
+ 首先添加为原型添加_init属性
+ resolveConstructorOptions(vm.constructor) , 其实什么也没做
+ mergeOptions() 
### 问题
+ 代码块中调用函数是什么意思,和use strict有关系吗？并未查到相关资料