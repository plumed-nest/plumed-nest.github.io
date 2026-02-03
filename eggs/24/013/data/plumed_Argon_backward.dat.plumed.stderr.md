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
[runnervmkj6or:06052] *** Process received signal ***
[runnervmkj6or:06052] Signal: Aborted (6)
[runnervmkj6or:06052] Signal code:  (-6)
[runnervmkj6or:06052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f81e7c45330]
[runnervmkj6or:06052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f81e7c9eb2c]
[runnervmkj6or:06052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f81e7c4527e]
[runnervmkj6or:06052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81e7c288ff]
[runnervmkj6or:06052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81e80a5ff5]
[runnervmkj6or:06052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81e80bb0da]
[runnervmkj6or:06052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81e80a5a55]
[runnervmkj6or:06052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81e80a5a6f]
[runnervmkj6or:06052] [ 8] plumed(+0x146dd)[0x560c826e86dd]
[runnervmkj6or:06052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f81e7c2a1ca]
[runnervmkj6or:06052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f81e7c2a28b]
[runnervmkj6or:06052] [11] plumed(+0x15365)[0x560c826e9365]
[runnervmkj6or:06052] *** End of error message ***
</pre>
{% endraw %}
