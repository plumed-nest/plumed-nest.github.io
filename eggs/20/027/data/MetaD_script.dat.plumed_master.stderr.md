**Project ID:** [plumID:20.027]({{ '/' | absolute_url }}eggs/20/027/)  
Stderr for source:  MetaD_script.dat   
(download [zipped raw stdout](MetaD_script.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az95-172:50398] *** Process received signal ***
[fv-az95-172:50398] Signal: Aborted (6)
[fv-az95-172:50398] Signal code:  (-6)
[fv-az95-172:50398] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9e941f1210]
[fv-az95-172:50398] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9e941f118b]
[fv-az95-172:50398] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9e941d0859]
[fv-az95-172:50398] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9e94458911]
[fv-az95-172:50398] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9e9446438c]
[fv-az95-172:50398] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9e944643f7]
[fv-az95-172:50398] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f9e944646fd]
[fv-az95-172:50398] [ 7] plumed_master(+0xf5b5)[0x55c25fae35b5]
[fv-az95-172:50398] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9e941d20b3]
[fv-az95-172:50398] [ 9] plumed_master(+0xf8be)[0x55c25fae38be]
[fv-az95-172:50398] *** End of error message ***
</pre>
{% endraw %}
