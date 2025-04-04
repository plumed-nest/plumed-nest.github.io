**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az805-507:09040] *** Process received signal ***
[fv-az805-507:09040] Signal: Aborted (6)
[fv-az805-507:09040] Signal code:  (-6)
[fv-az805-507:09040] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f60e8e45330]
[fv-az805-507:09040] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f60e8e9eb2c]
[fv-az805-507:09040] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f60e8e4527e]
[fv-az805-507:09040] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60e8e288ff]
[fv-az805-507:09040] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60e92a5ff5]
[fv-az805-507:09040] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60e92bb0da]
[fv-az805-507:09040] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60e92a5a55]
[fv-az805-507:09040] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60e92a5a6f]
[fv-az805-507:09040] [ 8] plumed_master(+0x146dd)[0x56484692a6dd]
[fv-az805-507:09040] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f60e8e2a1ca]
[fv-az805-507:09040] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f60e8e2a28b]
[fv-az805-507:09040] [11] plumed_master(+0x15365)[0x56484692b365]
[fv-az805-507:09040] *** End of error message ***
</pre>
{% endraw %}
