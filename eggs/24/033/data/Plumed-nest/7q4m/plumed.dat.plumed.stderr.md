**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmgx7h7:04847] *** Process received signal ***
[runnervmgx7h7:04847] Signal: Aborted (6)
[runnervmgx7h7:04847] Signal code:  (-6)
[runnervmgx7h7:04847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f697fc45330]
[runnervmgx7h7:04847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f697fc9ec0c]
[runnervmgx7h7:04847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f697fc4527e]
[runnervmgx7h7:04847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f697fc288ff]
[runnervmgx7h7:04847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69800a5ff5]
[runnervmgx7h7:04847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69800bb0da]
[runnervmgx7h7:04847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69800a5a55]
[runnervmgx7h7:04847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69800a5a6f]
[runnervmgx7h7:04847] [ 8] plumed(+0x146dd)[0x555ad545c6dd]
[runnervmgx7h7:04847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f697fc2a1ca]
[runnervmgx7h7:04847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f697fc2a28b]
[runnervmgx7h7:04847] [11] plumed(+0x15365)[0x555ad545d365]
[runnervmgx7h7:04847] *** End of error message ***
</pre>
{% endraw %}
