**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmmklqx:06612] *** Process received signal ***
[runnervmmklqx:06612] Signal: Aborted (6)
[runnervmmklqx:06612] Signal code:  (-6)
[runnervmmklqx:06612] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f768b245330]
[runnervmmklqx:06612] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f768b29eb2c]
[runnervmmklqx:06612] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f768b24527e]
[runnervmmklqx:06612] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f768b2288ff]
[runnervmmklqx:06612] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f768b6a5ff5]
[runnervmmklqx:06612] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f768b6bb0da]
[runnervmmklqx:06612] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f768b6a5a55]
[runnervmmklqx:06612] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f768b6a5a6f]
[runnervmmklqx:06612] [ 8] plumed_master(+0x146dd)[0x5618a8aa76dd]
[runnervmmklqx:06612] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f768b22a1ca]
[runnervmmklqx:06612] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f768b22a28b]
[runnervmmklqx:06612] [11] plumed_master(+0x15365)[0x5618a8aa8365]
[runnervmmklqx:06612] *** End of error message ***
</pre>
{% endraw %}
