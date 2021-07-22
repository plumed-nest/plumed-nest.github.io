**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  meta_inputs/LJ-38/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:34033] *** Process received signal ***
[fv-az95-172:34033] Signal: Aborted (6)
[fv-az95-172:34033] Signal code:  (-6)
[fv-az95-172:34033] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8bea85a210]
[fv-az95-172:34033] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8bea85a18b]
[fv-az95-172:34033] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8bea839859]
[fv-az95-172:34033] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8beaac1911]
[fv-az95-172:34033] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8beaacd38c]
[fv-az95-172:34033] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8beaacd3f7]
[fv-az95-172:34033] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f8beaacd6fd]
[fv-az95-172:34033] [ 7] plumed_master(+0xf5b5)[0x55f4b102d5b5]
[fv-az95-172:34033] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8bea83b0b3]
[fv-az95-172:34033] [ 9] plumed_master(+0xf8be)[0x55f4b102d8be]
[fv-az95-172:34033] *** End of error message ***
</pre>
{% endraw %}
