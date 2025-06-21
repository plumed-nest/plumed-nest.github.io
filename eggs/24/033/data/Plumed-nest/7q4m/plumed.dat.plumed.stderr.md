**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmxyh4eaekms:05896] *** Process received signal ***
[pkrvmxyh4eaekms:05896] Signal: Aborted (6)
[pkrvmxyh4eaekms:05896] Signal code:  (-6)
[pkrvmxyh4eaekms:05896] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc871045330]
[pkrvmxyh4eaekms:05896] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc87109eb2c]
[pkrvmxyh4eaekms:05896] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc87104527e]
[pkrvmxyh4eaekms:05896] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8710288ff]
[pkrvmxyh4eaekms:05896] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8714a5ff5]
[pkrvmxyh4eaekms:05896] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8714bb0da]
[pkrvmxyh4eaekms:05896] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8714a5a55]
[pkrvmxyh4eaekms:05896] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8714a5a6f]
[pkrvmxyh4eaekms:05896] [ 8] plumed(+0x146dd)[0x55a7d839a6dd]
[pkrvmxyh4eaekms:05896] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc87102a1ca]
[pkrvmxyh4eaekms:05896] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc87102a28b]
[pkrvmxyh4eaekms:05896] [11] plumed(+0x15365)[0x55a7d839b365]
[pkrvmxyh4eaekms:05896] *** End of error message ***
</pre>
{% endraw %}
