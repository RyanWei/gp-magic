# gp-advanced-backup-and-restore
gpdbbackup
gp数据库备份命令，配合gpdbrestore使用
gpdbrestore
gp数据库恢复命令，配合gpdbbackup使用

gpddbackup
gp数据库备份命令，配合gpddrestore使用
与gpdbbackup的区别在于，此命令备份数据文件不压缩，对于数据通过NAS存储到DataDomain有较好的兼容
向DataDomain存储压缩后的文件，不利于深度压缩去重，因此才修改了这样的版本
gpddrestore
gp数据库恢复命令，配合gpddbackup使用

gpdbtransfer
集群之间数据同步命令

截止目前[20171128] 所有这些命令全部代码全部由 陈淼 [ miaochen@mail.ustc.edu.cn ] 个人贡献
