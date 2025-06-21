**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmxyh4eaekms:10858] *** Process received signal ***
[pkrvmxyh4eaekms:10858] Signal: Aborted (6)
[pkrvmxyh4eaekms:10858] Signal code:  (-6)
[pkrvmxyh4eaekms:10858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff094845330]
[pkrvmxyh4eaekms:10858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff09489eb2c]
[pkrvmxyh4eaekms:10858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff09484527e]
[pkrvmxyh4eaekms:10858] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff0948288ff]
[pkrvmxyh4eaekms:10858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff094ca5ff5]
[pkrvmxyh4eaekms:10858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff094cbb0da]
[pkrvmxyh4eaekms:10858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff094ca5a55]
[pkrvmxyh4eaekms:10858] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff094ca5a6f]
[pkrvmxyh4eaekms:10858] [ 8] plumed(+0x146dd)[0x564d2151c6dd]
[pkrvmxyh4eaekms:10858] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff09482a1ca]
[pkrvmxyh4eaekms:10858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff09482a28b]
[pkrvmxyh4eaekms:10858] [11] plumed(+0x15365)[0x564d2151d365]
[pkrvmxyh4eaekms:10858] *** End of error message ***
</pre>
{% endraw %}
