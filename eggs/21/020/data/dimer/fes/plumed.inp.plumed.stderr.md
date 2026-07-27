**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s19 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09560] *** Process received signal ***
[runnervmvrwv9:09560] Signal: Aborted (6)
[runnervmvrwv9:09560] Signal code:  (-6)
[runnervmvrwv9:09560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e92a45330]
[runnervmvrwv9:09560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e92a9eb2c]
[runnervmvrwv9:09560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e92a4527e]
[runnervmvrwv9:09560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e92a288ff]
[runnervmvrwv9:09560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e92ea5ff5]
[runnervmvrwv9:09560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e92ebb0da]
[runnervmvrwv9:09560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e92ea5a55]
[runnervmvrwv9:09560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e92ea5a6f]
[runnervmvrwv9:09560] [ 8] plumed(+0x146dd)[0x55a85e3756dd]
[runnervmvrwv9:09560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e92a2a1ca]
[runnervmvrwv9:09560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e92a2a28b]
[runnervmvrwv9:09560] [11] plumed(+0x15365)[0x55a85e376365]
[runnervmvrwv9:09560] *** End of error message ***
</pre>
{% endraw %}
