**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmkj6or:06920] *** Process received signal ***
[runnervmkj6or:06920] Signal: Aborted (6)
[runnervmkj6or:06920] Signal code:  (-6)
[runnervmkj6or:06920] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff48cc45330]
[runnervmkj6or:06920] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff48cc9eb2c]
[runnervmkj6or:06920] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff48cc4527e]
[runnervmkj6or:06920] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff48cc288ff]
[runnervmkj6or:06920] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff48d0a5ff5]
[runnervmkj6or:06920] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff48d0bb0da]
[runnervmkj6or:06920] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff48d0a5a55]
[runnervmkj6or:06920] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff48d0a5a6f]
[runnervmkj6or:06920] [ 8] plumed(+0x146dd)[0x559170cfc6dd]
[runnervmkj6or:06920] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff48cc2a1ca]
[runnervmkj6or:06920] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff48cc2a28b]
[runnervmkj6or:06920] [11] plumed(+0x15365)[0x559170cfd365]
[runnervmkj6or:06920] *** End of error message ***
</pre>
{% endraw %}
