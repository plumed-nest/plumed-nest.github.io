**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp450K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[fv-az585-767:10054] *** Process received signal ***
[fv-az585-767:10054] Signal: Aborted (6)
[fv-az585-767:10054] Signal code:  (-6)
[fv-az585-767:10054] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2b20e42520]
[fv-az585-767:10054] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2b20e969fc]
[fv-az585-767:10054] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2b20e42476]
[fv-az585-767:10054] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2b20e287f3]
[fv-az585-767:10054] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2b212a2b9e]
[fv-az585-767:10054] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2b212ae20c]
[fv-az585-767:10054] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2b212ae277]
[fv-az585-767:10054] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2b212ae52b]
[fv-az585-767:10054] [ 8] plumed_master(+0x14254)[0x5562fe7f9254]
[fv-az585-767:10054] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2b20e29d90]
[fv-az585-767:10054] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2b20e29e40]
[fv-az585-767:10054] [11] plumed_master(+0x14eb5)[0x5562fe7f9eb5]
[fv-az585-767:10054] *** End of error message ***
</pre>
{% endraw %}
