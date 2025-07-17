**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmq0rgcvqdmg:09560] *** Process received signal ***
[pkrvmq0rgcvqdmg:09560] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09560] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa0ec445330]
[pkrvmq0rgcvqdmg:09560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa0ec49eb2c]
[pkrvmq0rgcvqdmg:09560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa0ec44527e]
[pkrvmq0rgcvqdmg:09560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa0ec4288ff]
[pkrvmq0rgcvqdmg:09560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa0ec8a5ff5]
[pkrvmq0rgcvqdmg:09560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa0ec8bb0da]
[pkrvmq0rgcvqdmg:09560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa0ec8a5a55]
[pkrvmq0rgcvqdmg:09560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa0ec8a5a6f]
[pkrvmq0rgcvqdmg:09560] [ 8] plumed_master(+0x146dd)[0x5581a2b216dd]
[pkrvmq0rgcvqdmg:09560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa0ec42a1ca]
[pkrvmq0rgcvqdmg:09560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa0ec42a28b]
[pkrvmq0rgcvqdmg:09560] [11] plumed_master(+0x15365)[0x5581a2b22365]
[pkrvmq0rgcvqdmg:09560] *** End of error message ***
</pre>
{% endraw %}
