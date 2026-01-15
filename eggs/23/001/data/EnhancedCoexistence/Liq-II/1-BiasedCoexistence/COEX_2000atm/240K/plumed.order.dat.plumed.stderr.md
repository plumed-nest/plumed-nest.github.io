**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmmtnos:34596] *** Process received signal ***
[runnervmmtnos:34596] Signal: Aborted (6)
[runnervmmtnos:34596] Signal code:  (-6)
[runnervmmtnos:34596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f04c4c45330]
[runnervmmtnos:34596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f04c4c9eb2c]
[runnervmmtnos:34596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f04c4c4527e]
[runnervmmtnos:34596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04c4c288ff]
[runnervmmtnos:34596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04c50a5ff5]
[runnervmmtnos:34596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04c50bb0da]
[runnervmmtnos:34596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04c50a5a55]
[runnervmmtnos:34596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04c50a5a6f]
[runnervmmtnos:34596] [ 8] plumed(+0x146dd)[0x563ffdbd86dd]
[runnervmmtnos:34596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f04c4c2a1ca]
[runnervmmtnos:34596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f04c4c2a28b]
[runnervmmtnos:34596] [11] plumed(+0x15365)[0x563ffdbd9365]
[runnervmmtnos:34596] *** End of error message ***
</pre>
{% endraw %}
