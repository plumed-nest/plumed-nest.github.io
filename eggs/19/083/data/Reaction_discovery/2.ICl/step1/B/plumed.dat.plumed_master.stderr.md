**Project ID:** [plumID:19.083]({{ '/' | absolute_url }}eggs/19/083/)  
Stderr for source:  Reaction_discovery/2.ICl/step1/B/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label restraint : restart file ..//HILLS.2 not found
[fv-az95-172:53907] *** Process received signal ***
[fv-az95-172:53907] Signal: Aborted (6)
[fv-az95-172:53907] Signal code:  (-6)
[fv-az95-172:53907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc1d1c16210]
[fv-az95-172:53907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc1d1c1618b]
[fv-az95-172:53907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc1d1bf5859]
[fv-az95-172:53907] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc1d1e7d911]
[fv-az95-172:53907] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc1d1e8938c]
[fv-az95-172:53907] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc1d1e893f7]
[fv-az95-172:53907] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fc1d1e896fd]
[fv-az95-172:53907] [ 7] plumed_master(+0xf5b5)[0x55cd1fef75b5]
[fv-az95-172:53907] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc1d1bf70b3]
[fv-az95-172:53907] [ 9] plumed_master(+0xf8be)[0x55cd1fef78be]
[fv-az95-172:53907] *** End of error message ***
</pre>
{% endraw %}
