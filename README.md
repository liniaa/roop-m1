pip install -r re.txt
roop ./
python run.py --execution-provider coreml --frame-processor face_swapper face_enhancer --temp-frame-quality 100 --output-video-quality 100

python run.py [options]

这是一个 Python 命令行程序的帮助信息,包含了各种选项的说明:

- -h, --help:显示帮助信息并退出
- -s, --source:选择源图像文件
- -t, --target:选择目标图像文件或视频文件
- -o, --output:选择输出文件或目录
- --frame-processor:帧处理器选择(脸部替换、脸部增强等)
- --keep-fps:保持目标视频的帧率
- --keep-frames:保留临时帧
- --skip-audio:跳过目标音频
- --many-faces:处理每一张脸
- --reference-face-position:参考脸的位置
- --reference-frame-number:参考帧的编号
- --similar-face-distance:用于人脸识别的脸部距离阈值
- --temp-frame-format:临时帧提取的图像格式
- --temp-frame-quality:临时帧提取的图像质量
- --output-video-encoder:输出视频的编码器选择
- --output-video-quality:输出视频的质量
- --max-memory:最大内存使用量(GB)
- --execution-provider:执行环境选择(CPU 等)
- --execution-threads:执行线程数
- -v, --version:显示程序版本号并退出

通过这些选项可以控制这个视频处理程序的各种参数和行为。
