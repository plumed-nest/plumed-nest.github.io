**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmkj6or:06069] *** Process received signal ***
[runnervmkj6or:06069] Signal: Aborted (6)
[runnervmkj6or:06069] Signal code:  (-6)
[runnervmkj6or:06069] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa1f045330]
[runnervmkj6or:06069] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa1f09eb2c]
[runnervmkj6or:06069] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa1f04527e]
[runnervmkj6or:06069] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa1f0288ff]
[runnervmkj6or:06069] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa1f4a5ff5]
[runnervmkj6or:06069] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa1f4bb0da]
[runnervmkj6or:06069] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa1f4a5a55]
[runnervmkj6or:06069] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa1f4a5a6f]
[runnervmkj6or:06069] [ 8] plumed_master(+0x146dd)[0x5560d97876dd]
[runnervmkj6or:06069] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa1f02a1ca]
[runnervmkj6or:06069] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa1f02a28b]
[runnervmkj6or:06069] [11] plumed_master(+0x15365)[0x5560d9788365]
[runnervmkj6or:06069] *** End of error message ***
</pre>
{% endraw %}
