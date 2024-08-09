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
[fv-az1019-654:05139] *** Process received signal ***
[fv-az1019-654:05139] Signal: Aborted (6)
[fv-az1019-654:05139] Signal code:  (-6)
[fv-az1019-654:05139] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd93ea42520]
[fv-az1019-654:05139] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd93ea969fc]
[fv-az1019-654:05139] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd93ea42476]
[fv-az1019-654:05139] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd93ea287f3]
[fv-az1019-654:05139] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd93eea2b9e]
[fv-az1019-654:05139] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd93eeae20c]
[fv-az1019-654:05139] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd93eeae277]
[fv-az1019-654:05139] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd93eeae52b]
[fv-az1019-654:05139] [ 8] plumed_master(+0x14274)[0x55c963c3b274]
[fv-az1019-654:05139] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd93ea29d90]
[fv-az1019-654:05139] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd93ea29e40]
[fv-az1019-654:05139] [11] plumed_master(+0x14ed5)[0x55c963c3bed5]
[fv-az1019-654:05139] *** End of error message ***
</pre>
{% endraw %}
