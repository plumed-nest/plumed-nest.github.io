**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @167 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62698] *** Process received signal ***
[pkrvmbietmlfzoi:62698] Signal: Aborted (6)
[pkrvmbietmlfzoi:62698] Signal code:  (-6)
[pkrvmbietmlfzoi:62698] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b54c45330]
[pkrvmbietmlfzoi:62698] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b54c9eb2c]
[pkrvmbietmlfzoi:62698] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b54c4527e]
[pkrvmbietmlfzoi:62698] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b54c288ff]
[pkrvmbietmlfzoi:62698] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b550a5ff5]
[pkrvmbietmlfzoi:62698] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b550bb0da]
[pkrvmbietmlfzoi:62698] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b550a5a55]
[pkrvmbietmlfzoi:62698] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b550a5a6f]
[pkrvmbietmlfzoi:62698] [ 8] plumed_master(+0x146dd)[0x5608532a66dd]
[pkrvmbietmlfzoi:62698] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b54c2a1ca]
[pkrvmbietmlfzoi:62698] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b54c2a28b]
[pkrvmbietmlfzoi:62698] [11] plumed_master(+0x15365)[0x5608532a7365]
[pkrvmbietmlfzoi:62698] *** End of error message ***
</pre>
{% endraw %}
