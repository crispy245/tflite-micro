## Make Flags
The command to build TFL Micro for SERV is:
```
make -f tensorflow/lite/micro/tools/make/Makefile TARGET=serv_mcu 
```
If you want to build the hello_world (https://github.com/crispy245/tflite-micro/tree/main/tensorflow/lite/micro/examples/hello_world) example:
```
make -f tensorflow/lite/micro/tools/make/Makefile TARGET=serv_mcu hello_world_bin
```
