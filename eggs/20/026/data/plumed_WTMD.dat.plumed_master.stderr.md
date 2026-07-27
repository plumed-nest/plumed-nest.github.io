**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s58 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09898] *** Process received signal ***
[runnervmvrwv9:09898] Signal: Aborted (6)
[runnervmvrwv9:09898] Signal code:  (-6)
[runnervmvrwv9:09898] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f90b9045330]
[runnervmvrwv9:09898] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f90b909eb2c]
[runnervmvrwv9:09898] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f90b904527e]
[runnervmvrwv9:09898] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90b90288ff]
[runnervmvrwv9:09898] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90b94a5ff5]
[runnervmvrwv9:09898] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90b94bb0da]
[runnervmvrwv9:09898] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90b94a5a55]
[runnervmvrwv9:09898] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90b94a5a6f]
[runnervmvrwv9:09898] [ 8] plumed_master(+0x146dd)[0x5623a86396dd]
[runnervmvrwv9:09898] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f90b902a1ca]
[runnervmvrwv9:09898] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f90b902a28b]
[runnervmvrwv9:09898] [11] plumed_master(+0x15365)[0x5623a863a365]
[runnervmvrwv9:09898] *** End of error message ***
</pre>
{% endraw %}
