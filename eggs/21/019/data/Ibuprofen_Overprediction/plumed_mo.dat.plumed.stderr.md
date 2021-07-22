**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
(download [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action DISTANCE with label @0 : Number of specified atoms should be 2
[fv-az95-172:34754] *** Process received signal ***
[fv-az95-172:34754] Signal: Aborted (6)
[fv-az95-172:34754] Signal code:  (-6)
[fv-az95-172:34754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1a7b08a210]
[fv-az95-172:34754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1a7b08a18b]
[fv-az95-172:34754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1a7b069859]
[fv-az95-172:34754] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1a7b2f1911]
[fv-az95-172:34754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1a7b2fd38c]
[fv-az95-172:34754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1a7b2fd3f7]
[fv-az95-172:34754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1a7b2fd6a9]
[fv-az95-172:34754] [ 7] plumed(+0xf47d)[0x55739778547d]
[fv-az95-172:34754] [ 8] plumed(+0x14004)[0x55739778a004]
[fv-az95-172:34754] [ 9] plumed(+0xf698)[0x557397785698]
[fv-az95-172:34754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1a7b06b0b3]
[fv-az95-172:34754] [11] plumed(+0xf76e)[0x55739778576e]
[fv-az95-172:34754] *** End of error message ***
</pre>
{% endraw %}
