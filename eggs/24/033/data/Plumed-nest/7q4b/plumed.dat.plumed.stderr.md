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
[runnervmi13qx:32344] *** Process received signal ***
[runnervmi13qx:32344] Signal: Aborted (6)
[runnervmi13qx:32344] Signal code:  (-6)
[runnervmi13qx:32344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f885d045330]
[runnervmi13qx:32344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f885d09eb2c]
[runnervmi13qx:32344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f885d04527e]
[runnervmi13qx:32344] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f885d0288ff]
[runnervmi13qx:32344] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f885d4a5ff5]
[runnervmi13qx:32344] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f885d4bb0da]
[runnervmi13qx:32344] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f885d4a5a55]
[runnervmi13qx:32344] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f885d4a5a6f]
[runnervmi13qx:32344] [ 8] plumed(+0x146dd)[0x55c524c256dd]
[runnervmi13qx:32344] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f885d02a1ca]
[runnervmi13qx:32344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f885d02a28b]
[runnervmi13qx:32344] [11] plumed(+0x15365)[0x55c524c26365]
[runnervmi13qx:32344] *** End of error message ***
</pre>
{% endraw %}
