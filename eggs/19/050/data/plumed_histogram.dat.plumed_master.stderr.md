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
[pkrvmq0rgcvqdmg:12860] *** Process received signal ***
[pkrvmq0rgcvqdmg:12860] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12860] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12860] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4d11045330]
[pkrvmq0rgcvqdmg:12860] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4d1109eb2c]
[pkrvmq0rgcvqdmg:12860] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4d1104527e]
[pkrvmq0rgcvqdmg:12860] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4d110288ff]
[pkrvmq0rgcvqdmg:12860] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4d114a5ff5]
[pkrvmq0rgcvqdmg:12860] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4d114bb0da]
[pkrvmq0rgcvqdmg:12860] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4d114a5a55]
[pkrvmq0rgcvqdmg:12860] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4d114a5a6f]
[pkrvmq0rgcvqdmg:12860] [ 8] plumed_master(+0x146dd)[0x5625e4e5c6dd]
[pkrvmq0rgcvqdmg:12860] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4d1102a1ca]
[pkrvmq0rgcvqdmg:12860] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4d1102a28b]
[pkrvmq0rgcvqdmg:12860] [11] plumed_master(+0x15365)[0x5625e4e5d365]
[pkrvmq0rgcvqdmg:12860] *** End of error message ***
</pre>
{% endraw %}
