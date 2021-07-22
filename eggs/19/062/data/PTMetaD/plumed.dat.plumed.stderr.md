**Project ID:** [plumID:19.062]({{ '/' | absolute_url }}eggs/19/062/)  
Stderr for source:  PTMetaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label cvbias : cannot understand the following words from the input line : REWEIGHTING_NGRID=5001, REWEIGHTING_NHILLS=10
[fv-az95-172:64837] *** Process received signal ***
[fv-az95-172:64837] Signal: Aborted (6)
[fv-az95-172:64837] Signal code:  (-6)
[fv-az95-172:64837] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fef34700210]
[fv-az95-172:64837] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fef3470018b]
[fv-az95-172:64837] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fef346df859]
[fv-az95-172:64837] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fef34967911]
[fv-az95-172:64837] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fef3497338c]
[fv-az95-172:64837] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fef349733f7]
[fv-az95-172:64837] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fef349736a9]
[fv-az95-172:64837] [ 7] plumed(+0xf47d)[0x55d421b2d47d]
[fv-az95-172:64837] [ 8] plumed(+0x14004)[0x55d421b32004]
[fv-az95-172:64837] [ 9] plumed(+0xf698)[0x55d421b2d698]
[fv-az95-172:64837] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fef346e10b3]
[fv-az95-172:64837] [11] plumed(+0xf76e)[0x55d421b2d76e]
[fv-az95-172:64837] *** End of error message ***
</pre>
{% endraw %}
