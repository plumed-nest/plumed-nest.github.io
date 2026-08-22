**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervm76f27:11651] *** Process received signal ***
[runnervm76f27:11651] Signal: Aborted (6)
[runnervm76f27:11651] Signal code:  (-6)
[runnervm76f27:11651] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbcc8445330]
[runnervm76f27:11651] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbcc849ec0c]
[runnervm76f27:11651] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbcc844527e]
[runnervm76f27:11651] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbcc84288ff]
[runnervm76f27:11651] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbcc88a5ff5]
[runnervm76f27:11651] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbcc88bb0da]
[runnervm76f27:11651] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbcc88a5a55]
[runnervm76f27:11651] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbcc88a5a6f]
[runnervm76f27:11651] [ 8] plumed_master(+0x146dd)[0x5608ccfd86dd]
[runnervm76f27:11651] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbcc842a1ca]
[runnervm76f27:11651] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbcc842a28b]
[runnervm76f27:11651] [11] plumed_master(+0x15365)[0x5608ccfd9365]
[runnervm76f27:11651] *** End of error message ***
</pre>
{% endraw %}
