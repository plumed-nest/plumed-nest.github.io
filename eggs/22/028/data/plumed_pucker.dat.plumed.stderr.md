**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmkj6or:06355] *** Process received signal ***
[runnervmkj6or:06355] Signal: Aborted (6)
[runnervmkj6or:06355] Signal code:  (-6)
[runnervmkj6or:06355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5029e45330]
[runnervmkj6or:06355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5029e9eb2c]
[runnervmkj6or:06355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5029e4527e]
[runnervmkj6or:06355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5029e288ff]
[runnervmkj6or:06355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f502a2a5ff5]
[runnervmkj6or:06355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f502a2bb0da]
[runnervmkj6or:06355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f502a2a5a55]
[runnervmkj6or:06355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f502a2a5a6f]
[runnervmkj6or:06355] [ 8] plumed(+0x146dd)[0x55a72fd116dd]
[runnervmkj6or:06355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5029e2a1ca]
[runnervmkj6or:06355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5029e2a28b]
[runnervmkj6or:06355] [11] plumed(+0x15365)[0x55a72fd12365]
[runnervmkj6or:06355] *** End of error message ***
</pre>
{% endraw %}
