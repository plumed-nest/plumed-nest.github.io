**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmgx7h7:05612] *** Process received signal ***
[runnervmgx7h7:05612] Signal: Aborted (6)
[runnervmgx7h7:05612] Signal code:  (-6)
[runnervmgx7h7:05612] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa042c45330]
[runnervmgx7h7:05612] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa042c9ec0c]
[runnervmgx7h7:05612] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa042c4527e]
[runnervmgx7h7:05612] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa042c288ff]
[runnervmgx7h7:05612] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa0430a5ff5]
[runnervmgx7h7:05612] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa0430bb0da]
[runnervmgx7h7:05612] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa0430a5a55]
[runnervmgx7h7:05612] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa0430a5a6f]
[runnervmgx7h7:05612] [ 8] plumed_master(+0x146dd)[0x5641017636dd]
[runnervmgx7h7:05612] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa042c2a1ca]
[runnervmgx7h7:05612] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa042c2a28b]
[runnervmgx7h7:05612] [11] plumed_master(+0x15365)[0x564101764365]
[runnervmgx7h7:05612] *** End of error message ***
</pre>
{% endraw %}
