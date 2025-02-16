**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1939-440:62369] *** Process received signal ***
[fv-az1939-440:62369] Signal: Aborted (6)
[fv-az1939-440:62369] Signal code:  (-6)
[fv-az1939-440:62369] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4609245330]
[fv-az1939-440:62369] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f460929eb2c]
[fv-az1939-440:62369] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f460924527e]
[fv-az1939-440:62369] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46092288ff]
[fv-az1939-440:62369] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46096a5ff5]
[fv-az1939-440:62369] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46096bb0da]
[fv-az1939-440:62369] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46096a5a55]
[fv-az1939-440:62369] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46096a5a6f]
[fv-az1939-440:62369] [ 8] plumed_master(+0x146dd)[0x55c8236836dd]
[fv-az1939-440:62369] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f460922a1ca]
[fv-az1939-440:62369] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f460922a28b]
[fv-az1939-440:62369] [11] plumed_master(+0x15365)[0x55c823684365]
[fv-az1939-440:62369] *** End of error message ***
</pre>
{% endraw %}
