# 동방짱
##### 2019 인터페이스 자체 해커톤 "인커톤" 프로젝트
* 딥러닝을 이용하여 동아리방에 사람이 몇 명 있는지 탐지할 수 있는 인공지능을 개발하였다.
* 인터페이스 동아리방은 학생회관 518호이다.



## 팀원
|이름|기수|학과|학번|github ID|
|:--:|:----:|:----:|:----:|:----:|
|조동현| 31기 | 스마트기기공학전공 | 18011838 |[hyeon9698](https://github.com/hyeon9698)|
|서동수| 31기 | 스마트기기공학전공 | 18011878|[#](https://github.com/#)
|이승준| 31기 | 스마트기기공학전공 | 18011846 |[Looma1116](https://github.com/Looma1116)|
|이현주| 31기 | 컴퓨터공학과 | 18011603 |[alro923](https://github.com/alro923)|

*팀원들의 성을 따서 "이조판서"라는 팀 이름이 탄생하였습니다.*




## 설치 방법
* Windows or Linux
* **CMake >= 3.8** for modern CUDA support: https://cmake.org/download/
* **CUDA 10.0**: https://developer.nvidia.com/cuda-toolkit-archive (on Linux do [Post-installation Actions](https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html#post-installation-actions))
* **OpenCV >= 2.4**: use your preferred package manager (brew, apt), build from source using [vcpkg](https://github.com/Microsoft/vcpkg) or download from [OpenCV official site](https://opencv.org/releases.html) (on Windows set system variable `OpenCV_DIR` = `C:\opencv\build` - where are the `include` and `x64` folders [image](https://user-images.githubusercontent.com/4096485/53249516-5130f480-36c9-11e9-8238-a6e82e48c6f2.png))
* **cuDNN >= 7.0 for CUDA 10.0** https://developer.nvidia.com/rdp/cudnn-archive (on **Linux** copy `cudnn.h`,`libcudnn.so`... as desribed here https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#installlinux-tar , on **Windows** copy `cudnn.h`,`cudnn64_7.dll`, `cudnn64_7.lib` as desribed here https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#installwindows )
* **GPU with CC >= 3.0**: https://en.wikipedia.org/wiki/CUDA#GPUs_supported
* on Linux **GCC or Clang**, on Windows **MSVC 2015/2017/2019** https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community

Compiling on **Windows** by using `Cmake-GUI` as on this [**IMAGE**](https://user-images.githubusercontent.com/4096485/55107892-6becf380-50e3-11e9-9a0a-556a943c429a.png): Configure -> Optional platform for generator (Set: x64) -> Finish -> Generate -> Open Project -> x64 & Release -> Build -> Build solution

Compiling on **Linux** by using command `make` (or alternative way by using command: `cmake . && make` )


## 참고 자료
* **darknet**
    * https://github.com/AlexeyAB/darknet
    * https://zeuseyera.github.io/darknet-kr/SaYongBeob_Yolo-v3.html

* **Yolo mark**
    * https://github.com/AlexeyAB/Yolo_mark
