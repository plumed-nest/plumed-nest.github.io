**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:07843] *** Process received signal ***
[pkrvmxyh4eaekms:07843] Signal: Aborted (6)
[pkrvmxyh4eaekms:07843] Signal code:  (-6)
[pkrvmxyh4eaekms:07843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5801a45330]
[pkrvmxyh4eaekms:07843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5801a9eb2c]
[pkrvmxyh4eaekms:07843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5801a4527e]
[pkrvmxyh4eaekms:07843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5801a288ff]
[pkrvmxyh4eaekms:07843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5801ea5ff5]
[pkrvmxyh4eaekms:07843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5801ebb0da]
[pkrvmxyh4eaekms:07843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5801ea5a55]
[pkrvmxyh4eaekms:07843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5801ea5a6f]
[pkrvmxyh4eaekms:07843] [ 8] plumed_master(+0x146dd)[0x55b2a6f5a6dd]
[pkrvmxyh4eaekms:07843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5801a2a1ca]
[pkrvmxyh4eaekms:07843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5801a2a28b]
[pkrvmxyh4eaekms:07843] [11] plumed_master(+0x15365)[0x55b2a6f5b365]
[pkrvmxyh4eaekms:07843] *** End of error message ***
</pre>
{% endraw %}
