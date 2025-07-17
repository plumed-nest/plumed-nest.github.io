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
[pkrvmq0rgcvqdmg:13738] *** Process received signal ***
[pkrvmq0rgcvqdmg:13738] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:13738] Signal code:  (-6)
[pkrvmq0rgcvqdmg:13738] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd779045330]
[pkrvmq0rgcvqdmg:13738] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd77909eb2c]
[pkrvmq0rgcvqdmg:13738] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd77904527e]
[pkrvmq0rgcvqdmg:13738] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7790288ff]
[pkrvmq0rgcvqdmg:13738] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7794a5ff5]
[pkrvmq0rgcvqdmg:13738] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7794bb0da]
[pkrvmq0rgcvqdmg:13738] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7794a5a55]
[pkrvmq0rgcvqdmg:13738] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7794a5a6f]
[pkrvmq0rgcvqdmg:13738] [ 8] plumed_master(+0x146dd)[0x556fd6aba6dd]
[pkrvmq0rgcvqdmg:13738] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd77902a1ca]
[pkrvmq0rgcvqdmg:13738] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd77902a28b]
[pkrvmq0rgcvqdmg:13738] [11] plumed_master(+0x15365)[0x556fd6abb365]
[pkrvmq0rgcvqdmg:13738] *** End of error message ***
</pre>
{% endraw %}
