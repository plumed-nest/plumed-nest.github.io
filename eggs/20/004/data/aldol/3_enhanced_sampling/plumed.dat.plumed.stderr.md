**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
../../code/PytorchModel.cpp:25:10: fatal error: torch/torch.h: No such file or directory
   25 | #include <torch/torch.h>
      |          ^~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed"/scripts/mklib.sh ../../code/PytorchModel.cpp

[fv-az95-172:53631] *** Process received signal ***
[fv-az95-172:53631] Signal: Aborted (6)
[fv-az95-172:53631] Signal code:  (-6)
[fv-az95-172:53631] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3f2e3a4210]
[fv-az95-172:53631] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3f2e3a418b]
[fv-az95-172:53631] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3f2e383859]
[fv-az95-172:53631] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3f2e60b911]
[fv-az95-172:53631] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3f2e61738c]
[fv-az95-172:53631] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3f2e6173f7]
[fv-az95-172:53631] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3f2e6176a9]
[fv-az95-172:53631] [ 7] plumed(+0xf47d)[0x561bf449647d]
[fv-az95-172:53631] [ 8] plumed(+0x14004)[0x561bf449b004]
[fv-az95-172:53631] [ 9] plumed(+0xf698)[0x561bf4496698]
[fv-az95-172:53631] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3f2e3850b3]
[fv-az95-172:53631] [11] plumed(+0xf76e)[0x561bf449676e]
[fv-az95-172:53631] *** End of error message ***
</pre>
{% endraw %}
