**Project ID:** [plumID:19.007]({{ '/' | absolute_url }}eggs/19/007/)  
Stderr for source:  EMMI-MT/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action WHOLEMOLECULES with label @4 : cannot understand the following words from the input line : REF0=3.217,4.340,6.195
[fv-az95-172:72786] *** Process received signal ***
[fv-az95-172:72786] Signal: Aborted (6)
[fv-az95-172:72786] Signal code:  (-6)
[fv-az95-172:72786] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8ec49a2210]
[fv-az95-172:72786] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8ec49a218b]
[fv-az95-172:72786] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8ec4981859]
[fv-az95-172:72786] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8ec4c09911]
[fv-az95-172:72786] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8ec4c1538c]
[fv-az95-172:72786] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8ec4c153f7]
[fv-az95-172:72786] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f8ec4c156fd]
[fv-az95-172:72786] [ 7] plumed_master(+0xf5b5)[0x5602008635b5]
[fv-az95-172:72786] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8ec49830b3]
[fv-az95-172:72786] [ 9] plumed_master(+0xf8be)[0x5602008638be]
[fv-az95-172:72786] *** End of error message ***
</pre>
{% endraw %}
