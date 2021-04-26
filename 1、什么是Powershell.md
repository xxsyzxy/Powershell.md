#第一课：什么是Powershell
1.定义：Windows PowerShell 是一种命令行外壳程序和脚本环境。

2.工具作用：微软官方推荐的配置和管理微软系统的命令行工具

3.如何启动ta：在Windows 操作系统里，点击开始->运行->输入PowerShell  
win+R ——  powershell 

4.如何使用？  
- 1）查找用于查看和更改Windows 服务的cmdlet 列表  
get-command *-service  
- 2）可以使用 Get-Help cmdlet 了解有关该 cmdlet 的详细信息  
get-help get-service  
- 3）若要充分理解该 cmdlet 的输出，则可通过管道将其输出传递给 Get-Member cmdlet。例如，以下命令将通过 Get-Service cmdlet 显示有关该对象输出的成员的信息。  
get-service | get-member

5.使用技巧  
- 1）命令规律：动词-名词，eg：Get-help


