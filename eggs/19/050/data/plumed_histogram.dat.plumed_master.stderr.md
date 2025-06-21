**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:11531] *** Process received signal ***
[pkrvmxyh4eaekms:11531] Signal: Aborted (6)
[pkrvmxyh4eaekms:11531] Signal code:  (-6)
[pkrvmxyh4eaekms:11531] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe490a45330]
[pkrvmxyh4eaekms:11531] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe490a9eb2c]
[pkrvmxyh4eaekms:11531] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe490a4527e]
[pkrvmxyh4eaekms:11531] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe490a288ff]
[pkrvmxyh4eaekms:11531] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe490ea5ff5]
[pkrvmxyh4eaekms:11531] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe490ebb0da]
[pkrvmxyh4eaekms:11531] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe490ea5a55]
[pkrvmxyh4eaekms:11531] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe490ea5a6f]
[pkrvmxyh4eaekms:11531] [ 8] plumed_master(+0x146dd)[0x55f8e3b5c6dd]
[pkrvmxyh4eaekms:11531] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe490a2a1ca]
[pkrvmxyh4eaekms:11531] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe490a2a28b]
[pkrvmxyh4eaekms:11531] [11] plumed_master(+0x15365)[0x55f8e3b5d365]
[pkrvmxyh4eaekms:11531] *** End of error message ***
</pre>
{% endraw %}
