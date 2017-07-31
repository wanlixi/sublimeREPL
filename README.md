# sublimeREPL
关于在sblime text3里面配置repl及快捷键配置（达到VScode的效果），
目前网上只有关于python的repl配置，个人比较喜欢sublime text 真心
相比其他的IDE不卡（稳定），后来因为VScode里面集成了shell，用了一
段时间，感觉还不错，但是不能同时拖进去多个项目，不能忍
### 直接上图：
 ![image](https://github.com/wanlixi/sublimeREPL/blob/master/WechatIMG1.jpeg)
 
## 第一步：
```
   sublime text => ctrl/command + shift + P  => Package Control: install package
```
## 第二步：
```
输入 sublimeREPL ，点击安装
```
## 第三步：
```
重启sublime text编辑器
(此时也可以使用，ctrl + shift + P => 输入 sublimeREPL
重启sublime text编辑器，
重启sublime text编辑器
```
## 第四步：
```
sublime text => Prefenences => key Bindings =>

[
  { 
		"keys": ["f7"],
		"command": "toggle_setting",
		"args": {"setting": "word_wrap"}
	},
  { 
  	"keys":["f5"],
  	"caption": "SublimeREPL: Shell - RUN current file",
  	"command": "run_existing_window_command",
  	"args":{"id": "repl_shell","file": "config/Shell/Main.sublime-menu"}
  },
]
```
## 第三步：
```
重启sublime text编辑器
```
## 第三步：
```
重启sublime text编辑器
```
## 第三步：
```
重启sublime text编辑器
```
