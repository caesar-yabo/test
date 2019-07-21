查看显卡信息：nvidia-smi
查看cpu信息：watch -n 2 sensors


批量删除指定后缀的文件:1.首先,进入需要删除文件的目标文件夹

                                                    2.比如要删除当前文件夹下所有的.png文件,运行以下命令:

                                                          find . -name "*.png" | xargs rm -rf

                                                          需要删除什么类型的文件,就用什么文件的后缀即可,
