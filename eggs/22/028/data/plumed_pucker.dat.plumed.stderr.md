**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1019-654:05356] *** Process received signal ***
[fv-az1019-654:05356] Signal: Aborted (6)
[fv-az1019-654:05356] Signal code:  (-6)
[fv-az1019-654:05356] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe5a1e42520]
[fv-az1019-654:05356] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe5a1e969fc]
[fv-az1019-654:05356] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe5a1e42476]
[fv-az1019-654:05356] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe5a1e287f3]
[fv-az1019-654:05356] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe5a22a2b9e]
[fv-az1019-654:05356] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe5a22ae20c]
[fv-az1019-654:05356] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe5a22ae277]
[fv-az1019-654:05356] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe5a22ae52b]
[fv-az1019-654:05356] [ 8] plumed(+0x12f48)[0x55d65f346f48]
[fv-az1019-654:05356] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe5a1e29d90]
[fv-az1019-654:05356] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe5a1e29e40]
[fv-az1019-654:05356] [11] plumed(+0x131e5)[0x55d65f3471e5]
[fv-az1019-654:05356] *** End of error message ***
</pre>
{% endraw %}
