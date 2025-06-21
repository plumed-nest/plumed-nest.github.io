**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:09619] *** Process received signal ***
[pkrvmxyh4eaekms:09619] Signal: Aborted (6)
[pkrvmxyh4eaekms:09619] Signal code:  (-6)
[pkrvmxyh4eaekms:09619] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe27845330]
[pkrvmxyh4eaekms:09619] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe2789eb2c]
[pkrvmxyh4eaekms:09619] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe2784527e]
[pkrvmxyh4eaekms:09619] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe278288ff]
[pkrvmxyh4eaekms:09619] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe27ca5ff5]
[pkrvmxyh4eaekms:09619] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe27cbb0da]
[pkrvmxyh4eaekms:09619] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe27ca5a55]
[pkrvmxyh4eaekms:09619] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe27ca5a6f]
[pkrvmxyh4eaekms:09619] [ 8] plumed_master(+0x146dd)[0x558e8f0386dd]
[pkrvmxyh4eaekms:09619] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe2782a1ca]
[pkrvmxyh4eaekms:09619] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe2782a28b]
[pkrvmxyh4eaekms:09619] [11] plumed_master(+0x15365)[0x558e8f039365]
[pkrvmxyh4eaekms:09619] *** End of error message ***
</pre>
{% endraw %}
