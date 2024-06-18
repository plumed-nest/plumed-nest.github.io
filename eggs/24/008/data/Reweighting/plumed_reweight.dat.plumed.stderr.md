**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1215-453:04078] *** Process received signal ***
[fv-az1215-453:04078] Signal: Aborted (6)
[fv-az1215-453:04078] Signal code:  (-6)
[fv-az1215-453:04078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7faac4442520]
[fv-az1215-453:04078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7faac44969fc]
[fv-az1215-453:04078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7faac4442476]
[fv-az1215-453:04078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7faac44287f3]
[fv-az1215-453:04078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7faac48a2b9e]
[fv-az1215-453:04078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7faac48ae20c]
[fv-az1215-453:04078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7faac48ae277]
[fv-az1215-453:04078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7faac48ae52b]
[fv-az1215-453:04078] [ 8] plumed(+0x12f48)[0x559844ac1f48]
[fv-az1215-453:04078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7faac4429d90]
[fv-az1215-453:04078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7faac4429e40]
[fv-az1215-453:04078] [11] plumed(+0x131e5)[0x559844ac21e5]
[fv-az1215-453:04078] *** End of error message ***
</pre>
{% endraw %}
