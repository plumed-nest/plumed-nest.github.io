**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
(download [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az95-172:60969] *** Process received signal ***
[fv-az95-172:60969] Signal: Aborted (6)
[fv-az95-172:60969] Signal code:  (-6)
[fv-az95-172:60969] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc1344b9210]
[fv-az95-172:60969] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc1344b918b]
[fv-az95-172:60969] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc134498859]
[fv-az95-172:60969] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc134720911]
[fv-az95-172:60969] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc13472c38c]
[fv-az95-172:60969] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc13472c3f7]
[fv-az95-172:60969] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fc13472c6fd]
[fv-az95-172:60969] [ 7] plumed_master(+0xf5b5)[0x556a4bfd25b5]
[fv-az95-172:60969] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc13449a0b3]
[fv-az95-172:60969] [ 9] plumed_master(+0xf8be)[0x556a4bfd28be]
[fv-az95-172:60969] *** End of error message ***
</pre>
{% endraw %}
