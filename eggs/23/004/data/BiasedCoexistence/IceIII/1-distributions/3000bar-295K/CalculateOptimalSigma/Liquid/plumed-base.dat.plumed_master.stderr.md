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
[runnervmvrwv9:06716] *** Process received signal ***
[runnervmvrwv9:06716] Signal: Aborted (6)
[runnervmvrwv9:06716] Signal code:  (-6)
[runnervmvrwv9:06716] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc18a045330]
[runnervmvrwv9:06716] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc18a09eb2c]
[runnervmvrwv9:06716] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc18a04527e]
[runnervmvrwv9:06716] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc18a0288ff]
[runnervmvrwv9:06716] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc18a4a5ff5]
[runnervmvrwv9:06716] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc18a4bb0da]
[runnervmvrwv9:06716] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc18a4a5a55]
[runnervmvrwv9:06716] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc18a4a5a6f]
[runnervmvrwv9:06716] [ 8] plumed_master(+0x146dd)[0x55cbc5b496dd]
[runnervmvrwv9:06716] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc18a02a1ca]
[runnervmvrwv9:06716] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc18a02a28b]
[runnervmvrwv9:06716] [11] plumed_master(+0x15365)[0x55cbc5b4a365]
[runnervmvrwv9:06716] *** End of error message ***
</pre>
{% endraw %}
