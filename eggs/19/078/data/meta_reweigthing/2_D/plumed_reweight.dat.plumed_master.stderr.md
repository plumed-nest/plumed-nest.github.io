**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/2_D/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ITRE LABEL=it ARG=cc.logweights TEMP=1 MAXITER=20
Maybe a missing space or a typo?
[fv-az95-172:55713] *** Process received signal ***
[fv-az95-172:55713] Signal: Aborted (6)
[fv-az95-172:55713] Signal code:  (-6)
[fv-az95-172:55713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f99d6344210]
[fv-az95-172:55713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f99d634418b]
[fv-az95-172:55713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f99d6323859]
[fv-az95-172:55713] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f99d65ab911]
[fv-az95-172:55713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f99d65b738c]
[fv-az95-172:55713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f99d65b73f7]
[fv-az95-172:55713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f99d65b76fd]
[fv-az95-172:55713] [ 7] plumed_master(+0xf5b5)[0x55f5cdb755b5]
[fv-az95-172:55713] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f99d63250b3]
[fv-az95-172:55713] [ 9] plumed_master(+0xf8be)[0x55f5cdb758be]
[fv-az95-172:55713] *** End of error message ***
</pre>
{% endraw %}
