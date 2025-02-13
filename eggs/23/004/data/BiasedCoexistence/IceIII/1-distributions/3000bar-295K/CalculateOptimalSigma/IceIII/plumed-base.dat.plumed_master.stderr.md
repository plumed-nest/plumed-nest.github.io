**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1657-925:07386] *** Process received signal ***
[fv-az1657-925:07386] Signal: Aborted (6)
[fv-az1657-925:07386] Signal code:  (-6)
[fv-az1657-925:07386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa07d845330]
[fv-az1657-925:07386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa07d89eb2c]
[fv-az1657-925:07386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa07d84527e]
[fv-az1657-925:07386] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa07d8288ff]
[fv-az1657-925:07386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa07dca5ff5]
[fv-az1657-925:07386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa07dcbb0da]
[fv-az1657-925:07386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa07dca5a55]
[fv-az1657-925:07386] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa07dca5a6f]
[fv-az1657-925:07386] [ 8] plumed_master(+0x146dd)[0x55b7052626dd]
[fv-az1657-925:07386] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa07d82a1ca]
[fv-az1657-925:07386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa07d82a28b]
[fv-az1657-925:07386] [11] plumed_master(+0x15365)[0x55b705263365]
[fv-az1657-925:07386] *** End of error message ***
</pre>
{% endraw %}
