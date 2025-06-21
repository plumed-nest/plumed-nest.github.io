**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @43 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:09723] *** Process received signal ***
[pkrvmxyh4eaekms:09723] Signal: Aborted (6)
[pkrvmxyh4eaekms:09723] Signal code:  (-6)
[pkrvmxyh4eaekms:09723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7bda445330]
[pkrvmxyh4eaekms:09723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7bda49eb2c]
[pkrvmxyh4eaekms:09723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7bda44527e]
[pkrvmxyh4eaekms:09723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7bda4288ff]
[pkrvmxyh4eaekms:09723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7bda8a5ff5]
[pkrvmxyh4eaekms:09723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7bda8bb0da]
[pkrvmxyh4eaekms:09723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7bda8a5a55]
[pkrvmxyh4eaekms:09723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7bda8a5a6f]
[pkrvmxyh4eaekms:09723] [ 8] plumed_master(+0x146dd)[0x562128c0e6dd]
[pkrvmxyh4eaekms:09723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7bda42a1ca]
[pkrvmxyh4eaekms:09723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7bda42a28b]
[pkrvmxyh4eaekms:09723] [11] plumed_master(+0x15365)[0x562128c0f365]
[pkrvmxyh4eaekms:09723] *** End of error message ***
</pre>
{% endraw %}
