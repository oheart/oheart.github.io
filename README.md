## hexo-blog
用hexo-blog搭建的个人博客。  

预览地址：https://oheart.github.io/
## doc 
[中文doc](https://hexo.io/zh-cn/ )   
[英文doc](https://hexo.io/)
## 初始化hexo-blog
1. npm install hexo-cli -g
2. hexo init blog
3. cd blog
4. npm install
5. hexo server
## 常见用法
1. 新建文章： hexo new 文章名
2. 新建页面：hexo new page about  
   用localhost:4000/about/index.html访问
3. 修改项目根目录的_config.yml中的 post_asset_folder 参数设置文章的资源文件夹要不要.默认为false,设置为true新建文章时可以生成对应的文件夹  
[资源文件夹](https://hexo.io/zh-cn/docs/asset-folders.html)
4. 部署（deploy）
- github新建oheart.github.io的仓库，这里的oheart是用户名。
- [doc](https://hexo.io/docs/deployment.html)
- hexo generate - d  文件生成后立即部署网站
- 上传一个README.md到github
    - 在Hexo目录下的source根目录下添加一个,README.md。  
    - 修改Hexo目录下的_config.yml，设置skip_render:README.md  
    - link: [怎么用hexo上传一个README.md到github?（Ubuntu）](https://www.zhihu.com/question/28058973)


## 编辑文章内容
1. title: 标题
2. date: 创建日期
3. tags: 标签
4. categories: 分类
## scaffolds里面的模板(md文件)
1. post.md（新建文章的模板）  
给post.md添加categories字段，那么每次新建文章时就会多出来一个categories字段.
2. page.md（新建页面的模板）
3. draft.md（）
## 参考链接
1. [hexo+github搭建个人博客01](https://jirengu.com/app/video/403)  
2. [hexo+github搭建个人博客02](https://jirengu.com/app/video/405)




