**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az1215-453:05049] *** Process received signal ***
[fv-az1215-453:05049] Signal: Aborted (6)
[fv-az1215-453:05049] Signal code:  (-6)
[fv-az1215-453:05049] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6822042520]
[fv-az1215-453:05049] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f68220969fc]
[fv-az1215-453:05049] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6822042476]
[fv-az1215-453:05049] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f68220287f3]
[fv-az1215-453:05049] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f68224a2b9e]
[fv-az1215-453:05049] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f68224ae20c]
[fv-az1215-453:05049] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f68224ae277]
[fv-az1215-453:05049] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f68224ae52b]
[fv-az1215-453:05049] [ 8] plumed_master(+0x14274)[0x5644487b8274]
[fv-az1215-453:05049] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6822029d90]
[fv-az1215-453:05049] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6822029e40]
[fv-az1215-453:05049] [11] plumed_master(+0x14ed5)[0x5644487b8ed5]
[fv-az1215-453:05049] *** End of error message ***
</pre>
{% endraw %}
