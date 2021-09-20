1. Install Jekyll

  $ gem install jekyll
  $ jekyll -v                //查看版本
  $ jekyll new myblog
  $ cd myblog
  $ jekyll serve             //执行，默认4000端口

  至此访问 localhost:4000 就可以看到你的 Jekyll Blog 了

2. First post
  文件解释     更多内容详见https://jekyllrb.com/docs/configuration/

  _config.yml
    配置文件 有标题 邮件 描述
    例子 port: 8080 将默认端口改成从4000改成8080

  _site
    自动生成，完全不必去理会
    自动渲染的文件，将此文件夹上传至 github 下，创建 <your-account>.github.io 里面
    这是 Jekyll 的最终产品

  _layouts
    结构
  _posts
    实际网页内容
    
