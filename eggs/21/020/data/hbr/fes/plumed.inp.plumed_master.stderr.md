**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:08604] *** Process received signal ***
[runnervmgx7h7:08604] Signal: Aborted (6)
[runnervmgx7h7:08604] Signal code:  (-6)
[runnervmgx7h7:08604] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac96845330]
[runnervmgx7h7:08604] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac9689ec0c]
[runnervmgx7h7:08604] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac9684527e]
[runnervmgx7h7:08604] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac968288ff]
[runnervmgx7h7:08604] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac96ca5ff5]
[runnervmgx7h7:08604] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac96cbb0da]
[runnervmgx7h7:08604] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac96ca5a55]
[runnervmgx7h7:08604] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac96ca5a6f]
[runnervmgx7h7:08604] [ 8] plumed_master(+0x146dd)[0x5603b8c1c6dd]
[runnervmgx7h7:08604] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac9682a1ca]
[runnervmgx7h7:08604] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac9682a28b]
[runnervmgx7h7:08604] [11] plumed_master(+0x15365)[0x5603b8c1d365]
[runnervmgx7h7:08604] *** End of error message ***
</pre>
{% endraw %}
