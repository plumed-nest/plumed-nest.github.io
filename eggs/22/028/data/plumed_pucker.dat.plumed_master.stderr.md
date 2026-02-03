**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmkj6or:06371] *** Process received signal ***
[runnervmkj6or:06371] Signal: Aborted (6)
[runnervmkj6or:06371] Signal code:  (-6)
[runnervmkj6or:06371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe322845330]
[runnervmkj6or:06371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe32289eb2c]
[runnervmkj6or:06371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe32284527e]
[runnervmkj6or:06371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3228288ff]
[runnervmkj6or:06371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe322ca5ff5]
[runnervmkj6or:06371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe322cbb0da]
[runnervmkj6or:06371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe322ca5a55]
[runnervmkj6or:06371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe322ca5a6f]
[runnervmkj6or:06371] [ 8] plumed_master(+0x146dd)[0x564de70696dd]
[runnervmkj6or:06371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe32282a1ca]
[runnervmkj6or:06371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe32282a28b]
[runnervmkj6or:06371] [11] plumed_master(+0x15365)[0x564de706a365]
[runnervmkj6or:06371] *** End of error message ***
</pre>
{% endraw %}
