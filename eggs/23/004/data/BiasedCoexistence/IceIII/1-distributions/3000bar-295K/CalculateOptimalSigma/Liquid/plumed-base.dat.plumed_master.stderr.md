**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1344-582:61744] *** Process received signal ***
[fv-az1344-582:61744] Signal: Aborted (6)
[fv-az1344-582:61744] Signal code:  (-6)
[fv-az1344-582:61744] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef00045330]
[fv-az1344-582:61744] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef0009eb2c]
[fv-az1344-582:61744] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef0004527e]
[fv-az1344-582:61744] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef000288ff]
[fv-az1344-582:61744] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef004a5ff5]
[fv-az1344-582:61744] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef004bb0da]
[fv-az1344-582:61744] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef004a5a55]
[fv-az1344-582:61744] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef004a5a6f]
[fv-az1344-582:61744] [ 8] plumed_master(+0x146dd)[0x5631d55216dd]
[fv-az1344-582:61744] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef0002a1ca]
[fv-az1344-582:61744] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef0002a28b]
[fv-az1344-582:61744] [11] plumed_master(+0x15365)[0x5631d5522365]
[fv-az1344-582:61744] *** End of error message ***
</pre>
{% endraw %}
