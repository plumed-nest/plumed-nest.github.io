**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
(download [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az95-172:60489] *** Process received signal ***
[fv-az95-172:60489] Signal: Aborted (6)
[fv-az95-172:60489] Signal code:  (-6)
[fv-az95-172:60489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f88f1181210]
[fv-az95-172:60489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f88f118118b]
[fv-az95-172:60489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f88f1160859]
[fv-az95-172:60489] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f88f13e8911]
[fv-az95-172:60489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f88f13f438c]
[fv-az95-172:60489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f88f13f43f7]
[fv-az95-172:60489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f88f13f46fd]
[fv-az95-172:60489] [ 7] plumed_master(+0xf5b5)[0x5562ac8cb5b5]
[fv-az95-172:60489] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f88f11620b3]
[fv-az95-172:60489] [ 9] plumed_master(+0xf8be)[0x5562ac8cb8be]
[fv-az95-172:60489] *** End of error message ***
</pre>
{% endraw %}
