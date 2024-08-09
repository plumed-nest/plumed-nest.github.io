**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1019-654:04976] *** Process received signal ***
[fv-az1019-654:04976] Signal: Aborted (6)
[fv-az1019-654:04976] Signal code:  (-6)
[fv-az1019-654:04976] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f72dc442520]
[fv-az1019-654:04976] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f72dc4969fc]
[fv-az1019-654:04976] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f72dc442476]
[fv-az1019-654:04976] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f72dc4287f3]
[fv-az1019-654:04976] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f72dc8a2b9e]
[fv-az1019-654:04976] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f72dc8ae20c]
[fv-az1019-654:04976] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f72dc8ae277]
[fv-az1019-654:04976] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f72dc8ae52b]
[fv-az1019-654:04976] [ 8] plumed_master(+0x14274)[0x556c6f24d274]
[fv-az1019-654:04976] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f72dc429d90]
[fv-az1019-654:04976] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f72dc429e40]
[fv-az1019-654:04976] [11] plumed_master(+0x14ed5)[0x556c6f24ded5]
[fv-az1019-654:04976] *** End of error message ***
</pre>
{% endraw %}
