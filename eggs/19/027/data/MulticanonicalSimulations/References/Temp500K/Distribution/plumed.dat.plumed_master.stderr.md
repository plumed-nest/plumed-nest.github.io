**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp500K/Distribution/plumed.dat   
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
[fv-az585-767:10113] *** Process received signal ***
[fv-az585-767:10113] Signal: Aborted (6)
[fv-az585-767:10113] Signal code:  (-6)
[fv-az585-767:10113] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb166242520]
[fv-az585-767:10113] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb1662969fc]
[fv-az585-767:10113] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb166242476]
[fv-az585-767:10113] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb1662287f3]
[fv-az585-767:10113] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb1666a2b9e]
[fv-az585-767:10113] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb1666ae20c]
[fv-az585-767:10113] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb1666ae277]
[fv-az585-767:10113] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb1666ae52b]
[fv-az585-767:10113] [ 8] plumed_master(+0x14254)[0x56503deec254]
[fv-az585-767:10113] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb166229d90]
[fv-az585-767:10113] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb166229e40]
[fv-az585-767:10113] [11] plumed_master(+0x14eb5)[0x56503deeceb5]
[fv-az585-767:10113] *** End of error message ***
</pre>
{% endraw %}
