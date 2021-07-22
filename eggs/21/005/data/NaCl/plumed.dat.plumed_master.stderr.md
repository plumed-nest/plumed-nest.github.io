**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  NaCl/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTORCH_MODEL LABEL=auto1 MODEL=nacl_sfNa_ct1.pt ARG=s1.Sk3_-3_-3,s1.Sk3_-3_3,s1.Sk3_3_-3,s1.Sk3_3_3,s1.Sk6_0_0,s1.Sk0_6_-6,s1.Sk0_6_6,s1.Sk6_-6_0,s1.Sk6_0_-6,s1.Sk6_0_6,s1.Sk6_6_0,s1.Sk9_-3_-3,s1.Sk9_-3_3,s1.Sk9_3_-3,s1.Sk9_3_3
Maybe a missing space or a typo?
[fv-az95-172:46563] *** Process received signal ***
[fv-az95-172:46563] Signal: Aborted (6)
[fv-az95-172:46563] Signal code:  (-6)
[fv-az95-172:46563] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe35af42210]
[fv-az95-172:46563] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe35af4218b]
[fv-az95-172:46563] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe35af21859]
[fv-az95-172:46563] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe35b1a9911]
[fv-az95-172:46563] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe35b1b538c]
[fv-az95-172:46563] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe35b1b53f7]
[fv-az95-172:46563] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fe35b1b56fd]
[fv-az95-172:46563] [ 7] plumed_master(+0xf5b5)[0x55f11d9445b5]
[fv-az95-172:46563] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe35af230b3]
[fv-az95-172:46563] [ 9] plumed_master(+0xf8be)[0x55f11d9448be]
[fv-az95-172:46563] *** End of error message ***
</pre>
{% endraw %}
