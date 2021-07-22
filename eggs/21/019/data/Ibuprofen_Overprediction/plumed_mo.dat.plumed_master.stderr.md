**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
(download [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action DISTANCE with label @0 : Number of specified atoms should be 2
[fv-az95-172:34762] *** Process received signal ***
[fv-az95-172:34762] Signal: Aborted (6)
[fv-az95-172:34762] Signal code:  (-6)
[fv-az95-172:34762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa2d1ebb210]
[fv-az95-172:34762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa2d1ebb18b]
[fv-az95-172:34762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa2d1e9a859]
[fv-az95-172:34762] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa2d2122911]
[fv-az95-172:34762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa2d212e38c]
[fv-az95-172:34762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa2d212e3f7]
[fv-az95-172:34762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fa2d212e6fd]
[fv-az95-172:34762] [ 7] plumed_master(+0xf5b5)[0x557dbd2fb5b5]
[fv-az95-172:34762] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa2d1e9c0b3]
[fv-az95-172:34762] [ 9] plumed_master(+0xf8be)[0x557dbd2fb8be]
[fv-az95-172:34762] *** End of error message ***
</pre>
{% endraw %}
