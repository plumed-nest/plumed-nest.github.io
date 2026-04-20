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
[runnervmeorf1:05181] *** Process received signal ***
[runnervmeorf1:05181] Signal: Aborted (6)
[runnervmeorf1:05181] Signal code:  (-6)
[runnervmeorf1:05181] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb429a45330]
[runnervmeorf1:05181] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb429a9eb2c]
[runnervmeorf1:05181] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb429a4527e]
[runnervmeorf1:05181] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb429a288ff]
[runnervmeorf1:05181] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb429ea5ff5]
[runnervmeorf1:05181] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb429ebb0da]
[runnervmeorf1:05181] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb429ea5a55]
[runnervmeorf1:05181] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb429ea5a6f]
[runnervmeorf1:05181] [ 8] plumed_master(+0x146dd)[0x558debda56dd]
[runnervmeorf1:05181] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb429a2a1ca]
[runnervmeorf1:05181] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb429a2a28b]
[runnervmeorf1:05181] [11] plumed_master(+0x15365)[0x558debda6365]
[runnervmeorf1:05181] *** End of error message ***
</pre>
{% endraw %}
