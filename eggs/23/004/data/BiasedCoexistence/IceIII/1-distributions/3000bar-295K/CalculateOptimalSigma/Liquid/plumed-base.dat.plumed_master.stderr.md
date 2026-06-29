**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmmklqx:06574] *** Process received signal ***
[runnervmmklqx:06574] Signal: Aborted (6)
[runnervmmklqx:06574] Signal code:  (-6)
[runnervmmklqx:06574] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2688445330]
[runnervmmklqx:06574] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f268849eb2c]
[runnervmmklqx:06574] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f268844527e]
[runnervmmklqx:06574] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f26884288ff]
[runnervmmklqx:06574] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f26888a5ff5]
[runnervmmklqx:06574] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f26888bb0da]
[runnervmmklqx:06574] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f26888a5a55]
[runnervmmklqx:06574] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f26888a5a6f]
[runnervmmklqx:06574] [ 8] plumed_master(+0x146dd)[0x5628844a16dd]
[runnervmmklqx:06574] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f268842a1ca]
[runnervmmklqx:06574] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f268842a28b]
[runnervmmklqx:06574] [11] plumed_master(+0x15365)[0x5628844a2365]
[runnervmmklqx:06574] *** End of error message ***
</pre>
{% endraw %}
