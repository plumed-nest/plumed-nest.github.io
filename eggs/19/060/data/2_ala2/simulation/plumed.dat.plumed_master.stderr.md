**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  2_ala2/simulation/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=phi NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-pi GRID_MAX=pi GRID_BIN=50 TEMP=300. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=10000 DECAY=1000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[fv-az95-172:64975] *** Process received signal ***
[fv-az95-172:64975] Signal: Aborted (6)
[fv-az95-172:64975] Signal code:  (-6)
[fv-az95-172:64975] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1266370210]
[fv-az95-172:64975] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f126637018b]
[fv-az95-172:64975] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f126634f859]
[fv-az95-172:64975] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f12665d7911]
[fv-az95-172:64975] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f12665e338c]
[fv-az95-172:64975] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f12665e33f7]
[fv-az95-172:64975] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f12665e36fd]
[fv-az95-172:64975] [ 7] plumed_master(+0xf5b5)[0x55b65b9825b5]
[fv-az95-172:64975] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f12663510b3]
[fv-az95-172:64975] [ 9] plumed_master(+0xf8be)[0x55b65b9828be]
[fv-az95-172:64975] *** End of error message ***
</pre>
{% endraw %}
