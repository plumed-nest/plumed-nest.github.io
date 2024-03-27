**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1535-957:67632] *** Process received signal ***
[fv-az1535-957:67632] Signal: Aborted (6)
[fv-az1535-957:67632] Signal code:  (-6)
[fv-az1535-957:67632] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8d1ec42520]
[fv-az1535-957:67632] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8d1ec969fc]
[fv-az1535-957:67632] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8d1ec42476]
[fv-az1535-957:67632] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8d1ec287f3]
[fv-az1535-957:67632] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f8d1f0a4f26]
[fv-az1535-957:67632] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f8d1f0b6d9c]
[fv-az1535-957:67632] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f8d1f0b6e07]
[fv-az1535-957:67632] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8d1f0b70bb]
[fv-az1535-957:67632] [ 8] plumed_master(+0x12e7f)[0x55cf60ca5e7f]
[fv-az1535-957:67632] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8d1ec29d90]
[fv-az1535-957:67632] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8d1ec29e40]
[fv-az1535-957:67632] [11] plumed_master(+0x13115)[0x55cf60ca6115]
[fv-az1535-957:67632] *** End of error message ***
</pre>
{% endraw %}
