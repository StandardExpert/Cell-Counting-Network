# Cell-Counting-Network
2023/10/31
A tool for automatic cell counting in mouse whole-brain slices based on the fine Allen brain-atlas and YOLO V8

In current studies elucidating neuronal connections among different brain regions, modified anterograde or retrograde tracing virus fused with and fluorescence reporting proteins have been frequently used. Such approaches techniques often yield numerous traced or labelled cells across the whole brain, which demands a great deal of time and effort for detecting and counting cells handily. Thus, we have developed a neural network tool for automatic cell counting for the mouse brain, namely the Cell Counting Network (CCN). Working Procedure: The development of CCN mainly benefits from the newly-released fine Allen Mouse Brain Atlas (at 10 um thickness resolution) and the fully functional Object Detection Neural Network YOLO V5. The users are only required to load the brain-slice images in the form of pictures in the CCN, and the system will align the brain slices with the Allen map, complete the detection and counting of labelled cells in all loaded whole-brain slice, and output the detailed statistical results automatically, supported by the YOLO V5 after transfer learning. Results and Features: In comparison with the reported cell detection and counting systems in the recent literatures, our CCN has the following unique features: (1) It offers a complete process from the map registration, counting, manual correction, post-processing to final result output. (2) It has a more user-friendly interface and nearly all actions are conducted with mouse-clicks without any code typing. Moreover, it also offers an option of automated operations supported by the code only platform. (3) It provides more excellent DIY room and generalization ability. Because the YOLO possess a strong ability of transfer learning, the CCN can achieve many unexpected operations with conventional tools, such as operations of detecting labeled synapses or dead cells only, or of separating different fluorescence-labelled cells at the same time. (4) All processing data are saved for individual intermediate steps for later inspection or debugging, plus manual corrections are supported.

这是一个用来进行细胞计数的工具，基于MATLAB 20222b开发。目前处于公测阶段，这Github上传代码挺复杂，我先学学的...国内的同志们可以先拿夸克网盘下载，这个网盘不限速，比百度良心一点。网盘里有我给的教程和录像，更细节的信息我慢慢补充...
有啥问题可以邮件或者在github上问我（202221061054@mail.bnu.edu.cn），但是俺平时活特别多，所以回的比较慢。

This is a tool for cell counting, developed based on MATLAB 20222b. It is currently in the public beta stage. The Github upload code is quite complicated. I will learn it in a few days... Chinese comrades can download it from the Quark network disk first. This network disk has no speed limit and is more conscience than Baidu. There are tutorials and videos I gave on the network disk. I will slowly add more detailed information...
If you have any questions, you can ask me via email or on github(202221061054@mail.bnu.edu.cn), but I usually have a lot of work, so my replies could be a little bit slow...

我用夸克网盘分享了「Cell Counting Network先行体验版」 链接：https://pan.quark.cn/s/9fcc55fae439

2023/10/24 功能
完善了任意角度对图谱进行切片的显示功能，并且优化了切片速度。但是注意，本软件针对冠状切进行了专门优化，矢状切和水平切用起来会麻烦一点。
![Image text](https://github.com/StandardExpert/Cell-Counting-Network/blob/main/2%20%E5%AF%B9%E9%BD%90%E5%9B%BE%E8%B0%B1%E4%BB%BB%E6%84%8F%E8%A7%92%E5%BA%A6%E5%88%87%E7%89%87.png)
