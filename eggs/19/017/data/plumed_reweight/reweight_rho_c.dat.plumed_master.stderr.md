**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:12721] *** Process received signal ***
[runnervmgx7h7:12721] Signal: Aborted (6)
[runnervmgx7h7:12721] Signal code:  (-6)
[runnervmgx7h7:12721] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd92d245330]
[runnervmgx7h7:12721] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd92d29ec0c]
[runnervmgx7h7:12721] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd92d24527e]
[runnervmgx7h7:12721] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd92d2288ff]
[runnervmgx7h7:12721] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd92d6a5ff5]
[runnervmgx7h7:12721] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd92d6bb0da]
[runnervmgx7h7:12721] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd92d6a5a55]
[runnervmgx7h7:12721] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd92d6a5a6f]
[runnervmgx7h7:12721] [ 8] plumed_master(+0x146dd)[0x55c138f0a6dd]
[runnervmgx7h7:12721] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd92d22a1ca]
[runnervmgx7h7:12721] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd92d22a28b]
[runnervmgx7h7:12721] [11] plumed_master(+0x15365)[0x55c138f0b365]
[runnervmgx7h7:12721] *** End of error message ***
</pre>
{% endraw %}
