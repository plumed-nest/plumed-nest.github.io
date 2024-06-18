**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[fv-az1771-923:08875] *** Process received signal ***
[fv-az1771-923:08875] Signal: Aborted (6)
[fv-az1771-923:08875] Signal code:  (-6)
[fv-az1771-923:08875] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3d9d842520]
[fv-az1771-923:08875] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3d9d8969fc]
[fv-az1771-923:08875] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3d9d842476]
[fv-az1771-923:08875] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3d9d8287f3]
[fv-az1771-923:08875] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3d9dca2b9e]
[fv-az1771-923:08875] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3d9dcae20c]
[fv-az1771-923:08875] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3d9dcae277]
[fv-az1771-923:08875] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3d9dcae52b]
[fv-az1771-923:08875] [ 8] plumed_master(+0x14274)[0x564726ad5274]
[fv-az1771-923:08875] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3d9d829d90]
[fv-az1771-923:08875] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3d9d829e40]
[fv-az1771-923:08875] [11] plumed_master(+0x14ed5)[0x564726ad5ed5]
[fv-az1771-923:08875] *** End of error message ***
</pre>
{% endraw %}
