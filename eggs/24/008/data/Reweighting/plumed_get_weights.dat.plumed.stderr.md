**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1215-453:04047] *** Process received signal ***
[fv-az1215-453:04047] Signal: Aborted (6)
[fv-az1215-453:04047] Signal code:  (-6)
[fv-az1215-453:04047] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f75d5c42520]
[fv-az1215-453:04047] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f75d5c969fc]
[fv-az1215-453:04047] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f75d5c42476]
[fv-az1215-453:04047] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f75d5c287f3]
[fv-az1215-453:04047] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f75d60a2b9e]
[fv-az1215-453:04047] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f75d60ae20c]
[fv-az1215-453:04047] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f75d60ae277]
[fv-az1215-453:04047] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f75d60ae52b]
[fv-az1215-453:04047] [ 8] plumed(+0x12f48)[0x55d1b3c8df48]
[fv-az1215-453:04047] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f75d5c29d90]
[fv-az1215-453:04047] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f75d5c29e40]
[fv-az1215-453:04047] [11] plumed(+0x131e5)[0x55d1b3c8e1e5]
[fv-az1215-453:04047] *** End of error message ***
</pre>
{% endraw %}
