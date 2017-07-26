# lookPicture
    大家平时开发过程中可能有较多的浏览图片的需求，如果图片目录较大，可能打开图片会很低效。推荐一下我自己一直用的python脚本用于看图，请下载下来放在home目录下，然后打开~/.bashrc，在最后添加 alias iter='python ~/iter_folder.py'  , （缩写和python路径可以按喜好更换）， 即可通过iter + [folder_path]命令顺序浏览文件夹下图片。例如需要看/home/shaojun/images下的图片，执行iter /home/shaojun/images或在/home/shaojun录目下执行 iter images 即可。程序默认会按照文件夹下的所有的图片的文件名顺序进行查看。
