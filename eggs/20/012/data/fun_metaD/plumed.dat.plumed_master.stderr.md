**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_metaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PROJECTION_ON_AXIS LABEL=pp AXIS_ATOMS=p1,p2_FS2 ATOM=lig
Maybe a missing space or a typo?
[fv-az95-172:52546] *** Process received signal ***
[fv-az95-172:52546] Signal: Aborted (6)
[fv-az95-172:52546] Signal code:  (-6)
[fv-az95-172:52546] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4b56d40210]
[fv-az95-172:52546] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4b56d4018b]
[fv-az95-172:52546] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4b56d1f859]
[fv-az95-172:52546] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4b56fa7911]
[fv-az95-172:52546] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4b56fb338c]
[fv-az95-172:52546] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4b56fb33f7]
[fv-az95-172:52546] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f4b56fb36fd]
[fv-az95-172:52546] [ 7] plumed_master(+0xf5b5)[0x56053141a5b5]
[fv-az95-172:52546] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4b56d210b3]
[fv-az95-172:52546] [ 9] plumed_master(+0xf8be)[0x56053141a8be]
[fv-az95-172:52546] *** End of error message ***
</pre>
{% endraw %}
