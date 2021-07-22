**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  1_wolfe_quapp_potential/single_replica/inputs/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=p.x NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-3. GRID_MAX=3. GRID_BIN=50 TEMP=1. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=50000 DECAY=5000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[fv-az95-172:64950] *** Process received signal ***
[fv-az95-172:64950] Signal: Aborted (6)
[fv-az95-172:64950] Signal code:  (-6)
[fv-az95-172:64950] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f35546c1210]
[fv-az95-172:64950] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f35546c118b]
[fv-az95-172:64950] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f35546a0859]
[fv-az95-172:64950] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3554928911]
[fv-az95-172:64950] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f355493438c]
[fv-az95-172:64950] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f35549343f7]
[fv-az95-172:64950] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f35549346fd]
[fv-az95-172:64950] [ 7] plumed_master(+0xf5b5)[0x56165bf2e5b5]
[fv-az95-172:64950] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f35546a20b3]
[fv-az95-172:64950] [ 9] plumed_master(+0xf8be)[0x56165bf2e8be]
[fv-az95-172:64950] *** End of error message ***
</pre>
{% endraw %}
