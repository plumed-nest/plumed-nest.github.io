**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
(download [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az95-172:61014] *** Process received signal ***
[fv-az95-172:61014] Signal: Aborted (6)
[fv-az95-172:61014] Signal code:  (-6)
[fv-az95-172:61014] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5d01b11210]
[fv-az95-172:61014] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5d01b1118b]
[fv-az95-172:61014] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5d01af0859]
[fv-az95-172:61014] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5d01d78911]
[fv-az95-172:61014] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5d01d8438c]
[fv-az95-172:61014] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5d01d843f7]
[fv-az95-172:61014] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f5d01d846fd]
[fv-az95-172:61014] [ 7] plumed_master(+0xf5b5)[0x55ebed0225b5]
[fv-az95-172:61014] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5d01af20b3]
[fv-az95-172:61014] [ 9] plumed_master(+0xf8be)[0x55ebed0228be]
[fv-az95-172:61014] *** End of error message ***
</pre>
{% endraw %}
