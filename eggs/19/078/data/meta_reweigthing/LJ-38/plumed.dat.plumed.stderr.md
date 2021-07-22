**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:55894] *** Process received signal ***
[fv-az95-172:55894] Signal: Aborted (6)
[fv-az95-172:55894] Signal code:  (-6)
[fv-az95-172:55894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f730648a210]
[fv-az95-172:55894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f730648a18b]
[fv-az95-172:55894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7306469859]
[fv-az95-172:55894] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f73066f1911]
[fv-az95-172:55894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f73066fd38c]
[fv-az95-172:55894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f73066fd3f7]
[fv-az95-172:55894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f73066fd6a9]
[fv-az95-172:55894] [ 7] plumed(+0xf47d)[0x55901a38147d]
[fv-az95-172:55894] [ 8] plumed(+0x14004)[0x55901a386004]
[fv-az95-172:55894] [ 9] plumed(+0xf698)[0x55901a381698]
[fv-az95-172:55894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f730646b0b3]
[fv-az95-172:55894] [11] plumed(+0xf76e)[0x55901a38176e]
[fv-az95-172:55894] *** End of error message ***
</pre>
{% endraw %}
