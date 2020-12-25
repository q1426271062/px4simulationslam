# px4simulationslam
原文链接https://blog.csdn.net/bryantaoli/article/details/105155757
python mergebag.py -v nogpscs3.bag nogpscs1.bag nogpscs2.bag 链接 就把两个cs1  cs2 合在cs3里了，时间戳打的都是原来两个bag里原始的时间戳

python merge_bag.py -v --topics '/mavros/global_position/raw/fix  /mavros/global_position/raw/fix' nogpscs3.bag nogpscs1.bag nogpscs2.bag就把cs1 2.bag里的/raw/fix合并在了一起python mergebag.py -v nogpscs3.bag nogpscs1.bag nogpscs2.bag  就把两个cs1  cs2 合在cs3里了，时间戳打的都是原来两个bag里原始的时间戳
python merge_bag.py -v --topics '/mavros/global_position/raw/fix  /mavros/global_position/raw/fix' nogpscs3.bag nogpscs1.bag nogpscs2.bag就把cs1 2.bag里的/raw/fix合并在了一起
