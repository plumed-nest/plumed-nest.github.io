**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az95-172:67644] *** Process received signal ***
[fv-az95-172:67644] Signal: Aborted (6)
[fv-az95-172:67644] Signal code:  (-6)
[fv-az95-172:67644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f74b8983210]
[fv-az95-172:67644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f74b898318b]
[fv-az95-172:67644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f74b8962859]
[fv-az95-172:67644] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f74b8bea911]
[fv-az95-172:67644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f74b8bf638c]
[fv-az95-172:67644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f74b8bf63f7]
[fv-az95-172:67644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f74b8bf66fd]
[fv-az95-172:67644] [ 7] plumed_master(+0xf5b5)[0x556249b315b5]
[fv-az95-172:67644] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f74b89640b3]
[fv-az95-172:67644] [ 9] plumed_master(+0xf8be)[0x556249b318be]
[fv-az95-172:67644] *** End of error message ***
</pre>
{% endraw %}
