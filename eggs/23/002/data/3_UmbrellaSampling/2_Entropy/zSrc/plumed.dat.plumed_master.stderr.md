**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1429-284:05148] *** Process received signal ***
[fv-az1429-284:05148] Signal: Aborted (6)
[fv-az1429-284:05148] Signal code:  (-6)
[fv-az1429-284:05148] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7293a42520]
[fv-az1429-284:05148] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7293a969fc]
[fv-az1429-284:05148] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7293a42476]
[fv-az1429-284:05148] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7293a287f3]
[fv-az1429-284:05148] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7293ea2b9e]
[fv-az1429-284:05148] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7293eae20c]
[fv-az1429-284:05148] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7293eae277]
[fv-az1429-284:05148] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7293eae52b]
[fv-az1429-284:05148] [ 8] plumed_master(+0x14254)[0x563bfec51254]
[fv-az1429-284:05148] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7293a29d90]
[fv-az1429-284:05148] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7293a29e40]
[fv-az1429-284:05148] [11] plumed_master(+0x14eb5)[0x563bfec51eb5]
[fv-az1429-284:05148] *** End of error message ***
</pre>
{% endraw %}
