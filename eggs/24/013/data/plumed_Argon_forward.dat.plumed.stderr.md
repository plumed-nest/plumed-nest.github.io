**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmkj6or:06108] *** Process received signal ***
[runnervmkj6or:06108] Signal: Aborted (6)
[runnervmkj6or:06108] Signal code:  (-6)
[runnervmkj6or:06108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9550645330]
[runnervmkj6or:06108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f955069eb2c]
[runnervmkj6or:06108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f955064527e]
[runnervmkj6or:06108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95506288ff]
[runnervmkj6or:06108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9550aa5ff5]
[runnervmkj6or:06108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9550abb0da]
[runnervmkj6or:06108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9550aa5a55]
[runnervmkj6or:06108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9550aa5a6f]
[runnervmkj6or:06108] [ 8] plumed(+0x146dd)[0x55be5c6476dd]
[runnervmkj6or:06108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f955062a1ca]
[runnervmkj6or:06108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f955062a28b]
[runnervmkj6or:06108] [11] plumed(+0x15365)[0x55be5c648365]
[runnervmkj6or:06108] *** End of error message ***
</pre>
{% endraw %}
