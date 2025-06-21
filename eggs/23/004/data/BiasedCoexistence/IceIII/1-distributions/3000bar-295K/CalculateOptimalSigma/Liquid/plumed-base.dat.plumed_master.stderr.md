**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:07883] *** Process received signal ***
[pkrvmxyh4eaekms:07883] Signal: Aborted (6)
[pkrvmxyh4eaekms:07883] Signal code:  (-6)
[pkrvmxyh4eaekms:07883] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc468845330]
[pkrvmxyh4eaekms:07883] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc46889eb2c]
[pkrvmxyh4eaekms:07883] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc46884527e]
[pkrvmxyh4eaekms:07883] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4688288ff]
[pkrvmxyh4eaekms:07883] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc468ca5ff5]
[pkrvmxyh4eaekms:07883] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc468cbb0da]
[pkrvmxyh4eaekms:07883] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc468ca5a55]
[pkrvmxyh4eaekms:07883] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc468ca5a6f]
[pkrvmxyh4eaekms:07883] [ 8] plumed_master(+0x146dd)[0x55d55a59f6dd]
[pkrvmxyh4eaekms:07883] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc46882a1ca]
[pkrvmxyh4eaekms:07883] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc46882a28b]
[pkrvmxyh4eaekms:07883] [11] plumed_master(+0x15365)[0x55d55a5a0365]
[pkrvmxyh4eaekms:07883] *** End of error message ***
</pre>
{% endraw %}
