# maven note 的开始
依赖传递的情况下的一些，间接依赖的隐藏传递、屏蔽传递，
依赖传递深度图
![image](https://github.com/Kitoali/JavaNote/assets/54657765/78985538-9ac3-492c-a058-8e368b038bad)

在project2中会隐藏掉3中隐藏掉的依赖，--3中的依赖不想被2看到---->可选依赖
![image](https://github.com/Kitoali/JavaNote/assets/54657765/541a742f-a82e-4f74-9d46-399a8b7ee497)

有时项目2中引用了3，但是其中有不想用的间接依赖需要主动排除掉，写法如下---->排除依赖
![image](https://github.com/Kitoali/JavaNote/assets/54657765/dee6e41b-b705-4097-a89f-81676cd8e213)

依赖范围
![image](https://github.com/Kitoali/JavaNote/assets/54657765/42d22d0b-b026-4f6a-8e1d-92d11b0be523)

依赖范围的传递
![image](https://github.com/Kitoali/JavaNote/assets/54657765/28a4f62d-7277-4be5-b31d-85dfd68075b2)

生命周期内容
![image](https://github.com/Kitoali/JavaNote/assets/54657765/030f1e11-48e3-4594-aca0-28b56992505b)
指定步骤执行
maven对项目进行打包
![image](https://github.com/Kitoali/JavaNote/assets/54657765/6a461b0b-d0a9-4b27-9d9f-3a122be98cff)

工程模块的拆分
![image](https://github.com/Kitoali/JavaNote/assets/54657765/a96cc14e-864a-42d8-bc90-fbbc0d48d4f1)


service层的拆分
![image](https://github.com/Kitoali/JavaNote/assets/54657765/7092c242-bbc8-4420-9d4b-cbce38c932b7)

为了统一管理子工程的依赖，解决子工程间依赖版本不同造成的不兼容问题，继承
![image](https://github.com/Kitoali/JavaNote/assets/54657765/2fefc85a-c859-4d4c-b13d-922d868dec6e)

实际配置过程，先配置父工程dependency management，后简化子工程依赖版本，名称问题
![image](https://github.com/Kitoali/JavaNote/assets/54657765/c1f88d6b-41f2-402f-bbfc-691518f32ffe)

简化后，子工程的版本可以删除，由父工程统一版本，如果子工程单独声明不同版本也是可以的
![image](https://github.com/Kitoali/JavaNote/assets/54657765/0a70940f-1ec1-4841-9b34-d0ec5c828893)

可以用来继承的资源
![image](https://github.com/Kitoali/JavaNote/assets/54657765/7c366bf6-6480-483a-bbb8-fd4794136f51)

更方便的版本管理，自定义变量
![image](https://github.com/Kitoali/JavaNote/assets/54657765/5ff79be6-7447-4421-bdaa-66fd2087516f)

![image](https://github.com/Kitoali/JavaNote/assets/54657765/0ceab82f-7c4c-4c92-9364-d1e907d9f86b)


资源配置
![image](https://github.com/Kitoali/JavaNote/assets/54657765/a521b985-6507-4b58-bdb7-3580af14cbd7)
![image](https://github.com/Kitoali/JavaNote/assets/54657765/fcaa9136-ef18-4181-9af4-afc1dcd28a31) 




