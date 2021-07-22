**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:55903] *** Process received signal ***
[fv-az95-172:55903] Signal: Aborted (6)
[fv-az95-172:55903] Signal code:  (-6)
[fv-az95-172:55903] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe91ac4d210]
[fv-az95-172:55903] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe91ac4d18b]
[fv-az95-172:55903] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe91ac2c859]
[fv-az95-172:55903] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe91aeb4911]
[fv-az95-172:55903] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe91aec038c]
[fv-az95-172:55903] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe91aec03f7]
[fv-az95-172:55903] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fe91aec06fd]
[fv-az95-172:55903] [ 7] plumed_master(+0xf5b5)[0x556a64c315b5]
[fv-az95-172:55903] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe91ac2e0b3]
[fv-az95-172:55903] [ 9] plumed_master(+0xf8be)[0x556a64c318be]
[fv-az95-172:55903] *** End of error message ***
</pre>
{% endraw %}
