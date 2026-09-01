**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervmgx7h7:06217] *** Process received signal ***
[runnervmgx7h7:06217] Signal: Aborted (6)
[runnervmgx7h7:06217] Signal code:  (-6)
[runnervmgx7h7:06217] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d1d045330]
[runnervmgx7h7:06217] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d1d09ec0c]
[runnervmgx7h7:06217] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d1d04527e]
[runnervmgx7h7:06217] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d1d0288ff]
[runnervmgx7h7:06217] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d1d4a5ff5]
[runnervmgx7h7:06217] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d1d4bb0da]
[runnervmgx7h7:06217] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d1d4a5a55]
[runnervmgx7h7:06217] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d1d4a5a6f]
[runnervmgx7h7:06217] [ 8] plumed_master(+0x146dd)[0x55e3835276dd]
[runnervmgx7h7:06217] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d1d02a1ca]
[runnervmgx7h7:06217] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d1d02a28b]
[runnervmgx7h7:06217] [11] plumed_master(+0x15365)[0x55e383528365]
[runnervmgx7h7:06217] *** End of error message ***
</pre>
{% endraw %}
