**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  2_ala2/simulation/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=phi NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-pi GRID_MAX=pi GRID_BIN=50 TEMP=300. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=10000 DECAY=1000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[fv-az95-172:64966] *** Process received signal ***
[fv-az95-172:64966] Signal: Aborted (6)
[fv-az95-172:64966] Signal code:  (-6)
[fv-az95-172:64966] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f769b643210]
[fv-az95-172:64966] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f769b64318b]
[fv-az95-172:64966] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f769b622859]
[fv-az95-172:64966] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f769b8aa911]
[fv-az95-172:64966] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f769b8b638c]
[fv-az95-172:64966] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f769b8b63f7]
[fv-az95-172:64966] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f769b8b66a9]
[fv-az95-172:64966] [ 7] plumed(+0xf47d)[0x55fa2514547d]
[fv-az95-172:64966] [ 8] plumed(+0x14004)[0x55fa2514a004]
[fv-az95-172:64966] [ 9] plumed(+0xf698)[0x55fa25145698]
[fv-az95-172:64966] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f769b6240b3]
[fv-az95-172:64966] [11] plumed(+0xf76e)[0x55fa2514576e]
[fv-az95-172:64966] *** End of error message ***
</pre>
{% endraw %}
