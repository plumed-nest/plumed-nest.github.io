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
[runnervmkj6or:04780] *** Process received signal ***
[runnervmkj6or:04780] Signal: Aborted (6)
[runnervmkj6or:04780] Signal code:  (-6)
[runnervmkj6or:04780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97e2045330]
[runnervmkj6or:04780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97e209eb2c]
[runnervmkj6or:04780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97e204527e]
[runnervmkj6or:04780] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97e20288ff]
[runnervmkj6or:04780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97e24a5ff5]
[runnervmkj6or:04780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97e24bb0da]
[runnervmkj6or:04780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97e24a5a55]
[runnervmkj6or:04780] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97e24a5a6f]
[runnervmkj6or:04780] [ 8] plumed(+0x146dd)[0x55def438a6dd]
[runnervmkj6or:04780] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97e202a1ca]
[runnervmkj6or:04780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97e202a28b]
[runnervmkj6or:04780] [11] plumed(+0x15365)[0x55def438b365]
[runnervmkj6or:04780] *** End of error message ***
</pre>
{% endraw %}
