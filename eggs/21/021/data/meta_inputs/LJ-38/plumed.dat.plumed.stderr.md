**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  meta_inputs/LJ-38/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:34025] *** Process received signal ***
[fv-az95-172:34025] Signal: Aborted (6)
[fv-az95-172:34025] Signal code:  (-6)
[fv-az95-172:34025] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f791e284210]
[fv-az95-172:34025] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f791e28418b]
[fv-az95-172:34025] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f791e263859]
[fv-az95-172:34025] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f791e4eb911]
[fv-az95-172:34025] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f791e4f738c]
[fv-az95-172:34025] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f791e4f73f7]
[fv-az95-172:34025] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f791e4f76a9]
[fv-az95-172:34025] [ 7] plumed(+0xf47d)[0x5592986a447d]
[fv-az95-172:34025] [ 8] plumed(+0x14004)[0x5592986a9004]
[fv-az95-172:34025] [ 9] plumed(+0xf698)[0x5592986a4698]
[fv-az95-172:34025] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f791e2650b3]
[fv-az95-172:34025] [11] plumed(+0xf76e)[0x5592986a476e]
[fv-az95-172:34025] *** End of error message ***
</pre>
{% endraw %}
