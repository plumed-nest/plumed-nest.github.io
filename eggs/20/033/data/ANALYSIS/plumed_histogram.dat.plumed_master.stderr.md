**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:10482] *** Process received signal ***
[pkrvmxyh4eaekms:10482] Signal: Aborted (6)
[pkrvmxyh4eaekms:10482] Signal code:  (-6)
[pkrvmxyh4eaekms:10482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1cc3445330]
[pkrvmxyh4eaekms:10482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1cc349eb2c]
[pkrvmxyh4eaekms:10482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1cc344527e]
[pkrvmxyh4eaekms:10482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1cc34288ff]
[pkrvmxyh4eaekms:10482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1cc38a5ff5]
[pkrvmxyh4eaekms:10482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1cc38bb0da]
[pkrvmxyh4eaekms:10482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1cc38a5a55]
[pkrvmxyh4eaekms:10482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1cc38a5a6f]
[pkrvmxyh4eaekms:10482] [ 8] plumed_master(+0x146dd)[0x55799f2736dd]
[pkrvmxyh4eaekms:10482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1cc342a1ca]
[pkrvmxyh4eaekms:10482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1cc342a28b]
[pkrvmxyh4eaekms:10482] [11] plumed_master(+0x15365)[0x55799f274365]
[pkrvmxyh4eaekms:10482] *** End of error message ***
</pre>
{% endraw %}
