**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:06039] *** Process received signal ***
[pkrvmxyh4eaekms:06039] Signal: Aborted (6)
[pkrvmxyh4eaekms:06039] Signal code:  (-6)
[pkrvmxyh4eaekms:06039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7d3045330]
[pkrvmxyh4eaekms:06039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7d309eb2c]
[pkrvmxyh4eaekms:06039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7d304527e]
[pkrvmxyh4eaekms:06039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7d30288ff]
[pkrvmxyh4eaekms:06039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7d34a5ff5]
[pkrvmxyh4eaekms:06039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7d34bb0da]
[pkrvmxyh4eaekms:06039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7d34a5a55]
[pkrvmxyh4eaekms:06039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7d34a5a6f]
[pkrvmxyh4eaekms:06039] [ 8] plumed_master(+0x146dd)[0x561acbfff6dd]
[pkrvmxyh4eaekms:06039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7d302a1ca]
[pkrvmxyh4eaekms:06039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7d302a28b]
[pkrvmxyh4eaekms:06039] [11] plumed_master(+0x15365)[0x561acc000365]
[pkrvmxyh4eaekms:06039] *** End of error message ***
</pre>
{% endraw %}
