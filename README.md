## ChatView
这是一款可以根据输入文字长度大小去进行自动排版的输入框,简单集成只需拖入Chatview类,直接初始化即可.当然,也可以根据项目的需求不同,去定制属于你自己的UI

- 如何使用
例如,你只需要
`ChatView *chat = [[ChatView alloc]initWithFrame:CGRectMake(0,SCREN_H - 45 , self.view.frame.size.width, 45)withType:1];`
`[self.view addSubview:chat];`
就可以直接使用了,而输入之后内部值的回调则只需要设置
`chat.BtnSelector = ^(NSString *text){};`

***
如果觉得不错的话就给个星星鼓励下吧,如果你有什么好的建议,欢迎@我的邮箱1396559921.
