nohup yolo cfg=mytrain.yaml &
tail -f nohup.out
windows不支持直接使用多线程需要进行封装，linux可以直接使用多线程，num_workers默认等于0，就是只一个主进程运行
yolo cfg=mytest.yaml
conda activate yolov8
