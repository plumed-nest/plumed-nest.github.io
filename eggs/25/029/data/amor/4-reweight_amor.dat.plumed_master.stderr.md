**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:04401] *** Process received signal ***
[runnervmgx7h7:04401] Signal: Aborted (6)
[runnervmgx7h7:04401] Signal code:  (-6)
[runnervmgx7h7:04401] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71a4c45330]
[runnervmgx7h7:04401] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71a4c9ec0c]
[runnervmgx7h7:04401] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71a4c4527e]
[runnervmgx7h7:04401] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71a4c288ff]
[runnervmgx7h7:04401] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71a50a5ff5]
[runnervmgx7h7:04401] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71a50bb0da]
[runnervmgx7h7:04401] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71a50a5a55]
[runnervmgx7h7:04401] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71a50a5a6f]
[runnervmgx7h7:04401] [ 8] plumed_master(+0x146dd)[0x55a40becf6dd]
[runnervmgx7h7:04401] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71a4c2a1ca]
[runnervmgx7h7:04401] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71a4c2a28b]
[runnervmgx7h7:04401] [11] plumed_master(+0x15365)[0x55a40bed0365]
[runnervmgx7h7:04401] *** End of error message ***
</pre>
{% endraw %}
