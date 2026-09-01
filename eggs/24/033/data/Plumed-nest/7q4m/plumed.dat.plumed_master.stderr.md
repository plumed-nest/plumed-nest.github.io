**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmgx7h7:04864] *** Process received signal ***
[runnervmgx7h7:04864] Signal: Aborted (6)
[runnervmgx7h7:04864] Signal code:  (-6)
[runnervmgx7h7:04864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f86ec645330]
[runnervmgx7h7:04864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f86ec69ec0c]
[runnervmgx7h7:04864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f86ec64527e]
[runnervmgx7h7:04864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86ec6288ff]
[runnervmgx7h7:04864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f86ecaa5ff5]
[runnervmgx7h7:04864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f86ecabb0da]
[runnervmgx7h7:04864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f86ecaa5a55]
[runnervmgx7h7:04864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f86ecaa5a6f]
[runnervmgx7h7:04864] [ 8] plumed_master(+0x146dd)[0x55d3da7956dd]
[runnervmgx7h7:04864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f86ec62a1ca]
[runnervmgx7h7:04864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f86ec62a28b]
[runnervmgx7h7:04864] [11] plumed_master(+0x15365)[0x55d3da796365]
[runnervmgx7h7:04864] *** End of error message ***
</pre>
{% endraw %}
