**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmgx7h7:05589] *** Process received signal ***
[runnervmgx7h7:05589] Signal: Aborted (6)
[runnervmgx7h7:05589] Signal code:  (-6)
[runnervmgx7h7:05589] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0dd3445330]
[runnervmgx7h7:05589] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0dd349ec0c]
[runnervmgx7h7:05589] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0dd344527e]
[runnervmgx7h7:05589] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0dd34288ff]
[runnervmgx7h7:05589] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0dd38a5ff5]
[runnervmgx7h7:05589] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0dd38bb0da]
[runnervmgx7h7:05589] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0dd38a5a55]
[runnervmgx7h7:05589] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0dd38a5a6f]
[runnervmgx7h7:05589] [ 8] plumed_master(+0x146dd)[0x560cecc8f6dd]
[runnervmgx7h7:05589] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0dd342a1ca]
[runnervmgx7h7:05589] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0dd342a28b]
[runnervmgx7h7:05589] [11] plumed_master(+0x15365)[0x560cecc90365]
[runnervmgx7h7:05589] *** End of error message ***
</pre>
{% endraw %}
