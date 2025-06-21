**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w1.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:05754] *** Process received signal ***
[pkrvmxyh4eaekms:05754] Signal: Aborted (6)
[pkrvmxyh4eaekms:05754] Signal code:  (-6)
[pkrvmxyh4eaekms:05754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde3be45330]
[pkrvmxyh4eaekms:05754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde3be9eb2c]
[pkrvmxyh4eaekms:05754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde3be4527e]
[pkrvmxyh4eaekms:05754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde3be288ff]
[pkrvmxyh4eaekms:05754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde3c2a5ff5]
[pkrvmxyh4eaekms:05754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde3c2bb0da]
[pkrvmxyh4eaekms:05754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde3c2a5a55]
[pkrvmxyh4eaekms:05754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde3c2a5a6f]
[pkrvmxyh4eaekms:05754] [ 8] plumed_master(+0x146dd)[0x55ca21a236dd]
[pkrvmxyh4eaekms:05754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde3be2a1ca]
[pkrvmxyh4eaekms:05754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde3be2a28b]
[pkrvmxyh4eaekms:05754] [11] plumed_master(+0x15365)[0x55ca21a24365]
[pkrvmxyh4eaekms:05754] *** End of error message ***
</pre>
{% endraw %}
