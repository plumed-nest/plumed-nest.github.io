**Project ID:** [plumID:19.062]({{ '/' | absolute_url }}eggs/19/062/)  
Stderr for source:  PTMetaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label cvbias : cannot understand the following words from the input line : REWEIGHTING_NGRID=5001, REWEIGHTING_NHILLS=10
[fv-az95-172:64845] *** Process received signal ***
[fv-az95-172:64845] Signal: Aborted (6)
[fv-az95-172:64845] Signal code:  (-6)
[fv-az95-172:64845] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f250ea55210]
[fv-az95-172:64845] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f250ea5518b]
[fv-az95-172:64845] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f250ea34859]
[fv-az95-172:64845] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f250ecbc911]
[fv-az95-172:64845] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f250ecc838c]
[fv-az95-172:64845] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f250ecc83f7]
[fv-az95-172:64845] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f250ecc86fd]
[fv-az95-172:64845] [ 7] plumed_master(+0xf5b5)[0x55815ab295b5]
[fv-az95-172:64845] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f250ea360b3]
[fv-az95-172:64845] [ 9] plumed_master(+0xf8be)[0x55815ab298be]
[fv-az95-172:64845] *** End of error message ***
</pre>
{% endraw %}
