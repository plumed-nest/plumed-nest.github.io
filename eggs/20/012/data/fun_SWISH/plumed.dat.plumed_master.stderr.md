**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_SWISH/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at IFile.cpp:113, function virtual PLMD::IFile& PLMD::IFile::open(const string&)
+++ assertion failed: do_exist
+++ message follows +++
file cmap.dat cannot be found
[fv-az95-172:52499] *** Process received signal ***
[fv-az95-172:52499] Signal: Aborted (6)
[fv-az95-172:52499] Signal code:  (-6)
[fv-az95-172:52499] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f86fee3a210]
[fv-az95-172:52499] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f86fee3a18b]
[fv-az95-172:52499] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f86fee19859]
[fv-az95-172:52499] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f86ff0a1911]
[fv-az95-172:52499] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f86ff0ad38c]
[fv-az95-172:52499] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f86ff0ad3f7]
[fv-az95-172:52499] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f86ff0ad6fd]
[fv-az95-172:52499] [ 7] plumed_master(+0xf5b5)[0x5575de3535b5]
[fv-az95-172:52499] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f86fee1b0b3]
[fv-az95-172:52499] [ 9] plumed_master(+0xf8be)[0x5575de3538be]
[fv-az95-172:52499] *** End of error message ***
</pre>
{% endraw %}
