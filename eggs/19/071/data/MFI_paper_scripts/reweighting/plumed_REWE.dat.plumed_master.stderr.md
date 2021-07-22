**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
(download [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[fv-az95-172:60582] *** Process received signal ***
[fv-az95-172:60582] Signal: Aborted (6)
[fv-az95-172:60582] Signal code:  (-6)
[fv-az95-172:60582] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa54182d210]
[fv-az95-172:60582] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa54182d18b]
[fv-az95-172:60582] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa54180c859]
[fv-az95-172:60582] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa541a94911]
[fv-az95-172:60582] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa541aa038c]
[fv-az95-172:60582] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa541aa03f7]
[fv-az95-172:60582] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fa541aa06fd]
[fv-az95-172:60582] [ 7] plumed_master(+0xf5b5)[0x55cbcbae25b5]
[fv-az95-172:60582] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa54180e0b3]
[fv-az95-172:60582] [ 9] plumed_master(+0xf8be)[0x55cbcbae28be]
[fv-az95-172:60582] *** End of error message ***
</pre>
{% endraw %}
