**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmeorf1:05004] *** Process received signal ***
[runnervmeorf1:05004] Signal: Aborted (6)
[runnervmeorf1:05004] Signal code:  (-6)
[runnervmeorf1:05004] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3583045330]
[runnervmeorf1:05004] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f358309eb2c]
[runnervmeorf1:05004] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f358304527e]
[runnervmeorf1:05004] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35830288ff]
[runnervmeorf1:05004] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35834a5ff5]
[runnervmeorf1:05004] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35834bb0da]
[runnervmeorf1:05004] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35834a5a55]
[runnervmeorf1:05004] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35834a5a6f]
[runnervmeorf1:05004] [ 8] plumed_master(+0x146dd)[0x5610922876dd]
[runnervmeorf1:05004] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f358302a1ca]
[runnervmeorf1:05004] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f358302a28b]
[runnervmeorf1:05004] [11] plumed_master(+0x15365)[0x561092288365]
[runnervmeorf1:05004] *** End of error message ***
</pre>
{% endraw %}
