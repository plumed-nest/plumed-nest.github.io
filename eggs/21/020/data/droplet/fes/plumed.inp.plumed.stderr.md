**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s32 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09409] *** Process received signal ***
[runnervmvrwv9:09409] Signal: Aborted (6)
[runnervmvrwv9:09409] Signal code:  (-6)
[runnervmvrwv9:09409] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4372e45330]
[runnervmvrwv9:09409] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4372e9eb2c]
[runnervmvrwv9:09409] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4372e4527e]
[runnervmvrwv9:09409] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4372e288ff]
[runnervmvrwv9:09409] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43732a5ff5]
[runnervmvrwv9:09409] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43732bb0da]
[runnervmvrwv9:09409] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43732a5a55]
[runnervmvrwv9:09409] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43732a5a6f]
[runnervmvrwv9:09409] [ 8] plumed(+0x146dd)[0x559530d886dd]
[runnervmvrwv9:09409] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4372e2a1ca]
[runnervmvrwv9:09409] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4372e2a28b]
[runnervmvrwv9:09409] [11] plumed(+0x15365)[0x559530d89365]
[runnervmvrwv9:09409] *** End of error message ***
</pre>
{% endraw %}
