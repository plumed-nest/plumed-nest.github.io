**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:55919] *** Process received signal ***
[fv-az95-172:55919] Signal: Aborted (6)
[fv-az95-172:55919] Signal code:  (-6)
[fv-az95-172:55919] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f502057f210]
[fv-az95-172:55919] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f502057f18b]
[fv-az95-172:55919] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f502055e859]
[fv-az95-172:55919] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f50207e6911]
[fv-az95-172:55919] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f50207f238c]
[fv-az95-172:55919] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f50207f23f7]
[fv-az95-172:55919] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f50207f26a9]
[fv-az95-172:55919] [ 7] plumed(+0xf47d)[0x55d688b2a47d]
[fv-az95-172:55919] [ 8] plumed(+0x14004)[0x55d688b2f004]
[fv-az95-172:55919] [ 9] plumed(+0xf698)[0x55d688b2a698]
[fv-az95-172:55919] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f50205600b3]
[fv-az95-172:55919] [11] plumed(+0xf76e)[0x55d688b2a76e]
[fv-az95-172:55919] *** End of error message ***
</pre>
{% endraw %}
