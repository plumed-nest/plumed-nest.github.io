**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmkj6or:04799] *** Process received signal ***
[runnervmkj6or:04799] Signal: Aborted (6)
[runnervmkj6or:04799] Signal code:  (-6)
[runnervmkj6or:04799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8657645330]
[runnervmkj6or:04799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f865769eb2c]
[runnervmkj6or:04799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f865764527e]
[runnervmkj6or:04799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86576288ff]
[runnervmkj6or:04799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8657aa5ff5]
[runnervmkj6or:04799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8657abb0da]
[runnervmkj6or:04799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8657aa5a55]
[runnervmkj6or:04799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8657aa5a6f]
[runnervmkj6or:04799] [ 8] plumed_master(+0x146dd)[0x55b4ab64e6dd]
[runnervmkj6or:04799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f865762a1ca]
[runnervmkj6or:04799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f865762a28b]
[runnervmkj6or:04799] [11] plumed_master(+0x15365)[0x55b4ab64f365]
[runnervmkj6or:04799] *** End of error message ***
</pre>
{% endraw %}
