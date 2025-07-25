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
[pkrvmpptgkbjq6m:07983] *** Process received signal ***
[pkrvmpptgkbjq6m:07983] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07983] Signal code:  (-6)
[pkrvmpptgkbjq6m:07983] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe41b845330]
[pkrvmpptgkbjq6m:07983] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe41b89eb2c]
[pkrvmpptgkbjq6m:07983] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe41b84527e]
[pkrvmpptgkbjq6m:07983] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe41b8288ff]
[pkrvmpptgkbjq6m:07983] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe41bca5ff5]
[pkrvmpptgkbjq6m:07983] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe41bcbb0da]
[pkrvmpptgkbjq6m:07983] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe41bca5a55]
[pkrvmpptgkbjq6m:07983] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe41bca5a6f]
[pkrvmpptgkbjq6m:07983] [ 8] plumed_master(+0x146dd)[0x564e2a7756dd]
[pkrvmpptgkbjq6m:07983] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe41b82a1ca]
[pkrvmpptgkbjq6m:07983] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe41b82a28b]
[pkrvmpptgkbjq6m:07983] [11] plumed_master(+0x15365)[0x564e2a776365]
[pkrvmpptgkbjq6m:07983] *** End of error message ***
</pre>
{% endraw %}
