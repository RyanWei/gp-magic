# gp-magic
此repository的所有代码遵从GPL3协议，任何获取本repository代码的主体不得用于任何商业目的，因为您的代码也必须开源
此repository仅有一个贡献者：陈淼 [ miaochen@mail.ustc.edu.cn ]，在未得到本人授权之前，任何人不得剽窃代码中的任何理念

名称确定为gp-magic，感谢Ryan Wei给起了个这么高大上的名字
出于分享精神，打算后续多放点有通用性价值的小工具上来

gpdbbackup：gp数据库备份命令，配合gpdbrestore使用
gpdbrestore：gp数据库恢复命令，配合gpdbbackup使用

gpddbackup：gp数据库备份命令，配合gpddrestore使用，与gpdbbackup的区别在于，此命令备份数据文件不压缩，对于数据通过NAS存储到DataDomain有较好的兼容向DataDomain存储压缩后的文件，不利于深度压缩去重，因此才修改了这样的版本
gpddrestore：gp数据库恢复命令，配合gpddbackup使用

gpdbtransfer：集群之间数据同步命令

截止当前最新版本 此repository全部代码全部由 陈淼 [ miaochen@mail.ustc.edu.cn ] 个人贡献
