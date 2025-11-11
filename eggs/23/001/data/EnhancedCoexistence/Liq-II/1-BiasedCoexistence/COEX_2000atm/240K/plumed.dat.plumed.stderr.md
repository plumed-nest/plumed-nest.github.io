**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervmw9dnm:08102] *** Process received signal ***
[runnervmw9dnm:08102] Signal: Aborted (6)
[runnervmw9dnm:08102] Signal code:  (-6)
[runnervmw9dnm:08102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffaea245330]
[runnervmw9dnm:08102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffaea29eb2c]
[runnervmw9dnm:08102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffaea24527e]
[runnervmw9dnm:08102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffaea2288ff]
[runnervmw9dnm:08102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffaea6a5ff5]
[runnervmw9dnm:08102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffaea6bb0da]
[runnervmw9dnm:08102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffaea6a5a55]
[runnervmw9dnm:08102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffaea6a5a6f]
[runnervmw9dnm:08102] [ 8] plumed(+0x146dd)[0x5567d29dd6dd]
[runnervmw9dnm:08102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffaea22a1ca]
[runnervmw9dnm:08102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffaea22a28b]
[runnervmw9dnm:08102] [11] plumed(+0x15365)[0x5567d29de365]
[runnervmw9dnm:08102] *** End of error message ***
</pre>
{% endraw %}
