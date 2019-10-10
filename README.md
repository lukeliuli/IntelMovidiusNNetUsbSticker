1.在https://software.intel.com/en-us/articles/get-started-with-neural-compute-stick 按照流程安装window下的神经网络相关软件  
2.serial number : C9PJ-ZXZP7H5B  
3,中文安装指导https://blog.csdn.net/qq_34258054/article/details/89310070
4.安装python3.6以上,注意要把python,pip所在目录添加到PATH中。
5.安装CMAKE,
6.安装VS，注意如果不是安装在C默认目录，需要在运行例子程序，里面CMAKE会出错，因为找不到MSBUILD的版本，所有要在BAT里面添加  
set "MSBUILD_VERSION=16 2019" （我安装VS2019而且不是安装到默认位置）     

  
PS:
1.在例子的各种BAT文件中，如果出现错误，使用类似以下语句检查错误。  
echo "%VS_PATH%"， echo "%MSBUILD_BIN%"    
2.BAT里面因为软件安装不是默认安装，经常出现错误，所有要自行定义一些变量，类似上面的6