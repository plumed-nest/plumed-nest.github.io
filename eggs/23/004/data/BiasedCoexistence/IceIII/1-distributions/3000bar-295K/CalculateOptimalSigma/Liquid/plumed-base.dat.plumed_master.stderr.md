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
[runnervm0kj6c:06509] *** Process received signal ***
[runnervm0kj6c:06509] Signal: Aborted (6)
[runnervm0kj6c:06509] Signal code:  (-6)
[runnervm0kj6c:06509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff500645330]
[runnervm0kj6c:06509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff50069eb2c]
[runnervm0kj6c:06509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff50064527e]
[runnervm0kj6c:06509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5006288ff]
[runnervm0kj6c:06509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff500aa5ff5]
[runnervm0kj6c:06509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff500abb0da]
[runnervm0kj6c:06509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff500aa5a55]
[runnervm0kj6c:06509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff500aa5a6f]
[runnervm0kj6c:06509] [ 8] plumed_master(+0x146dd)[0x5655489306dd]
[runnervm0kj6c:06509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff50062a1ca]
[runnervm0kj6c:06509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff50062a28b]
[runnervm0kj6c:06509] [11] plumed_master(+0x15365)[0x565548931365]
[runnervm0kj6c:06509] *** End of error message ***
</pre>
{% endraw %}
