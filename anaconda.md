# 环境管理
**conda env list**	查看所有环境
**conda list**	查看环境中的包
**conda create -n <env_name> python==version**	创建环境
**conda activate <env_name>**	激活环境
**conda deactivate**	退出环境
**conda remove -n <env_name> --all**	删除环境

# 安装，更新，删除包
**conda install <package_name>**	安装包
**conda update <package_name>**	更新包
**conda remove <package_name>**	删除包

# 导出和导入环境
**conda env export > environment.yml**	环境保存到当前目录下
**pip freeze > requirements.txt** 同上
**conda env create -f environment.yml**	创建并导入

