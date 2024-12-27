config_all.xlsx
    一个sheet表示一个车型，head行：group_name	path	doa	wakeup_count	type	ref
    分别表示：分组名、音频文件名或路径、唤醒定位、唤醒次数、类型（1：误唤醒音频）、复用依赖

    可以指定：唤醒资源、信号资源、sspe工具、唤醒词配置。
    唤醒词配置为空时，将从唤醒资源中自动读取。
    type=1时，将自动保存唤醒小音频。