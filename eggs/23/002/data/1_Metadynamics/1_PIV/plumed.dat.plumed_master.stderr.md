**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmgx7h7:05614] *** Process received signal ***
[runnervmgx7h7:05614] Signal: Aborted (6)
[runnervmgx7h7:05614] Signal code:  (-6)
[runnervmgx7h7:05614] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcdc9245330]
[runnervmgx7h7:05614] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcdc929ec0c]
[runnervmgx7h7:05614] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcdc924527e]
[runnervmgx7h7:05614] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcdc92288ff]
[runnervmgx7h7:05614] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcdc96a5ff5]
[runnervmgx7h7:05614] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcdc96bb0da]
[runnervmgx7h7:05614] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcdc96a5a55]
[runnervmgx7h7:05614] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcdc96a5a6f]
[runnervmgx7h7:05614] [ 8] plumed_master(+0x146dd)[0x562078a156dd]
[runnervmgx7h7:05614] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcdc922a1ca]
[runnervmgx7h7:05614] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcdc922a28b]
[runnervmgx7h7:05614] [11] plumed_master(+0x15365)[0x562078a16365]
[runnervmgx7h7:05614] *** End of error message ***
</pre>
{% endraw %}
