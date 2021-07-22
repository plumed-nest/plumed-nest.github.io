**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  1_wolfe_quapp_potential/single_replica/inputs/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=p.x NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-3. GRID_MAX=3. GRID_BIN=50 TEMP=1. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=50000 DECAY=5000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[fv-az95-172:64942] *** Process received signal ***
[fv-az95-172:64942] Signal: Aborted (6)
[fv-az95-172:64942] Signal code:  (-6)
[fv-az95-172:64942] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7faf6380e210]
[fv-az95-172:64942] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7faf6380e18b]
[fv-az95-172:64942] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7faf637ed859]
[fv-az95-172:64942] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7faf63a75911]
[fv-az95-172:64942] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7faf63a8138c]
[fv-az95-172:64942] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7faf63a813f7]
[fv-az95-172:64942] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7faf63a816a9]
[fv-az95-172:64942] [ 7] plumed(+0xf47d)[0x5596073a447d]
[fv-az95-172:64942] [ 8] plumed(+0x14004)[0x5596073a9004]
[fv-az95-172:64942] [ 9] plumed(+0xf698)[0x5596073a4698]
[fv-az95-172:64942] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7faf637ef0b3]
[fv-az95-172:64942] [11] plumed(+0xf76e)[0x5596073a476e]
[fv-az95-172:64942] *** End of error message ***
</pre>
{% endraw %}
