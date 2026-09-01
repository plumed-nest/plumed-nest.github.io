**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmgx7h7:04719] *** Process received signal ***
[runnervmgx7h7:04719] Signal: Aborted (6)
[runnervmgx7h7:04719] Signal code:  (-6)
[runnervmgx7h7:04719] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd61445330]
[runnervmgx7h7:04719] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd6149ec0c]
[runnervmgx7h7:04719] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd6144527e]
[runnervmgx7h7:04719] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd614288ff]
[runnervmgx7h7:04719] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd618a5ff5]
[runnervmgx7h7:04719] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd618bb0da]
[runnervmgx7h7:04719] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd618a5a55]
[runnervmgx7h7:04719] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd618a5a6f]
[runnervmgx7h7:04719] [ 8] plumed_master(+0x146dd)[0x556db72536dd]
[runnervmgx7h7:04719] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd6142a1ca]
[runnervmgx7h7:04719] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd6142a28b]
[runnervmgx7h7:04719] [11] plumed_master(+0x15365)[0x556db7254365]
[runnervmgx7h7:04719] *** End of error message ***
</pre>
{% endraw %}
