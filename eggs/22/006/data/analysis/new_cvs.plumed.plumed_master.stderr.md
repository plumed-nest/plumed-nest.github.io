**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @89 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:07521] *** Process received signal ***
[pkrvmxyh4eaekms:07521] Signal: Aborted (6)
[pkrvmxyh4eaekms:07521] Signal code:  (-6)
[pkrvmxyh4eaekms:07521] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f263c045330]
[pkrvmxyh4eaekms:07521] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f263c09eb2c]
[pkrvmxyh4eaekms:07521] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f263c04527e]
[pkrvmxyh4eaekms:07521] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f263c0288ff]
[pkrvmxyh4eaekms:07521] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f263c4a5ff5]
[pkrvmxyh4eaekms:07521] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f263c4bb0da]
[pkrvmxyh4eaekms:07521] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f263c4a5a55]
[pkrvmxyh4eaekms:07521] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f263c4a5a6f]
[pkrvmxyh4eaekms:07521] [ 8] plumed_master(+0x146dd)[0x5567d468c6dd]
[pkrvmxyh4eaekms:07521] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f263c02a1ca]
[pkrvmxyh4eaekms:07521] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f263c02a28b]
[pkrvmxyh4eaekms:07521] [11] plumed_master(+0x15365)[0x5567d468d365]
[pkrvmxyh4eaekms:07521] *** End of error message ***
</pre>
{% endraw %}
