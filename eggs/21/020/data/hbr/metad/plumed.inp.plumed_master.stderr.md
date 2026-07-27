**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09831] *** Process received signal ***
[runnervmvrwv9:09831] Signal: Aborted (6)
[runnervmvrwv9:09831] Signal code:  (-6)
[runnervmvrwv9:09831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae9e245330]
[runnervmvrwv9:09831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae9e29eb2c]
[runnervmvrwv9:09831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae9e24527e]
[runnervmvrwv9:09831] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae9e2288ff]
[runnervmvrwv9:09831] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae9e6a5ff5]
[runnervmvrwv9:09831] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae9e6bb0da]
[runnervmvrwv9:09831] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae9e6a5a55]
[runnervmvrwv9:09831] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae9e6a5a6f]
[runnervmvrwv9:09831] [ 8] plumed_master(+0x146dd)[0x55c1add9b6dd]
[runnervmvrwv9:09831] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae9e22a1ca]
[runnervmvrwv9:09831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae9e22a28b]
[runnervmvrwv9:09831] [11] plumed_master(+0x15365)[0x55c1add9c365]
[runnervmvrwv9:09831] *** End of error message ***
</pre>
{% endraw %}
