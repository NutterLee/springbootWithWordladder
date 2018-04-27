# springbootWithWordladder
the word ladder web app with springboot and shiro

用法：启动项目后访问/ladder?start=code&end=data，将code与data两个单词替换为你想建立ladder的单词

     因为初次访问没有登录将被系统重定向至登录界面
     
     登录之后即可使用word ladder
     
     管理员在登录后可以访问/userInfo，/userList，/userAdd，/userDel等用户管理界面（具体界面没有完善），非管理员用户登录无法访问这些页面
     
     对数据库存储的密码进行了加密，管理员账户名为admin 密码为123456
     
     数据库配置
    datasource:
    
      url: jdbc:mysql://localhost:3306/testLogin
      
      username: root
      
      password: 4869
      
    
     
