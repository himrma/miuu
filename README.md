# MIUU.TOP
一款更方便展示域名的域名出售列表，来自米优优米表-[MIUU.TOP](https://miuu.top)。  
支持中英文切换，支持明暗模式切换。

## 添加域名卡片
```
 { name: "example.com", desc: ["中文说明", "English instructions"], link: "https://example.com", sold: false },
```
 把example.com修改成自己的域名；   
 "中文说明", "English instructions"分别对应中英文说明；  
 link后添加要跳转的链接；
 false=未出售；true=已出售。   

 域名卡片顺序依次排列，根据需要自行调整。   
 源码中已有域名卡片仅为示例，请删除并添加自己的域名。

## 添加友链
```
 <a href="https://friend1.com" target="_blank" rel="noopener noreferrer" data-i18n="friend1">张三</a>
 <a href="https://friend2.com" target="_blank" rel="noopener noreferrer" data-i18n="friend2">李四</a>
 <a href="https://friend3.com" target="_blank" rel="noopener noreferrer" data-i18n="friend3">王五</a>
 <a href="https://friend4.com" target="_blank" rel="noopener noreferrer" data-i18n="friend4">赵六</a>
```
修改以上链接同时也要修改一下国际化配置，才能在中英文模式下正常显示。
```
 // 国际化配置
 zh: {
   friend1: "张三",
   friend2: "李四",
   friend3: "王五",
   friend4: "赵六",
   },

 en: {
   friend1: "Zhansan",
   friend2: "Lisi",
   friend3: "Wangwu",
   friend4: "Zhaoliu",
   },
```

## 其他修改
修改标题、联系方式、邮箱、购买、售出等文字信息和友链一样，也需要调整**国际化配置**

## 效果
Demo： [MIUU.TOP](https://miuu.top)   
祝大佬们域名大卖！
