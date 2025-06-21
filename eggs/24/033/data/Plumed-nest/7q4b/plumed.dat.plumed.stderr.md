**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmxyh4eaekms:05741] *** Process received signal ***
[pkrvmxyh4eaekms:05741] Signal: Aborted (6)
[pkrvmxyh4eaekms:05741] Signal code:  (-6)
[pkrvmxyh4eaekms:05741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c19e45330]
[pkrvmxyh4eaekms:05741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c19e9eb2c]
[pkrvmxyh4eaekms:05741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c19e4527e]
[pkrvmxyh4eaekms:05741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c19e288ff]
[pkrvmxyh4eaekms:05741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c1a2a5ff5]
[pkrvmxyh4eaekms:05741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c1a2bb0da]
[pkrvmxyh4eaekms:05741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c1a2a5a55]
[pkrvmxyh4eaekms:05741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c1a2a5a6f]
[pkrvmxyh4eaekms:05741] [ 8] plumed(+0x146dd)[0x559702f026dd]
[pkrvmxyh4eaekms:05741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c19e2a1ca]
[pkrvmxyh4eaekms:05741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c19e2a28b]
[pkrvmxyh4eaekms:05741] [11] plumed(+0x15365)[0x559702f03365]
[pkrvmxyh4eaekms:05741] *** End of error message ***
</pre>
{% endraw %}
