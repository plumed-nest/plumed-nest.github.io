**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  ala2/3_enhanced_sampling/plumed.dat   
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

[fv-az95-172:53595] *** Process received signal ***
[fv-az95-172:53595] Signal: Aborted (6)
[fv-az95-172:53595] Signal code:  (-6)
[fv-az95-172:53595] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f67befc2210]
[fv-az95-172:53595] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f67befc218b]
[fv-az95-172:53595] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f67befa1859]
[fv-az95-172:53595] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f67bf229911]
[fv-az95-172:53595] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f67bf23538c]
[fv-az95-172:53595] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f67bf2353f7]
[fv-az95-172:53595] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f67bf2356a9]
[fv-az95-172:53595] [ 7] plumed(+0xf47d)[0x55c9a040547d]
[fv-az95-172:53595] [ 8] plumed(+0x14004)[0x55c9a040a004]
[fv-az95-172:53595] [ 9] plumed(+0xf698)[0x55c9a0405698]
[fv-az95-172:53595] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f67befa30b3]
[fv-az95-172:53595] [11] plumed(+0xf76e)[0x55c9a040576e]
[fv-az95-172:53595] *** End of error message ***
</pre>
{% endraw %}
