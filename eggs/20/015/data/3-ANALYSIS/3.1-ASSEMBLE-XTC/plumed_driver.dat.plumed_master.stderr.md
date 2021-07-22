**Project ID:** [plumID:20.015]({{ '/' | absolute_url }}eggs/20/015/)  
Stderr for source:  3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.dat   
(download [zipped raw stdout](plumed_driver.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action WHOLEMOLECULES with label @2 : cannot understand the following words from the input line : REF0=5.3607,4.5911,3.1497, REF1=3.2439,3.3684,6.0308
[fv-az95-172:52198] *** Process received signal ***
[fv-az95-172:52198] Signal: Aborted (6)
[fv-az95-172:52198] Signal code:  (-6)
[fv-az95-172:52198] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe474bd6210]
[fv-az95-172:52198] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe474bd618b]
[fv-az95-172:52198] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe474bb5859]
[fv-az95-172:52198] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe474e3d911]
[fv-az95-172:52198] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe474e4938c]
[fv-az95-172:52198] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe474e493f7]
[fv-az95-172:52198] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fe474e496fd]
[fv-az95-172:52198] [ 7] plumed_master(+0xf5b5)[0x558aaecfa5b5]
[fv-az95-172:52198] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe474bb70b3]
[fv-az95-172:52198] [ 9] plumed_master(+0xf8be)[0x558aaecfa8be]
[fv-az95-172:52198] *** End of error message ***
</pre>
{% endraw %}
