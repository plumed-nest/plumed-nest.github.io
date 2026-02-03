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
[runnervmkj6or:05670] *** Process received signal ***
[runnervmkj6or:05670] Signal: Aborted (6)
[runnervmkj6or:05670] Signal code:  (-6)
[runnervmkj6or:05670] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc400c45330]
[runnervmkj6or:05670] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc400c9eb2c]
[runnervmkj6or:05670] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc400c4527e]
[runnervmkj6or:05670] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc400c288ff]
[runnervmkj6or:05670] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4010a5ff5]
[runnervmkj6or:05670] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4010bb0da]
[runnervmkj6or:05670] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4010a5a55]
[runnervmkj6or:05670] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4010a5a6f]
[runnervmkj6or:05670] [ 8] plumed_master(+0x146dd)[0x5600969796dd]
[runnervmkj6or:05670] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc400c2a1ca]
[runnervmkj6or:05670] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc400c2a28b]
[runnervmkj6or:05670] [11] plumed_master(+0x15365)[0x56009697a365]
[runnervmkj6or:05670] *** End of error message ***
</pre>
{% endraw %}
