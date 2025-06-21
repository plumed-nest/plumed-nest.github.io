**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:11147] *** Process received signal ***
[pkrvmxyh4eaekms:11147] Signal: Aborted (6)
[pkrvmxyh4eaekms:11147] Signal code:  (-6)
[pkrvmxyh4eaekms:11147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5408045330]
[pkrvmxyh4eaekms:11147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f540809eb2c]
[pkrvmxyh4eaekms:11147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f540804527e]
[pkrvmxyh4eaekms:11147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f54080288ff]
[pkrvmxyh4eaekms:11147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54084a5ff5]
[pkrvmxyh4eaekms:11147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54084bb0da]
[pkrvmxyh4eaekms:11147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54084a5a55]
[pkrvmxyh4eaekms:11147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54084a5a6f]
[pkrvmxyh4eaekms:11147] [ 8] plumed_master(+0x146dd)[0x55726a8806dd]
[pkrvmxyh4eaekms:11147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f540802a1ca]
[pkrvmxyh4eaekms:11147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f540802a28b]
[pkrvmxyh4eaekms:11147] [11] plumed_master(+0x15365)[0x55726a881365]
[pkrvmxyh4eaekms:11147] *** End of error message ***
</pre>
{% endraw %}
