**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmgx7h7:05879] *** Process received signal ***
[runnervmgx7h7:05879] Signal: Aborted (6)
[runnervmgx7h7:05879] Signal code:  (-6)
[runnervmgx7h7:05879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5e49a45330]
[runnervmgx7h7:05879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5e49a9ec0c]
[runnervmgx7h7:05879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5e49a4527e]
[runnervmgx7h7:05879] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5e49a288ff]
[runnervmgx7h7:05879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5e49ea5ff5]
[runnervmgx7h7:05879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5e49ebb0da]
[runnervmgx7h7:05879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5e49ea5a55]
[runnervmgx7h7:05879] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5e49ea5a6f]
[runnervmgx7h7:05879] [ 8] plumed_master(+0x146dd)[0x55707c96a6dd]
[runnervmgx7h7:05879] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5e49a2a1ca]
[runnervmgx7h7:05879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5e49a2a28b]
[runnervmgx7h7:05879] [11] plumed_master(+0x15365)[0x55707c96b365]
[runnervmgx7h7:05879] *** End of error message ***
</pre>
{% endraw %}
