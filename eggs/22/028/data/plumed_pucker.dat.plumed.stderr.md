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
[pkrvmxyh4eaekms:08615] *** Process received signal ***
[pkrvmxyh4eaekms:08615] Signal: Aborted (6)
[pkrvmxyh4eaekms:08615] Signal code:  (-6)
[pkrvmxyh4eaekms:08615] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca91e45330]
[pkrvmxyh4eaekms:08615] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca91e9eb2c]
[pkrvmxyh4eaekms:08615] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca91e4527e]
[pkrvmxyh4eaekms:08615] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca91e288ff]
[pkrvmxyh4eaekms:08615] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca922a5ff5]
[pkrvmxyh4eaekms:08615] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca922bb0da]
[pkrvmxyh4eaekms:08615] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca922a5a55]
[pkrvmxyh4eaekms:08615] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca922a5a6f]
[pkrvmxyh4eaekms:08615] [ 8] plumed(+0x146dd)[0x56120e27f6dd]
[pkrvmxyh4eaekms:08615] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca91e2a1ca]
[pkrvmxyh4eaekms:08615] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca91e2a28b]
[pkrvmxyh4eaekms:08615] [11] plumed(+0x15365)[0x56120e280365]
[pkrvmxyh4eaekms:08615] *** End of error message ***
</pre>
{% endraw %}
