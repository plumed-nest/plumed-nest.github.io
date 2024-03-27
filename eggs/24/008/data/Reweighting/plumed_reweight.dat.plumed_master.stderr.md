**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1535-957:67663] *** Process received signal ***
[fv-az1535-957:67663] Signal: Aborted (6)
[fv-az1535-957:67663] Signal code:  (-6)
[fv-az1535-957:67663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f26e5042520]
[fv-az1535-957:67663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f26e50969fc]
[fv-az1535-957:67663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f26e5042476]
[fv-az1535-957:67663] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f26e50287f3]
[fv-az1535-957:67663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f26e54a4f26]
[fv-az1535-957:67663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f26e54b6d9c]
[fv-az1535-957:67663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f26e54b6e07]
[fv-az1535-957:67663] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f26e54b70bb]
[fv-az1535-957:67663] [ 8] plumed_master(+0x12e7f)[0x560c85ab7e7f]
[fv-az1535-957:67663] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f26e5029d90]
[fv-az1535-957:67663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f26e5029e40]
[fv-az1535-957:67663] [11] plumed_master(+0x13115)[0x560c85ab8115]
[fv-az1535-957:67663] *** End of error message ***
</pre>
{% endraw %}
