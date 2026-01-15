**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervmmtnos:34507] *** Process received signal ***
[runnervmmtnos:34507] Signal: Aborted (6)
[runnervmmtnos:34507] Signal code:  (-6)
[runnervmmtnos:34507] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ccf645330]
[runnervmmtnos:34507] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ccf69eb2c]
[runnervmmtnos:34507] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ccf64527e]
[runnervmmtnos:34507] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ccf6288ff]
[runnervmmtnos:34507] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ccfaa5ff5]
[runnervmmtnos:34507] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ccfabb0da]
[runnervmmtnos:34507] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ccfaa5a55]
[runnervmmtnos:34507] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ccfaa5a6f]
[runnervmmtnos:34507] [ 8] plumed_master(+0x146dd)[0x55e4a559c6dd]
[runnervmmtnos:34507] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ccf62a1ca]
[runnervmmtnos:34507] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ccf62a28b]
[runnervmmtnos:34507] [11] plumed_master(+0x15365)[0x55e4a559d365]
[runnervmmtnos:34507] *** End of error message ***
</pre>
{% endraw %}
