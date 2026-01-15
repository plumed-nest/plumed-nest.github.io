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
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmmtnos:31662] *** Process received signal ***
[runnervmmtnos:31662] Signal: Aborted (6)
[runnervmmtnos:31662] Signal code:  (-6)
[runnervmmtnos:31662] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f78c8a45330]
[runnervmmtnos:31662] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f78c8a9eb2c]
[runnervmmtnos:31662] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f78c8a4527e]
[runnervmmtnos:31662] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f78c8a288ff]
[runnervmmtnos:31662] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f78c8ea5ff5]
[runnervmmtnos:31662] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f78c8ebb0da]
[runnervmmtnos:31662] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f78c8ea5a55]
[runnervmmtnos:31662] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f78c8ea5a6f]
[runnervmmtnos:31662] [ 8] plumed_master(+0x146dd)[0x560e5ac0c6dd]
[runnervmmtnos:31662] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f78c8a2a1ca]
[runnervmmtnos:31662] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f78c8a2a28b]
[runnervmmtnos:31662] [11] plumed_master(+0x15365)[0x560e5ac0d365]
[runnervmmtnos:31662] *** End of error message ***
</pre>
{% endraw %}
