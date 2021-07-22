**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
../../code/PytorchModel.cpp:25:10: fatal error: torch/torch.h: No such file or directory
   25 | #include <torch/torch.h>
      |          ^~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:972, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../code/PytorchModel.cpp

[fv-az95-172:53646] *** Process received signal ***
[fv-az95-172:53646] Signal: Aborted (6)
[fv-az95-172:53646] Signal code:  (-6)
[fv-az95-172:53646] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8f6aea8210]
[fv-az95-172:53646] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8f6aea818b]
[fv-az95-172:53646] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8f6ae87859]
[fv-az95-172:53646] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8f6b10f911]
[fv-az95-172:53646] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8f6b11b38c]
[fv-az95-172:53646] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8f6b11b3f7]
[fv-az95-172:53646] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f8f6b11b6fd]
[fv-az95-172:53646] [ 7] plumed_master(+0xf5b5)[0x55a3417f95b5]
[fv-az95-172:53646] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8f6ae890b3]
[fv-az95-172:53646] [ 9] plumed_master(+0xf8be)[0x55a3417f98be]
[fv-az95-172:53646] *** End of error message ***
</pre>
{% endraw %}
