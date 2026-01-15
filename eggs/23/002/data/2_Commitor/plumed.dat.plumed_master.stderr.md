**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33813] *** Process received signal ***
[runnervmmtnos:33813] Signal: Aborted (6)
[runnervmmtnos:33813] Signal code:  (-6)
[runnervmmtnos:33813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c28045330]
[runnervmmtnos:33813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c2809eb2c]
[runnervmmtnos:33813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c2804527e]
[runnervmmtnos:33813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c280288ff]
[runnervmmtnos:33813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c284a5ff5]
[runnervmmtnos:33813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c284bb0da]
[runnervmmtnos:33813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c284a5a55]
[runnervmmtnos:33813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c284a5a6f]
[runnervmmtnos:33813] [ 8] plumed_master(+0x146dd)[0x55aade79f6dd]
[runnervmmtnos:33813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c2802a1ca]
[runnervmmtnos:33813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c2802a28b]
[runnervmmtnos:33813] [11] plumed_master(+0x15365)[0x55aade7a0365]
[runnervmmtnos:33813] *** End of error message ***
</pre>
{% endraw %}
