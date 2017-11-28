# Don_Quixote_robot(堂吉诃德家庭机器人)
计划在linux(Python)上编写一个家居机器人，可以进行正常聊天，旅行规划、日程安排、天气咨询; 可以通过语音对家电进行控制;
所有代码开源，所用第三方API以及包都属于免费或者开源；打造一个免费的机器人管家；可以运行在旧手机、老电脑、树莓派上，不需要太大的运行空间和内存；
只要有想法就会上传

目前需要的网络API：
图灵机器人API；
百度语音API;
百度人脸识别API;

目前需要依赖包：
PyAudio：用于语音交互；
Opencv2：用于（人脸识别？），图像处理；
jeiba：用于NLP分词等；
pydub:用于mp3转换wav，PyAudio不能播放mp3；

注意：项目在下载后主要改动control文件夹中的settings.py和control_robot.py
settings.py:配置文件，里面有提示的所有需要的百度语音API的key和图灵机器人API；
control_robot:关于所有机器人的控制文件可以在里面编写，包括对语音、人脸等的识别；
