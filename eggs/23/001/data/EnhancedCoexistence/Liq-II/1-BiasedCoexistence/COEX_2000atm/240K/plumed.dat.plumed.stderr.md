**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervmmklqx:08271] *** Process received signal ***
[runnervmmklqx:08271] Signal: Aborted (6)
[runnervmmklqx:08271] Signal code:  (-6)
[runnervmmklqx:08271] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2f38045330]
[runnervmmklqx:08271] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2f3809eb2c]
[runnervmmklqx:08271] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2f3804527e]
[runnervmmklqx:08271] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2f380288ff]
[runnervmmklqx:08271] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2f384a5ff5]
[runnervmmklqx:08271] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2f384bb0da]
[runnervmmklqx:08271] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2f384a5a55]
[runnervmmklqx:08271] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2f384a5a6f]
[runnervmmklqx:08271] [ 8] plumed(+0x146dd)[0x55cc7b6ae6dd]
[runnervmmklqx:08271] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2f3802a1ca]
[runnervmmklqx:08271] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2f3802a28b]
[runnervmmklqx:08271] [11] plumed(+0x15365)[0x55cc7b6af365]
[runnervmmklqx:08271] *** End of error message ***
</pre>
{% endraw %}
