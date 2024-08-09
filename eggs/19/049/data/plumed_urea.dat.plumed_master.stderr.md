**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1019-654:08725] *** Process received signal ***
[fv-az1019-654:08725] Signal: Aborted (6)
[fv-az1019-654:08725] Signal code:  (-6)
[fv-az1019-654:08725] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7feeee842520]
[fv-az1019-654:08725] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7feeee8969fc]
[fv-az1019-654:08725] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7feeee842476]
[fv-az1019-654:08725] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7feeee8287f3]
[fv-az1019-654:08725] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7feeeeca2b9e]
[fv-az1019-654:08725] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7feeeecae20c]
[fv-az1019-654:08725] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7feeeecae277]
[fv-az1019-654:08725] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7feeeecae52b]
[fv-az1019-654:08725] [ 8] plumed_master(+0x14274)[0x55977b97d274]
[fv-az1019-654:08725] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7feeee829d90]
[fv-az1019-654:08725] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7feeee829e40]
[fv-az1019-654:08725] [11] plumed_master(+0x14ed5)[0x55977b97ded5]
[fv-az1019-654:08725] *** End of error message ***
</pre>
{% endraw %}
