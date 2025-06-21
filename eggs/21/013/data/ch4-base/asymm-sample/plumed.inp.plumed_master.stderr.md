**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @42 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:10355] *** Process received signal ***
[pkrvmxyh4eaekms:10355] Signal: Aborted (6)
[pkrvmxyh4eaekms:10355] Signal code:  (-6)
[pkrvmxyh4eaekms:10355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1382c45330]
[pkrvmxyh4eaekms:10355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1382c9eb2c]
[pkrvmxyh4eaekms:10355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1382c4527e]
[pkrvmxyh4eaekms:10355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1382c288ff]
[pkrvmxyh4eaekms:10355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f13830a5ff5]
[pkrvmxyh4eaekms:10355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f13830bb0da]
[pkrvmxyh4eaekms:10355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f13830a5a55]
[pkrvmxyh4eaekms:10355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f13830a5a6f]
[pkrvmxyh4eaekms:10355] [ 8] plumed_master(+0x146dd)[0x555b4d98e6dd]
[pkrvmxyh4eaekms:10355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1382c2a1ca]
[pkrvmxyh4eaekms:10355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1382c2a28b]
[pkrvmxyh4eaekms:10355] [11] plumed_master(+0x15365)[0x555b4d98f365]
[pkrvmxyh4eaekms:10355] *** End of error message ***
</pre>
{% endraw %}
