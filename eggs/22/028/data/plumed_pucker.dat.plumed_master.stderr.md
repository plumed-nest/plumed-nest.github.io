**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmxyh4eaekms:08632] *** Process received signal ***
[pkrvmxyh4eaekms:08632] Signal: Aborted (6)
[pkrvmxyh4eaekms:08632] Signal code:  (-6)
[pkrvmxyh4eaekms:08632] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34b6045330]
[pkrvmxyh4eaekms:08632] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34b609eb2c]
[pkrvmxyh4eaekms:08632] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34b604527e]
[pkrvmxyh4eaekms:08632] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34b60288ff]
[pkrvmxyh4eaekms:08632] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34b64a5ff5]
[pkrvmxyh4eaekms:08632] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34b64bb0da]
[pkrvmxyh4eaekms:08632] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34b64a5a55]
[pkrvmxyh4eaekms:08632] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34b64a5a6f]
[pkrvmxyh4eaekms:08632] [ 8] plumed_master(+0x146dd)[0x55ba967f56dd]
[pkrvmxyh4eaekms:08632] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34b602a1ca]
[pkrvmxyh4eaekms:08632] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34b602a28b]
[pkrvmxyh4eaekms:08632] [11] plumed_master(+0x15365)[0x55ba967f6365]
[pkrvmxyh4eaekms:08632] *** End of error message ***
</pre>
{% endraw %}
