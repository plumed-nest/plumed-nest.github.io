**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w2-s10.850/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az95-172:39068] *** Process received signal ***
[fv-az95-172:39068] Signal: Aborted (6)
[fv-az95-172:39068] Signal code:  (-6)
[fv-az95-172:39068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0f5b344210]
[fv-az95-172:39068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0f5b34418b]
[fv-az95-172:39068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0f5b323859]
[fv-az95-172:39068] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0f5b5ab911]
[fv-az95-172:39068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0f5b5b738c]
[fv-az95-172:39068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0f5b5b73f7]
[fv-az95-172:39068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f0f5b5b76fd]
[fv-az95-172:39068] [ 7] plumed_master(+0xf5b5)[0x55afb98125b5]
[fv-az95-172:39068] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0f5b3250b3]
[fv-az95-172:39068] [ 9] plumed_master(+0xf8be)[0x55afb98128be]
[fv-az95-172:39068] *** End of error message ***
</pre>
{% endraw %}
