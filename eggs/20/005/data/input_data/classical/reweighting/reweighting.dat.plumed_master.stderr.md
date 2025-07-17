**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:11163] *** Process received signal ***
[pkrvmq0rgcvqdmg:11163] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11163] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11163] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe137645330]
[pkrvmq0rgcvqdmg:11163] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe13769eb2c]
[pkrvmq0rgcvqdmg:11163] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe13764527e]
[pkrvmq0rgcvqdmg:11163] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1376288ff]
[pkrvmq0rgcvqdmg:11163] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe137aa5ff5]
[pkrvmq0rgcvqdmg:11163] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe137abb0da]
[pkrvmq0rgcvqdmg:11163] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe137aa5a55]
[pkrvmq0rgcvqdmg:11163] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe137aa5a6f]
[pkrvmq0rgcvqdmg:11163] [ 8] plumed_master(+0x146dd)[0x55e07287f6dd]
[pkrvmq0rgcvqdmg:11163] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe13762a1ca]
[pkrvmq0rgcvqdmg:11163] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe13762a28b]
[pkrvmq0rgcvqdmg:11163] [11] plumed_master(+0x15365)[0x55e072880365]
[pkrvmq0rgcvqdmg:11163] *** End of error message ***
</pre>
{% endraw %}
