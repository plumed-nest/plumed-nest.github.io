**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmgx7h7:09334] *** Process received signal ***
[runnervmgx7h7:09334] Signal: Aborted (6)
[runnervmgx7h7:09334] Signal code:  (-6)
[runnervmgx7h7:09334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b34645330]
[runnervmgx7h7:09334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b3469ec0c]
[runnervmgx7h7:09334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b3464527e]
[runnervmgx7h7:09334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b346288ff]
[runnervmgx7h7:09334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b34aa5ff5]
[runnervmgx7h7:09334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b34abb0da]
[runnervmgx7h7:09334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b34aa5a55]
[runnervmgx7h7:09334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b34aa5a6f]
[runnervmgx7h7:09334] [ 8] plumed_master(+0x146dd)[0x564aa69826dd]
[runnervmgx7h7:09334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b3462a1ca]
[runnervmgx7h7:09334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b3462a28b]
[runnervmgx7h7:09334] [11] plumed_master(+0x15365)[0x564aa6983365]
[runnervmgx7h7:09334] *** End of error message ***
</pre>
{% endraw %}
