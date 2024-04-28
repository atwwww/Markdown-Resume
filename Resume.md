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
 - 求职意向：操作系统开发工程师

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士，西安电子科技大学，计算机科学与技术专业，2022.9~2025.6
- 学士，西安电子科技大学，计算机科学与技术专业，2018.9~2022.6

## <img src="assets/tools-solid.svg" width="30px"> 专业技能

- 熟悉C、C++编程语言，熟悉STL下常见容器底层数据结构。了解Java、Python、SQL等；
- 熟悉OSI七层模型，掌握HTTP、TCP/UDP、IP等常见协议；
- 熟悉openGauss数据库内核数据类型构建原理。了解MySQL、openGauss、PostgreSQL等国内外主流数据库的使用；
- 熟悉linux环境下常用命令及相关工具的使用（gcc、gdb、vim、git等）；
- 熟悉嵌入式RTOS在arm架构上的移植方法。RTOS的任务构建、多任务并发、多任务同步的底层原理；
- 熟悉POSIX线程模型及其在RTOS上的实现原理；
- 熟悉x86与arm体系架构原子操作实现原理，操作系统自旋锁、互斥锁、futex的实现原理；
- 熟悉arm、x86体系架构中断操作的流程；
- 了解linux系统在x86架构上的构建流程；
- 了解CPU三层缓存模型、缓存一致性协议MESI、软硬件内存屏障；
- 了解嵌入式编译器arm-none-eabi-gcc的构建内容，以及C/C++标准库、操作系统之间的耦合关系。

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- ### 基于星载操作系统SpaceOS的C/C++标准库开发

    **合作单位：** 北京控制工程研究所星载计算机与电子产品研制中心

    **项目内容：** 基于星载操作系统SpaceOS、嵌入式编译器arm-none-eabi-gcc开发C/C++标准库，提高操作系统编码效率与语言兼容性，助力国产航天操作系统发展。

    **项目难点：** 
    - RTOS操作系统实现原理；
    - C/C++对应标准涵盖内容，编译器内部C/C++标准库构建方式；
    - 编译器、C/C++标准库、操作系统三者的耦合关系。

    **负责工作：**
    - 项目技术主要负责人（共6人），总体维护代码仓库；
    - 调研RTOS多任务并发实现原理，系统移植方法，调研嵌入式编译器标准库符号覆盖机制；
    - 主导项目组通过ISO的C99、C++11标准文件整合语言标准库模块，**分模块产出共计35000+字文档**；
    - 制定总体实现计划，**产出20000+字开发设计方案报告**。
    - 在FreeRTOS上实现原型系统，**主要负责实现C++11多线程支持**，如\<thread\>、\<atomic\>模块等；
    - 对shared_ptr、weak_ptr引用计数线程安全性进行深入研究并实现，利用emutls实现C/C++中TLS的模拟。

- ### openGauss实现或兼容MySQL日期处理函数开发合作项目

    **合作单位：** 华为技术有限公司

    **项目内容：** 基于openGauss数据库内核开发，新增或兼容MySQL若干（共计39个）日期处理函数，增强国产数据库兼容性。
    
    **项目难点：** 
    - 与原有函数功能产生冲突时，需要做好相关类型数据库实现隔离，如last_day函数openGauss和MySQL实现不一致；
    - openGauss与MySQL函数构建机制不同带来的多返回值类型问题，如str_to_date能够根据不同逻辑返回data、time、datetime等不同类型；
    - openGauss与MySQL日期类型底层实现不一致带来的函数特征点实现问题，如在不同模式下返回null值。

    **负责工作：**
    - 项目技术主要负责人（共3人），总体维护本地代码仓库；
    - 调研openGauss数据库日期类型系统构建原理，内核函数实现机制；
    - 深度调研MySQL文档，对任务需求中MySQL日期处理函数分类，**设计文档累计85000+字**；
    - 负责本地仓库与openGauss开源社区之间的PR管理，**累计提交函数说明文档+代码=29个**；
    - 函数功能点测试、性能对比测试。90%性能优异，10%基本和MySQL持平。使用火焰图分析函数调用中的性能瓶颈问题。

## <img src="assets/github-brands.svg" width="30px"> 开源经历

- openGauss开源社区贡献者，累计提交29+PR；
- RT-Thread社区开源贡献者：
  - <a href="https://github.com/RT-Thread/rt-thread/pull/8648">添加GCC泛化原子操作函数</a>
  - <a href="https://github.com/RT-Thread/rt-thread/pull/8790">修复POSIX线程本地存储寻找POSIX线程句柄时的逻辑错误</a>
  - <a href="https://github.com/RT-Thread/rt-thread/pull/8802">修复C++11 thread_local对象析构函数与实际内存释放动作顺序相反问题</a>

## <img src="assets/briefcase-solid.svg" width="30px"> 荣誉/证书

- **2023** <a href="https://www.hikunpeng.com/developer/contests/kunpeng-competition2023?tab=2">鲲鹏应用创新大赛2023全国总决赛-铜奖</a>
- **2023** 校二等奖学金
- **2022** <a href="https://edu.hicomputing.huawei.com/openeuler-opengauss-talent/award">华为开源贡献精英奖学金</a>
- **2018-2022** 国家励志奖学金若干
- 英语六级