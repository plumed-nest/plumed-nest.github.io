**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/6_D/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ITRE LABEL=it ARG=cc.logweights TEMP=1 MAXITER=10
Maybe a missing space or a typo?
[fv-az95-172:55854] *** Process received signal ***
[fv-az95-172:55854] Signal: Aborted (6)
[fv-az95-172:55854] Signal code:  (-6)
[fv-az95-172:55854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6024542210]
[fv-az95-172:55854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f602454218b]
[fv-az95-172:55854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6024521859]
[fv-az95-172:55854] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f60247a9911]
[fv-az95-172:55854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f60247b538c]
[fv-az95-172:55854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f60247b53f7]
[fv-az95-172:55854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f60247b56fd]
[fv-az95-172:55854] [ 7] plumed_master(+0xf5b5)[0x557dde2f25b5]
[fv-az95-172:55854] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f60245230b3]
[fv-az95-172:55854] [ 9] plumed_master(+0xf8be)[0x557dde2f28be]
[fv-az95-172:55854] *** End of error message ***
</pre>
{% endraw %}
