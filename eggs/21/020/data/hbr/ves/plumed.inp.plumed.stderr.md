**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09867] *** Process received signal ***
[runnervmvrwv9:09867] Signal: Aborted (6)
[runnervmvrwv9:09867] Signal code:  (-6)
[runnervmvrwv9:09867] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40f4845330]
[runnervmvrwv9:09867] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40f489eb2c]
[runnervmvrwv9:09867] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40f484527e]
[runnervmvrwv9:09867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40f48288ff]
[runnervmvrwv9:09867] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40f4ca5ff5]
[runnervmvrwv9:09867] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40f4cbb0da]
[runnervmvrwv9:09867] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40f4ca5a55]
[runnervmvrwv9:09867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40f4ca5a6f]
[runnervmvrwv9:09867] [ 8] plumed(+0x146dd)[0x5613e46066dd]
[runnervmvrwv9:09867] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40f482a1ca]
[runnervmvrwv9:09867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40f482a28b]
[runnervmvrwv9:09867] [11] plumed(+0x15365)[0x5613e4607365]
[runnervmvrwv9:09867] *** End of error message ***
</pre>
{% endraw %}
