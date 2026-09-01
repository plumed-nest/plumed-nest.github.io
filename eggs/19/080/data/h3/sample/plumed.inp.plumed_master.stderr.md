**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmgx7h7:09638] *** Process received signal ***
[runnervmgx7h7:09638] Signal: Aborted (6)
[runnervmgx7h7:09638] Signal code:  (-6)
[runnervmgx7h7:09638] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f856ae45330]
[runnervmgx7h7:09638] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f856ae9ec0c]
[runnervmgx7h7:09638] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f856ae4527e]
[runnervmgx7h7:09638] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f856ae288ff]
[runnervmgx7h7:09638] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f856b2a5ff5]
[runnervmgx7h7:09638] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f856b2bb0da]
[runnervmgx7h7:09638] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f856b2a5a55]
[runnervmgx7h7:09638] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f856b2a5a6f]
[runnervmgx7h7:09638] [ 8] plumed_master(+0x146dd)[0x55e7f8c756dd]
[runnervmgx7h7:09638] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f856ae2a1ca]
[runnervmgx7h7:09638] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f856ae2a28b]
[runnervmgx7h7:09638] [11] plumed_master(+0x15365)[0x55e7f8c76365]
[runnervmgx7h7:09638] *** End of error message ***
</pre>
{% endraw %}
