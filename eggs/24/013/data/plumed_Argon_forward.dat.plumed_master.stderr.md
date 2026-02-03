**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmkj6or:06124] *** Process received signal ***
[runnervmkj6or:06124] Signal: Aborted (6)
[runnervmkj6or:06124] Signal code:  (-6)
[runnervmkj6or:06124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f036c045330]
[runnervmkj6or:06124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f036c09eb2c]
[runnervmkj6or:06124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f036c04527e]
[runnervmkj6or:06124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f036c0288ff]
[runnervmkj6or:06124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f036c4a5ff5]
[runnervmkj6or:06124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f036c4bb0da]
[runnervmkj6or:06124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f036c4a5a55]
[runnervmkj6or:06124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f036c4a5a6f]
[runnervmkj6or:06124] [ 8] plumed_master(+0x146dd)[0x564592a616dd]
[runnervmkj6or:06124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f036c02a1ca]
[runnervmkj6or:06124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f036c02a28b]
[runnervmkj6or:06124] [11] plumed_master(+0x15365)[0x564592a62365]
[runnervmkj6or:06124] *** End of error message ***
</pre>
{% endraw %}
