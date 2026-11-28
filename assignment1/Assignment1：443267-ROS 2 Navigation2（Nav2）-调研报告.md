**#Assignment1：开源项目调研**



个人标识：443267



项目名称：ROS 2 Navigation2（Nav2）



仓库链接：https://github.com/ros-navigation/navigation2



调研日期：2026-11-28



**##1. 项目用途与选择原因**



Navigation2是ROS 2生态中的一个开源导航框架，主要用于帮助移动机器人完成自主导航任务。简单来说，就是让机器人能够根据已有地图确定自己的位置，并根据设定的目标点规划行走路线，在移动过程中尽量避开障碍物，最终到达指定位置。



该项目主要面向机器人开发人员、科研人员以及学习ROS 2的学生。项目包含定位、路径规划、运动控制和行为管理等多个功能模块，可以根据不同机器人的实际需求进行配置和调整。



我选择这个项目，主要是因为之前在课程实验中接触过ROS 2和TurtleBot3机器人，也使用过Nav2完成地图导航任务。当时需要启动导航系统、设置机器人初始位置和目标点，再观察机器人是否能够按照规划路线移动。通过实际操作，我对Nav2有了一些初步认识，但对于它内部具体是如何实现导航的还不太了解。因此，我希望通过这次调研进一步了解这个项目的组成和开源协作情况。



项目仓库：https://github.com/ros-navigation/navigation2



**##2. 开源许可证**



通过查看项目仓库中的LICENSE文件，可以发现Nav2并不是所有文件都采用同一种许可证，而是根据不同的软件包使用不同的许可证，主要包括Apache-2.0、LGPL-2.1-or-later和BSD-3-Clause等。



其中，对于没有单独标注许可证的文件，仓库默认采用Apache-2.0许可证。具体使用时，还需要查看对应软件包中的package.xml文件，确认该部分代码使用的许可证。



Apache-2.0许可证允许用户使用、修改和再发布相关代码，但也有一些需要注意的地方。例如，在重新发布软件时，需要保留原有的版权声明和许可证文本；如果对原有文件进行了修改，还需要对修改情况作出适当说明，不能直接将原作者的工作当作自己的成果。



我认为，开源并不意味着可以不受限制地使用别人的代码。在实际开发中，了解项目许可证也是比较重要的一步。



许可证文件：https://github.com/ros-navigation/navigation2/blob/main/LICENSE



**##3. 维护与活跃情况**



通过查看Nav2的GitHub仓库，我从项目版本更新和Pull Request两个方面了解了它的维护情况。



首先，从版本发布情况来看，该项目一直有持续更新。根据仓库的Releases记录，Nav2在2026年10月17日发布了1.5.3版本，此前在2026年9月16日也发布过1.5.2版本。此外，项目还针对不同ROS 2发行版本进行了相应的更新，说明开发团队仍在持续维护和改进项目。



Release记录：https://github.com/ros-navigation/navigation2/releases



其次，从Pull Request情况来看，项目仍然有开发者参与功能改进和问题修复。例如，在2026年11月26日，开发者提交了编号为#6864的PR，主要涉及ComputeAndTrackRoute节点的操作功能；同一天还有编号为#6863的PR，主要处理图文件无法写入时的返回问题。这些内容说明项目不仅在发布新版本，也有人持续参与具体功能的完善和问题处理。



PR记录：https://github.com/ros-navigation/navigation2/pulls



综合来看，Nav2目前仍然处于持续维护状态，既有定期的版本更新，也有开发者参与提交新的功能和修复问题。不过，单纯通过版本和PR数量还不能完全判断项目质量，具体更新是否稳定、实际使用效果如何，还需要结合使用过程进一步观察。



**##4. 参考资料与工具使用**



Nav2 GitHub项目主页：https://github.com/ros-navigation/navigation2



Nav2许可证文件：https://github.com/ros-navigation/navigation2/blob/main/LICENSE



Nav2版本发布记录：https://github.com/ros-navigation/navigation2/releases



Nav2 Pull Request记录：https://github.com/ros-navigation/navigation2/pulls



**AI工具使用说明：**本次调研使用ChatGPT辅助理解项目功能、整理报告结构和修改文字表达。项目许可证、版本发布时间及PR记录均通过GitHub仓库页面进行核查，报告内容根据实际查阅的资料整理完成。

