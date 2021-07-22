**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_SWISH/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at IFile.cpp:113, function virtual PLMD::IFile& PLMD::IFile::open(const string&)
+++ assertion failed: do_exist
+++ message follows +++
file cmap.dat cannot be found
[fv-az95-172:52479] *** Process received signal ***
[fv-az95-172:52479] Signal: Aborted (6)
[fv-az95-172:52479] Signal code:  (-6)
[fv-az95-172:52479] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f218d622210]
[fv-az95-172:52479] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f218d62218b]
[fv-az95-172:52479] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f218d601859]
[fv-az95-172:52479] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f218d889911]
[fv-az95-172:52479] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f218d89538c]
[fv-az95-172:52479] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f218d8953f7]
[fv-az95-172:52479] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f218d8956a9]
[fv-az95-172:52479] [ 7] plumed(+0xf47d)[0x55b936fdc47d]
[fv-az95-172:52479] [ 8] plumed(+0x14004)[0x55b936fe1004]
[fv-az95-172:52479] [ 9] plumed(+0xf698)[0x55b936fdc698]
[fv-az95-172:52479] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f218d6030b3]
[fv-az95-172:52479] [11] plumed(+0xf76e)[0x55b936fdc76e]
[fv-az95-172:52479] *** End of error message ***
</pre>
{% endraw %}
