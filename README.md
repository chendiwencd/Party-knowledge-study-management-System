# Party building knowledge learning management system
Management Party building knowledge learning, a simple and systematic reproduction
该系统分为两部分，管理员部分和学生部分
管理员部分实现的功能包括：学生信息管理，对学生账号信息，学习情况进行修改
                         学习任务管理，对学习任务进行发布，查看学生完成进度
学生部分实现的功能包括：个人信息管理，修改个人账号信息（包括密码、个人基础信息等）
                        学习任务完成，对学习信息进行获取，汇报完成进度，查看其他学生进度与积分排名
两部分功能的区分由登录功能实现，由两个不同的数据库表对用户权限和功能进行区分，
学生表包括个人信息，积分，任务完成情况，管理员表则只包含账号密码，另有一张表为管理员发布的任务信息
