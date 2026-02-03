**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmkj6or:06936] *** Process received signal ***
[runnervmkj6or:06936] Signal: Aborted (6)
[runnervmkj6or:06936] Signal code:  (-6)
[runnervmkj6or:06936] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f85fea45330]
[runnervmkj6or:06936] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f85fea9eb2c]
[runnervmkj6or:06936] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f85fea4527e]
[runnervmkj6or:06936] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f85fea288ff]
[runnervmkj6or:06936] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f85feea5ff5]
[runnervmkj6or:06936] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f85feebb0da]
[runnervmkj6or:06936] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f85feea5a55]
[runnervmkj6or:06936] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f85feea5a6f]
[runnervmkj6or:06936] [ 8] plumed_master(+0x146dd)[0x55ef987396dd]
[runnervmkj6or:06936] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f85fea2a1ca]
[runnervmkj6or:06936] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f85fea2a28b]
[runnervmkj6or:06936] [11] plumed_master(+0x15365)[0x55ef9873a365]
[runnervmkj6or:06936] *** End of error message ***
</pre>
{% endraw %}
