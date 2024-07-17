 <center>
     <h1>王阿涛</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18348392003
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             atao_wang_email@163.com
         </span>
         ·
         <span>
             <img src="assets/qq-fill.svg" width="18px">
             793822091
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 性别：男
 - **求职意向：操作系统开发工程师**

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士，西安电子科技大学，计算机科学与技术专业，2022.9~2025.6
- 学士，西安电子科技大学，计算机科学与技术专业，2018.9~2022.6

## <img src="assets/tools-solid.svg" width="30px"> 专业技能

- 熟悉C、C++，了解常见STL容器底层实现，了解Java、Python等；
- 掌握网络TCP/IP五层模型，熟悉TCP/IP、HTTP等网络协议；
- 熟悉linux环境下常用命令及相关工具的使用（gcc、gdb、vim、git等）；
- 了解MySQL的使用及相关原理，如索引、事务、锁、MVCC、日志；
- 了解操作系统进程、线程、原子操作、锁、中断、信号；了解常见IO多路复用方法：select、poll、epoll；熟悉POSIX线程模型及其join、detach等操作的实现原理；
- 了解CPU三层缓存模型、缓存一致性协议MESI、软硬件内存屏障；

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- ### **基于星载操作系统SpaceOS的C/C++标准库开发**（北京控制工程研究所）

    **项目简介：** 基于星载操作系统SpaceOS、嵌入式编译器arm-none-eabi-gcc、Cortex-A9硬件平台设计开发C/C++标准库。
    - 项目技术负责人（共6人）；总体维护代码仓库；主导项目组通过C99、C++11标准文件整合标准库模块，分析arm-none-eabi-gcc依赖操作系统接口情况；撰写总体开发设计方案报告；
    - 阅读分析RTOS源码，掌握链接脚本、RTOS移植方法、多任务并发实现原理、C/C++标准库符号覆盖机制；
    - 通过链接脚本符号地址确定由于任务栈溢出导致的数据异常问题；
    - **主要负责实现C++11多线程支持**，如\<thread\>、\<atomic\>等模块：
      - 对shared_ptr、weak_ptr引用计数的线程安全性进行深入研究并实现。
      - 利用emutls实现C/C++中TLS的模拟。
      - 针对Cortex-M和Cortex-A架构，采用不同的C++原子变量底层支持方法。

- ### **openGauss实现或兼容MySQL日期处理函数开发合作项目**（华为）

    **项目简介：** 基于openGauss数据库内核开发，新增或兼容MySQL数据库39个日期处理函数。
    - 项目技术负责人（共3人）；维护本地代码仓库与上游开源仓库之间的交互；根据功能细化分类MySQL日期处理函数兼容需求，分阶段实现；参加SIG评审会评审设计方案；
    - 阅读分析openGauss数据库源码，掌握数据库日期系统构建原理；对照MySQL相应函数实现要求在openGauss侧实现；数据库调试；自测用例设计；
    - 使用lcov进行用例覆盖率测试；基于ASAN进行内存安全测试；使用火焰图定位函数调用链中的性能瓶颈。

- ### **muduo高性能异步日志组件复现**

    **项目简介：** 
    - 使用生产者消费者模型实现日志组件的前后端；使用固定数量的缓冲区交换保持热点内存，减少PageFault开销；进行日志性能对比，通过火焰图发现**snprintf**函数性能瓶颈。
    - 对linux系统编程模块，如IO、时间等有了较深认识；对操作系统缓冲区、用户缓冲的使用有了深入了解。

- ### **校园外卖订餐系统**

    **项目简介：** 基于Spring、SpringBoot、Mybatis、Redis的前后端分离项目，主要负责后端实现。
    - 管理端和用户端数据库关系表的设计；
    - 云对象存储；JWT权限验证；微信小程序用户身份认证；微信支付；重要信息导出excel表格。
## <img src="assets/github-brands.svg" width="30px"> 开源经历

- **openGauss开源社区**，累计提交29个PR；
- **RT-Thread开源社区**：
  - 添加GCC泛化原子操作函数
  - 修复POSIX线程本地存储寻找POSIX线程句柄时的逻辑错误
  - 修复C++11 thread_local对象析构函数与实际内存释放动作顺序相反问题

## <img src="assets/briefcase-solid.svg" width="30px"> 荣誉/证书

- **2023** **鲲鹏应用创新大赛2023全国总决赛-铜奖**
- **2023** 研究生学业奖学金二等奖
- **2022** **华为开源贡献精英奖学金**
- **2022** 研究生学业奖学金一等奖
- **2018~2021** 国家励志奖学金若干
- 英语六级