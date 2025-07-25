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
[pkrvmpptgkbjq6m:08813] *** Process received signal ***
[pkrvmpptgkbjq6m:08813] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08813] Signal code:  (-6)
[pkrvmpptgkbjq6m:08813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f572cc45330]
[pkrvmpptgkbjq6m:08813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f572cc9eb2c]
[pkrvmpptgkbjq6m:08813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f572cc4527e]
[pkrvmpptgkbjq6m:08813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f572cc288ff]
[pkrvmpptgkbjq6m:08813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f572d0a5ff5]
[pkrvmpptgkbjq6m:08813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f572d0bb0da]
[pkrvmpptgkbjq6m:08813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f572d0a5a55]
[pkrvmpptgkbjq6m:08813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f572d0a5a6f]
[pkrvmpptgkbjq6m:08813] [ 8] plumed(+0x146dd)[0x558687fe86dd]
[pkrvmpptgkbjq6m:08813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f572cc2a1ca]
[pkrvmpptgkbjq6m:08813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f572cc2a28b]
[pkrvmpptgkbjq6m:08813] [11] plumed(+0x15365)[0x558687fe9365]
[pkrvmpptgkbjq6m:08813] *** End of error message ***
</pre>
{% endraw %}
