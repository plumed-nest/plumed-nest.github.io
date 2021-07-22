**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
(download [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label n4 : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:33754] *** Process received signal ***
[fv-az95-172:33754] Signal: Aborted (6)
[fv-az95-172:33754] Signal code:  (-6)
[fv-az95-172:33754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1f8c209210]
[fv-az95-172:33754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1f8c20918b]
[fv-az95-172:33754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1f8c1e8859]
[fv-az95-172:33754] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1f8c470911]
[fv-az95-172:33754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1f8c47c38c]
[fv-az95-172:33754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1f8c47c3f7]
[fv-az95-172:33754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f1f8c47c6fd]
[fv-az95-172:33754] [ 7] plumed_master(+0xf5b5)[0x5576d12225b5]
[fv-az95-172:33754] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1f8c1ea0b3]
[fv-az95-172:33754] [ 9] plumed_master(+0xf8be)[0x5576d12228be]
[fv-az95-172:33754] *** End of error message ***
</pre>
{% endraw %}
