**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmgx7h7:05820] *** Process received signal ***
[runnervmgx7h7:05820] Signal: Aborted (6)
[runnervmgx7h7:05820] Signal code:  (-6)
[runnervmgx7h7:05820] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f922bc45330]
[runnervmgx7h7:05820] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f922bc9ec0c]
[runnervmgx7h7:05820] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f922bc4527e]
[runnervmgx7h7:05820] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f922bc288ff]
[runnervmgx7h7:05820] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f922c0a5ff5]
[runnervmgx7h7:05820] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f922c0bb0da]
[runnervmgx7h7:05820] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f922c0a5a55]
[runnervmgx7h7:05820] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f922c0a5a6f]
[runnervmgx7h7:05820] [ 8] plumed_master(+0x146dd)[0x557fbd7fd6dd]
[runnervmgx7h7:05820] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f922bc2a1ca]
[runnervmgx7h7:05820] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f922bc2a28b]
[runnervmgx7h7:05820] [11] plumed_master(+0x15365)[0x557fbd7fe365]
[runnervmgx7h7:05820] *** End of error message ***
</pre>
{% endraw %}
