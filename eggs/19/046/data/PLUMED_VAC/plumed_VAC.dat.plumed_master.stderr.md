**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC/plumed_VAC.dat   
(download [zipped raw stdout](plumed_VAC.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: TICA ARG=Prot_norm,wBpock_norm,ab_t,lig_OW_large_norm EIGEN_NUMBERS=4 LAGGED_TIME=150000 TAU_NUMBER=5000 STEP_SIZE=0.5 LOGWEIGHTS=rw
Maybe a missing space or a typo?
[fv-az95-172:66017] *** Process received signal ***
[fv-az95-172:66017] Signal: Aborted (6)
[fv-az95-172:66017] Signal code:  (-6)
[fv-az95-172:66017] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fee943cc210]
[fv-az95-172:66017] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fee943cc18b]
[fv-az95-172:66017] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fee943ab859]
[fv-az95-172:66017] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fee94633911]
[fv-az95-172:66017] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fee9463f38c]
[fv-az95-172:66017] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fee9463f3f7]
[fv-az95-172:66017] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fee9463f6fd]
[fv-az95-172:66017] [ 7] plumed_master(+0xf5b5)[0x556c2e9c25b5]
[fv-az95-172:66017] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fee943ad0b3]
[fv-az95-172:66017] [ 9] plumed_master(+0xf8be)[0x556c2e9c28be]
[fv-az95-172:66017] *** End of error message ***
</pre>
{% endraw %}
