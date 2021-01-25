- REF: https://docs.unrealengine.com/en-US/InteractiveExperiences/Framework/QuickReference/index.html
- REF: https://docs.unrealengine.com/en-US/InteractiveExperiences/Framework/UIAndHUD/index.html
- REF: https://docs.unrealengine.com/en-US/TestingAndOptimization/PerformanceAndProfiling/Scalability/ScalabilityReference/index.html
- REF: https://docs.unrealengine.com/en-US/BuildingWorlds/LightingAndShadows/MeshDistanceFields/HowTo/DFHT_4/index.html
- REF: https://docs.unrealengine.com/en-US/BuildingWorlds/LightingAndShadows/MeshDistanceFields/HowTo/DFHT_1/index.html
- REF: https://docs.unrealengine.com/en-US/BuildingWorlds/LightingAndShadows/CapsuleShadows/Overview/index.html
- REF: https://docs.unrealengine.com/en-US/ProgrammingAndScripting/ProgrammingWithCPP/IntroductionToCPP/index.html


### Verificar Vulkan
~~~
$ X -configure
~~~

~~~
$ grep LoadModule /var/log/Xorg.0.log
[    26.038] (II) LoadModule: "glx"
[    26.043] (II) LoadModule: "glxservernvidia"
[    26.043] (II) LoadModule: "intel"
[    26.043] (II) LoadModule: "nvidia"
[    26.060] (II) LoadModule: "fb"
[    26.062] (II) LoadModule: "wfb"
[    26.062] (II) LoadModule: "ramdac"
[    26.335] (II) LoadModule: "dri3"
[    26.335] (II) LoadModule: "dri2"
[    26.335] (II) LoadModule: "present"
[    26.336] (II) LoadModule: "glxserver_nvidia"
[    27.187] (II) LoadModule: "dri2"
[    27.254] (II) LoadModule: "libinput"
~~~

~~~
$ glxinfo | grep -i vulkan
~~~

~~~
$ vulkaninfo | head -n 15
$ nvidia-smi
~~~


### Problema al compilar iluminación
~~~
- Enabled UDP Messaging Plugin

$ sudo route add -net 224.0.0.0 netmask 240.0.0.0 dev lo
$ sudo ifconfig lo multicast
~~~


### Plugins Principales
~~~
- Content Browser - Asset Data Source
- Content Browser - Class Data Source
- Plugin Browser
- UDP Messaging
- GeometryMode
~~~
