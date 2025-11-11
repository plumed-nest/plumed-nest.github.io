**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervmw9dnm:13596] *** Process received signal ***
[runnervmw9dnm:13596] Signal: Aborted (6)
[runnervmw9dnm:13596] Signal code:  (-6)
[runnervmw9dnm:13596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41ab845330]
[runnervmw9dnm:13596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41ab89eb2c]
[runnervmw9dnm:13596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41ab84527e]
[runnervmw9dnm:13596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41ab8288ff]
[runnervmw9dnm:13596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41abca5ff5]
[runnervmw9dnm:13596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41abcbb0da]
[runnervmw9dnm:13596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41abca5a55]
[runnervmw9dnm:13596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41abca5a6f]
[runnervmw9dnm:13596] [ 8] plumed_master(+0x146dd)[0x55f9bce646dd]
[runnervmw9dnm:13596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41ab82a1ca]
[runnervmw9dnm:13596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41ab82a28b]
[runnervmw9dnm:13596] [11] plumed_master(+0x15365)[0x55f9bce65365]
[runnervmw9dnm:13596] *** End of error message ***
</pre>
{% endraw %}
