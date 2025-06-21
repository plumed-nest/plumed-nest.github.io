**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp550K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @27 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:12487] *** Process received signal ***
[pkrvmxyh4eaekms:12487] Signal: Aborted (6)
[pkrvmxyh4eaekms:12487] Signal code:  (-6)
[pkrvmxyh4eaekms:12487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f83a45330]
[pkrvmxyh4eaekms:12487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f83a9eb2c]
[pkrvmxyh4eaekms:12487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f83a4527e]
[pkrvmxyh4eaekms:12487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f83a288ff]
[pkrvmxyh4eaekms:12487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f83ea5ff5]
[pkrvmxyh4eaekms:12487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f83ebb0da]
[pkrvmxyh4eaekms:12487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f83ea5a55]
[pkrvmxyh4eaekms:12487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f83ea5a6f]
[pkrvmxyh4eaekms:12487] [ 8] plumed_master(+0x146dd)[0x557e1a3b86dd]
[pkrvmxyh4eaekms:12487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f83a2a1ca]
[pkrvmxyh4eaekms:12487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f83a2a28b]
[pkrvmxyh4eaekms:12487] [11] plumed_master(+0x15365)[0x557e1a3b9365]
[pkrvmxyh4eaekms:12487] *** End of error message ***
</pre>
{% endraw %}
