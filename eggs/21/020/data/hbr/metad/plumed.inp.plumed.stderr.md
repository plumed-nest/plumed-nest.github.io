**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:08691] *** Process received signal ***
[runnervmgx7h7:08691] Signal: Aborted (6)
[runnervmgx7h7:08691] Signal code:  (-6)
[runnervmgx7h7:08691] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f085d245330]
[runnervmgx7h7:08691] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f085d29ec0c]
[runnervmgx7h7:08691] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f085d24527e]
[runnervmgx7h7:08691] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f085d2288ff]
[runnervmgx7h7:08691] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f085d6a5ff5]
[runnervmgx7h7:08691] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f085d6bb0da]
[runnervmgx7h7:08691] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f085d6a5a55]
[runnervmgx7h7:08691] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f085d6a5a6f]
[runnervmgx7h7:08691] [ 8] plumed(+0x146dd)[0x55e47893a6dd]
[runnervmgx7h7:08691] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f085d22a1ca]
[runnervmgx7h7:08691] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f085d22a28b]
[runnervmgx7h7:08691] [11] plumed(+0x15365)[0x55e47893b365]
[runnervmgx7h7:08691] *** End of error message ***
</pre>
{% endraw %}
