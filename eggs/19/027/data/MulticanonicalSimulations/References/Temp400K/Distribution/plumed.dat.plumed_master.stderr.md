**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp400K/Distribution/plumed.dat   
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
[pkrvmxyh4eaekms:12295] *** Process received signal ***
[pkrvmxyh4eaekms:12295] Signal: Aborted (6)
[pkrvmxyh4eaekms:12295] Signal code:  (-6)
[pkrvmxyh4eaekms:12295] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf5aa45330]
[pkrvmxyh4eaekms:12295] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf5aa9eb2c]
[pkrvmxyh4eaekms:12295] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf5aa4527e]
[pkrvmxyh4eaekms:12295] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf5aa288ff]
[pkrvmxyh4eaekms:12295] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf5aea5ff5]
[pkrvmxyh4eaekms:12295] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf5aebb0da]
[pkrvmxyh4eaekms:12295] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf5aea5a55]
[pkrvmxyh4eaekms:12295] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf5aea5a6f]
[pkrvmxyh4eaekms:12295] [ 8] plumed_master(+0x146dd)[0x55a60914d6dd]
[pkrvmxyh4eaekms:12295] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf5aa2a1ca]
[pkrvmxyh4eaekms:12295] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf5aa2a28b]
[pkrvmxyh4eaekms:12295] [11] plumed_master(+0x15365)[0x55a60914e365]
[pkrvmxyh4eaekms:12295] *** End of error message ***
</pre>
{% endraw %}
