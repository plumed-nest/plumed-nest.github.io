**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervm76f27:08118] *** Process received signal ***
[runnervm76f27:08118] Signal: Aborted (6)
[runnervm76f27:08118] Signal code:  (-6)
[runnervm76f27:08118] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1264245330]
[runnervm76f27:08118] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f126429ec0c]
[runnervm76f27:08118] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f126424527e]
[runnervm76f27:08118] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12642288ff]
[runnervm76f27:08118] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12646a5ff5]
[runnervm76f27:08118] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12646bb0da]
[runnervm76f27:08118] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12646a5a55]
[runnervm76f27:08118] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12646a5a6f]
[runnervm76f27:08118] [ 8] plumed_master(+0x146dd)[0x55e64e50d6dd]
[runnervm76f27:08118] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f126422a1ca]
[runnervm76f27:08118] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f126422a28b]
[runnervm76f27:08118] [11] plumed_master(+0x15365)[0x55e64e50e365]
[runnervm76f27:08118] *** End of error message ***
</pre>
{% endraw %}
