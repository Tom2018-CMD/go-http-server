# Go Web 编程入门

这是我在公众号上更新的，《Go Web编程》系列教程文章的存档。教程对新手非常友好，从零开始用Go语言构建一个Web程序。我们通过用Go语言创建一个简易的Web框架来讲解Go语言在Web编程中经常涉及的功能及其实现，源码已经按照章节打成tag, 通过参考章节对应版本的源码一定会让你的学习过程更轻松，读者朋友们可以自己动手创建项目来练习这里教授的功能
源码，这样效果更好，如果自己的项目遇到卡壳儿的地方再去参考我提供的源码。

比如你想看第二章节节的代码，那么就可以在项目里使用
```
git checkout v0.2.0
```
切换到这个章节对应的源码版本了。


学习中如果遇到了问题，欢迎在我的公众号文章中留言，这样能帮助到更多读者。



## 目录
- [学习用Go语言自己实现Web服务器](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484112&idx=1&sn=79d0d3167d0d962fe41ec00cdafffbb0&chksm=fa80d347cdf75a51183182f14622af766538ca0c5335012e5e1cc50b100e78f2954fa3943770&token=708416499&lang=zh_CN#rd)
- [五分钟用Docker快速搭建Go开发环境](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484127&idx=1&sn=f5286405728b2d4f657e16cfdb6f07cc&chksm=fa80d348cdf75a5e1f95fdfb3a0d703cee59d6560e5b377f3a0bfe6770ca7bf236eadb0a7e44&token=708416499&lang=zh_CN#rd)
- [gorilla/mux 路由](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484172&idx=1&sn=6dc988c86c3572a8092bdc79feb8d4e8&chksm=fa80d29bcdf75b8d06fc56366352671131c06e1c299a4929a56d7f5ab7137d1e1aec213c5e40&token=1670923354&lang=zh_CN#rd)
- [十分钟学会用Go编写Web中间件](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484180&idx=1&sn=b66497c5428c25577068f18132b2d59d&chksm=fa80d283cdf75b95cc49d08c56d0fa9b00c47d0457c894be3ca3ea02bd3c404cfb5312fa1d93&token=730660954&lang=zh_CN#rd)
- [应用数据库](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484200&idx=1&sn=a6d41c6aa4b3e22eac313966fb7eac57&scene=19#wechat_redirect)
- [应用ORM](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484212&idx=1&sn=fc64a905c8f32acab908cc7d3d848680&chksm=fa80d2a3cdf75bb5f47244145b965e9be3ee002270154f53a1c16802a375001cd7822490986d&token=386954690&lang=zh_CN#rd)
- [深入学习如何解析HTTP请求](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484246&idx=1&sn=6de3644dcb1877a3e205745aaf9fed71&chksm=fa80d2c1cdf75bd78fbedbfc28931b213986bc861c757c8d0a1ad3efa088726a7e176bde2f61&token=1075978729&lang=zh_CN#rd)
- [超详细的Go语言模板库应用指南](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484271&idx=1&sn=6dfef42f172b6a177fd372e619796991&chksm=fa80d2f8cdf75bee931b7516f41e0aa4ba48b38d41ecce1fec055c255aaa51a5a828f7450f4e&token=1975536642&lang=zh_CN#rd)
- [使用Go语言创建静态文件服务器](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484278&idx=1&sn=488a0c0304237e15c53c74ebd7a8296a&chksm=fa80d2e1cdf75bf70efcf95f708bc54cf9564f1f22340754abef14ee0baf2a181d48230723c5&token=44329373&lang=zh_CN#rd)
- [使用 SecureCookie确保Cookie的安全传输](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484287&idx=1&sn=54baf9ab1739b2001a2e1aec6d6a2d66&chksm=fa80d2e8cdf75bfe8110856f8719be79db94a7de96fe771b9d38ea1d9a93957e7122c5fce780&token=975323517&lang=zh_CN#rd)
- [SecureCookie实现客户端Session管理](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484297&idx=1&sn=a1d647f0f3f2996a3dc1d06b9cfaaa9b&chksm=fa80d21ecdf75b089e0dc1d4a914688ef1e9c416366fd4562f7bff961c5ecdf6c4a5dfc71880&token=1228657490&lang=zh_CN#rd)
- [使用Go语言创建WebSocket服务
](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484313&idx=1&sn=a5c096466a5dbf4ec83eab2ba5992d7f&chksm=fa80d20ecdf75b18476a010bde5c5707e2bd3915f4c3e4e4ad4159baa541bb921c571d1f898b&token=1667524815&lang=zh_CN#rd)

- [关于如何收集，标准化和集中化处理Golang日志的一些建议
](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484320&idx=1&sn=d6c4b46c7e106ca14368c0772b8c803a&chksm=fa80d237cdf75b2194539edf548abad7aaba64b998d3abab6d441b15fdbbaf1eddd258c0c30e&token=1940467894&lang=zh_CN#rd)

- [给自己写的服务器添加错误和访问日志](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484332&idx=1&sn=99a3af12669240b721312d935854d1e4&chksm=fa80d23bcdf75b2d722e0b6274a73a9e8533ce92da9a3b24aabbc1f0d8c45bddcf435ccc565a&token=618719182&lang=zh_CN#rd)

- [Go Web编程--解析JSON请求和生成JSON响应](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484342&idx=1&sn=f2a66a72b8147009c50ade2ef8b7f054&chksm=fa80d221cdf75b3739932a357843d8b6cc44a3096c326fab9dc1e84bb59e61696911842ab444&token=916082054&lang=zh_CN#rd)

- [应该使用哪种哈希算法保护用户密码](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484347&idx=1&sn=37cdaff84347e59586ced60f9c17b026&chksm=fa80d22ccdf75b3a21f38483bc611a318b0d4ab04011fc2dcbaa388965da3533872a3ab45c55&token=726137373&lang=zh_CN#rd)

- [使用bcrpyt哈希用户密码](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247484352&idx=1&sn=30a070ec4aa61b98bcf4739348c6f111&chksm=fa80d257cdf75b41e51faa7f95712f6a2751659678ae487cd9868ad4de8f6b526011f0034529&token=923225651&lang=zh_CN#rd)
- [整合 Zap 作为项目业务日志 Logger 组件](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&amp;mid=2247493846&amp;idx=1&amp;sn=de3eee6b0d1a02bcd966ea07b7401c99&amp;chksm=fa833941cdf4b057d45b7cbf2748abb1c1e79d0572b55705f868f35581c8d9ed3d9812f8e27e&token=471555695&lang=zh_CN#rd_)

## 公众号

![微信公众号：网管叨bi叨](https://github.com/kevinyan815/Learning_Laravel_Kernel/blob/master/images/WX20200119-143845%402x.png)
