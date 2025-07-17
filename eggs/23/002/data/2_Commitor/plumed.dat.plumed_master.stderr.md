**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmq0rgcvqdmg:08763] *** Process received signal ***
[pkrvmq0rgcvqdmg:08763] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08763] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40ba645330]
[pkrvmq0rgcvqdmg:08763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40ba69eb2c]
[pkrvmq0rgcvqdmg:08763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40ba64527e]
[pkrvmq0rgcvqdmg:08763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40ba6288ff]
[pkrvmq0rgcvqdmg:08763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40baaa5ff5]
[pkrvmq0rgcvqdmg:08763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40baabb0da]
[pkrvmq0rgcvqdmg:08763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40baaa5a55]
[pkrvmq0rgcvqdmg:08763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40baaa5a6f]
[pkrvmq0rgcvqdmg:08763] [ 8] plumed_master(+0x146dd)[0x56341bb3a6dd]
[pkrvmq0rgcvqdmg:08763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40ba62a1ca]
[pkrvmq0rgcvqdmg:08763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40ba62a28b]
[pkrvmq0rgcvqdmg:08763] [11] plumed_master(+0x15365)[0x56341bb3b365]
[pkrvmq0rgcvqdmg:08763] *** End of error message ***
</pre>
{% endraw %}
