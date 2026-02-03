**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmkj6or:07038] *** Process received signal ***
[runnervmkj6or:07038] Signal: Aborted (6)
[runnervmkj6or:07038] Signal code:  (-6)
[runnervmkj6or:07038] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e0ec45330]
[runnervmkj6or:07038] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e0ec9eb2c]
[runnervmkj6or:07038] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e0ec4527e]
[runnervmkj6or:07038] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e0ec288ff]
[runnervmkj6or:07038] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e0f0a5ff5]
[runnervmkj6or:07038] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e0f0bb0da]
[runnervmkj6or:07038] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e0f0a5a55]
[runnervmkj6or:07038] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e0f0a5a6f]
[runnervmkj6or:07038] [ 8] plumed_master(+0x146dd)[0x55ae4555c6dd]
[runnervmkj6or:07038] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e0ec2a1ca]
[runnervmkj6or:07038] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e0ec2a28b]
[runnervmkj6or:07038] [11] plumed_master(+0x15365)[0x55ae4555d365]
[runnervmkj6or:07038] *** End of error message ***
</pre>
{% endraw %}
