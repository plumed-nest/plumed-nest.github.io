**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az585-767:09292] *** Process received signal ***
[fv-az585-767:09292] Signal: Aborted (6)
[fv-az585-767:09292] Signal code:  (-6)
[fv-az585-767:09292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6151642520]
[fv-az585-767:09292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f61516969fc]
[fv-az585-767:09292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6151642476]
[fv-az585-767:09292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f61516287f3]
[fv-az585-767:09292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6151aa2b9e]
[fv-az585-767:09292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6151aae20c]
[fv-az585-767:09292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6151aae277]
[fv-az585-767:09292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6151aae52b]
[fv-az585-767:09292] [ 8] plumed_master(+0x14254)[0x55c1a51b2254]
[fv-az585-767:09292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6151629d90]
[fv-az585-767:09292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6151629e40]
[fv-az585-767:09292] [11] plumed_master(+0x14eb5)[0x55c1a51b2eb5]
[fv-az585-767:09292] *** End of error message ***
</pre>
{% endraw %}