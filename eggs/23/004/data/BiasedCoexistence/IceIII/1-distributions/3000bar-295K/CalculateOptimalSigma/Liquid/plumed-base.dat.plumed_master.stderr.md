**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmw9dnm:07685] *** Process received signal ***
[runnervmw9dnm:07685] Signal: Aborted (6)
[runnervmw9dnm:07685] Signal code:  (-6)
[runnervmw9dnm:07685] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe6d9e45330]
[runnervmw9dnm:07685] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe6d9e9eb2c]
[runnervmw9dnm:07685] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe6d9e4527e]
[runnervmw9dnm:07685] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6d9e288ff]
[runnervmw9dnm:07685] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6da2a5ff5]
[runnervmw9dnm:07685] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6da2bb0da]
[runnervmw9dnm:07685] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6da2a5a55]
[runnervmw9dnm:07685] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6da2a5a6f]
[runnervmw9dnm:07685] [ 8] plumed_master(+0x146dd)[0x55f5ce81b6dd]
[runnervmw9dnm:07685] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe6d9e2a1ca]
[runnervmw9dnm:07685] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe6d9e2a28b]
[runnervmw9dnm:07685] [11] plumed_master(+0x15365)[0x55f5ce81c365]
[runnervmw9dnm:07685] *** End of error message ***
</pre>
{% endraw %}
