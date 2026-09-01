**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmgx7h7:05908] *** Process received signal ***
[runnervmgx7h7:05908] Signal: Aborted (6)
[runnervmgx7h7:05908] Signal code:  (-6)
[runnervmgx7h7:05908] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b10245330]
[runnervmgx7h7:05908] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b1029ec0c]
[runnervmgx7h7:05908] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b1024527e]
[runnervmgx7h7:05908] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b102288ff]
[runnervmgx7h7:05908] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b106a5ff5]
[runnervmgx7h7:05908] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b106bb0da]
[runnervmgx7h7:05908] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b106a5a55]
[runnervmgx7h7:05908] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b106a5a6f]
[runnervmgx7h7:05908] [ 8] plumed(+0x146dd)[0x56240749c6dd]
[runnervmgx7h7:05908] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b1022a1ca]
[runnervmgx7h7:05908] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b1022a28b]
[runnervmgx7h7:05908] [11] plumed(+0x15365)[0x56240749d365]
[runnervmgx7h7:05908] *** End of error message ***
</pre>
{% endraw %}
