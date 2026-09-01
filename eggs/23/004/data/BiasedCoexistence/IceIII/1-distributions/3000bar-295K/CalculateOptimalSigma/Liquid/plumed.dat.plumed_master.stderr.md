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
[runnervmgx7h7:05688] *** Process received signal ***
[runnervmgx7h7:05688] Signal: Aborted (6)
[runnervmgx7h7:05688] Signal code:  (-6)
[runnervmgx7h7:05688] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c18045330]
[runnervmgx7h7:05688] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c1809ec0c]
[runnervmgx7h7:05688] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c1804527e]
[runnervmgx7h7:05688] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c180288ff]
[runnervmgx7h7:05688] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c184a5ff5]
[runnervmgx7h7:05688] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c184bb0da]
[runnervmgx7h7:05688] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c184a5a55]
[runnervmgx7h7:05688] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c184a5a6f]
[runnervmgx7h7:05688] [ 8] plumed_master(+0x146dd)[0x55e9dc3746dd]
[runnervmgx7h7:05688] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c1802a1ca]
[runnervmgx7h7:05688] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c1802a28b]
[runnervmgx7h7:05688] [11] plumed_master(+0x15365)[0x55e9dc375365]
[runnervmgx7h7:05688] *** End of error message ***
</pre>
{% endraw %}
