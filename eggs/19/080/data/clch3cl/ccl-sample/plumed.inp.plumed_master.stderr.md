**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmgx7h7:09337] *** Process received signal ***
[runnervmgx7h7:09337] Signal: Aborted (6)
[runnervmgx7h7:09337] Signal code:  (-6)
[runnervmgx7h7:09337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f541e245330]
[runnervmgx7h7:09337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f541e29ec0c]
[runnervmgx7h7:09337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f541e24527e]
[runnervmgx7h7:09337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f541e2288ff]
[runnervmgx7h7:09337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f541e6a5ff5]
[runnervmgx7h7:09337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f541e6bb0da]
[runnervmgx7h7:09337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f541e6a5a55]
[runnervmgx7h7:09337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f541e6a5a6f]
[runnervmgx7h7:09337] [ 8] plumed_master(+0x146dd)[0x562de89706dd]
[runnervmgx7h7:09337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f541e22a1ca]
[runnervmgx7h7:09337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f541e22a28b]
[runnervmgx7h7:09337] [11] plumed_master(+0x15365)[0x562de8971365]
[runnervmgx7h7:09337] *** End of error message ***
</pre>
{% endraw %}
