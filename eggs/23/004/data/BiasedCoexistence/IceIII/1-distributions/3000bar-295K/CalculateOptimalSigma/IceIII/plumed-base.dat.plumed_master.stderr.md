**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmw9dnm:07605] *** Process received signal ***
[runnervmw9dnm:07605] Signal: Aborted (6)
[runnervmw9dnm:07605] Signal code:  (-6)
[runnervmw9dnm:07605] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0647445330]
[runnervmw9dnm:07605] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f064749eb2c]
[runnervmw9dnm:07605] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f064744527e]
[runnervmw9dnm:07605] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06474288ff]
[runnervmw9dnm:07605] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06478a5ff5]
[runnervmw9dnm:07605] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06478bb0da]
[runnervmw9dnm:07605] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06478a5a55]
[runnervmw9dnm:07605] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06478a5a6f]
[runnervmw9dnm:07605] [ 8] plumed_master(+0x146dd)[0x55ed421ae6dd]
[runnervmw9dnm:07605] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f064742a1ca]
[runnervmw9dnm:07605] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f064742a28b]
[runnervmw9dnm:07605] [11] plumed_master(+0x15365)[0x55ed421af365]
[runnervmw9dnm:07605] *** End of error message ***
</pre>
{% endraw %}
