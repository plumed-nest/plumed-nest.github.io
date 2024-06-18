**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1215-453:05112] *** Process received signal ***
[fv-az1215-453:05112] Signal: Aborted (6)
[fv-az1215-453:05112] Signal code:  (-6)
[fv-az1215-453:05112] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fec85e42520]
[fv-az1215-453:05112] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fec85e969fc]
[fv-az1215-453:05112] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fec85e42476]
[fv-az1215-453:05112] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fec85e287f3]
[fv-az1215-453:05112] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fec862a2b9e]
[fv-az1215-453:05112] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fec862ae20c]
[fv-az1215-453:05112] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fec862ae277]
[fv-az1215-453:05112] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fec862ae52b]
[fv-az1215-453:05112] [ 8] plumed_master(+0x14274)[0x563b2cb7f274]
[fv-az1215-453:05112] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fec85e29d90]
[fv-az1215-453:05112] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fec85e29e40]
[fv-az1215-453:05112] [11] plumed_master(+0x14ed5)[0x563b2cb7fed5]
[fv-az1215-453:05112] *** End of error message ***
</pre>
{% endraw %}
