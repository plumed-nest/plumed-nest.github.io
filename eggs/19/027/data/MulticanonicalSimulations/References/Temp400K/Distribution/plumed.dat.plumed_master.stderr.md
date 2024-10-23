**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp400K/Distribution/plumed.dat   
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
[fv-az585-767:09992] *** Process received signal ***
[fv-az585-767:09992] Signal: Aborted (6)
[fv-az585-767:09992] Signal code:  (-6)
[fv-az585-767:09992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff679442520]
[fv-az585-767:09992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff6794969fc]
[fv-az585-767:09992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff679442476]
[fv-az585-767:09992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff6794287f3]
[fv-az585-767:09992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff6798a2b9e]
[fv-az585-767:09992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff6798ae20c]
[fv-az585-767:09992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff6798ae277]
[fv-az585-767:09992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff6798ae52b]
[fv-az585-767:09992] [ 8] plumed_master(+0x14254)[0x555903ee8254]
[fv-az585-767:09992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff679429d90]
[fv-az585-767:09992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff679429e40]
[fv-az585-767:09992] [11] plumed_master(+0x14eb5)[0x555903ee8eb5]
[fv-az585-767:09992] *** End of error message ***
</pre>
{% endraw %}
