**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmkj6or:07022] *** Process received signal ***
[runnervmkj6or:07022] Signal: Aborted (6)
[runnervmkj6or:07022] Signal code:  (-6)
[runnervmkj6or:07022] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a92845330]
[runnervmkj6or:07022] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a9289eb2c]
[runnervmkj6or:07022] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a9284527e]
[runnervmkj6or:07022] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a928288ff]
[runnervmkj6or:07022] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a92ca5ff5]
[runnervmkj6or:07022] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a92cbb0da]
[runnervmkj6or:07022] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a92ca5a55]
[runnervmkj6or:07022] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a92ca5a6f]
[runnervmkj6or:07022] [ 8] plumed(+0x146dd)[0x558d39ec66dd]
[runnervmkj6or:07022] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a9282a1ca]
[runnervmkj6or:07022] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a9282a28b]
[runnervmkj6or:07022] [11] plumed(+0x15365)[0x558d39ec7365]
[runnervmkj6or:07022] *** End of error message ***
</pre>
{% endraw %}
