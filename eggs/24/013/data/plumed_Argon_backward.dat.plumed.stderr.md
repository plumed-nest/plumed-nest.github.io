**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmeorf1:05194] *** Process received signal ***
[runnervmeorf1:05194] Signal: Aborted (6)
[runnervmeorf1:05194] Signal code:  (-6)
[runnervmeorf1:05194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9b6c45330]
[runnervmeorf1:05194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9b6c9eb2c]
[runnervmeorf1:05194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9b6c4527e]
[runnervmeorf1:05194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9b6c288ff]
[runnervmeorf1:05194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9b70a5ff5]
[runnervmeorf1:05194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9b70bb0da]
[runnervmeorf1:05194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9b70a5a55]
[runnervmeorf1:05194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9b70a5a6f]
[runnervmeorf1:05194] [ 8] plumed(+0x146dd)[0x562171eaf6dd]
[runnervmeorf1:05194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9b6c2a1ca]
[runnervmeorf1:05194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9b6c2a28b]
[runnervmeorf1:05194] [11] plumed(+0x15365)[0x562171eb0365]
[runnervmeorf1:05194] *** End of error message ***
</pre>
{% endraw %}
