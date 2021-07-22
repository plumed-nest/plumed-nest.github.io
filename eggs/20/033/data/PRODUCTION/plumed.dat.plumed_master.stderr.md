**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[fv-az95-172:47904] *** Process received signal ***
[fv-az95-172:47904] Signal: Aborted (6)
[fv-az95-172:47904] Signal code:  (-6)
[fv-az95-172:47904] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4967635210]
[fv-az95-172:47904] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f496763518b]
[fv-az95-172:47904] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4967614859]
[fv-az95-172:47904] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f496789c911]
[fv-az95-172:47904] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f49678a838c]
[fv-az95-172:47904] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f49678a83f7]
[fv-az95-172:47904] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f49678a86fd]
[fv-az95-172:47904] [ 7] plumed_master(+0xf5b5)[0x562147b8e5b5]
[fv-az95-172:47904] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f49676160b3]
[fv-az95-172:47904] [ 9] plumed_master(+0xf8be)[0x562147b8e8be]
[fv-az95-172:47904] *** End of error message ***
</pre>
{% endraw %}
