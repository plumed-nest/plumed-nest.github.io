**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  COMet_Path/plumed.dat   
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
[fv-az95-172:52426] *** Process received signal ***
[fv-az95-172:52426] Signal: Aborted (6)
[fv-az95-172:52426] Signal code:  (-6)
[fv-az95-172:52426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7f7be8e210]
[fv-az95-172:52426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7f7be8e18b]
[fv-az95-172:52426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7f7be6d859]
[fv-az95-172:52426] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7f7c0f5911]
[fv-az95-172:52426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7f7c10138c]
[fv-az95-172:52426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7f7c1013f7]
[fv-az95-172:52426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f7f7c1016fd]
[fv-az95-172:52426] [ 7] plumed_master(+0xf5b5)[0x557f6e3715b5]
[fv-az95-172:52426] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7f7be6f0b3]
[fv-az95-172:52426] [ 9] plumed_master(+0xf8be)[0x557f6e3718be]
[fv-az95-172:52426] *** End of error message ***
</pre>
{% endraw %}
