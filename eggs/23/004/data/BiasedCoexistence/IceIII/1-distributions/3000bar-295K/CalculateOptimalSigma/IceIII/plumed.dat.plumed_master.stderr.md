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
[pkrvmpptgkbjq6m:07943] *** Process received signal ***
[pkrvmpptgkbjq6m:07943] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07943] Signal code:  (-6)
[pkrvmpptgkbjq6m:07943] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fada6c45330]
[pkrvmpptgkbjq6m:07943] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fada6c9eb2c]
[pkrvmpptgkbjq6m:07943] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fada6c4527e]
[pkrvmpptgkbjq6m:07943] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fada6c288ff]
[pkrvmpptgkbjq6m:07943] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fada70a5ff5]
[pkrvmpptgkbjq6m:07943] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fada70bb0da]
[pkrvmpptgkbjq6m:07943] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fada70a5a55]
[pkrvmpptgkbjq6m:07943] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fada70a5a6f]
[pkrvmpptgkbjq6m:07943] [ 8] plumed_master(+0x146dd)[0x563f76baa6dd]
[pkrvmpptgkbjq6m:07943] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fada6c2a1ca]
[pkrvmpptgkbjq6m:07943] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fada6c2a28b]
[pkrvmpptgkbjq6m:07943] [11] plumed_master(+0x15365)[0x563f76bab365]
[pkrvmpptgkbjq6m:07943] *** End of error message ***
</pre>
{% endraw %}
