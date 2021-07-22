**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC/plumed_VAC.dat   
(download [zipped raw stdout](plumed_VAC.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: TICA ARG=Prot_norm,wBpock_norm,ab_t,lig_OW_large_norm EIGEN_NUMBERS=4 LAGGED_TIME=150000 TAU_NUMBER=5000 STEP_SIZE=0.5 LOGWEIGHTS=rw
Maybe a missing space or a typo?
[fv-az95-172:66009] *** Process received signal ***
[fv-az95-172:66009] Signal: Aborted (6)
[fv-az95-172:66009] Signal code:  (-6)
[fv-az95-172:66009] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f588c3f1210]
[fv-az95-172:66009] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f588c3f118b]
[fv-az95-172:66009] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f588c3d0859]
[fv-az95-172:66009] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f588c658911]
[fv-az95-172:66009] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f588c66438c]
[fv-az95-172:66009] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f588c6643f7]
[fv-az95-172:66009] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f588c6646a9]
[fv-az95-172:66009] [ 7] plumed(+0xf47d)[0x5650322d847d]
[fv-az95-172:66009] [ 8] plumed(+0x14004)[0x5650322dd004]
[fv-az95-172:66009] [ 9] plumed(+0xf698)[0x5650322d8698]
[fv-az95-172:66009] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f588c3d20b3]
[fv-az95-172:66009] [11] plumed(+0xf76e)[0x5650322d876e]
[fv-az95-172:66009] *** End of error message ***
</pre>
{% endraw %}
