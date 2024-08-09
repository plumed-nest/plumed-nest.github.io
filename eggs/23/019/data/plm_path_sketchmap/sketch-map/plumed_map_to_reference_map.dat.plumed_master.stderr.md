**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_map_to_reference_map.dat   
Download: [zipped raw stdout](plumed_map_to_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_map_to_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:668) std::string PLMD::Keywords::getOutputComponentDescription(const string&) const
could not find output component named coord
[fv-az1490-855:04626] *** Process received signal ***
[fv-az1490-855:04626] Signal: Aborted (6)
[fv-az1490-855:04626] Signal code:  (-6)
[fv-az1490-855:04626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc791a42520]
[fv-az1490-855:04626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc791a969fc]
[fv-az1490-855:04626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc791a42476]
[fv-az1490-855:04626] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc791a287f3]
[fv-az1490-855:04626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc791ea2b9e]
[fv-az1490-855:04626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc791eae20c]
[fv-az1490-855:04626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc791eae277]
[fv-az1490-855:04626] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc791eae52b]
[fv-az1490-855:04626] [ 8] plumed_master(+0x14274)[0x555b0a00b274]
[fv-az1490-855:04626] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc791a29d90]
[fv-az1490-855:04626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc791a29e40]
[fv-az1490-855:04626] [11] plumed_master(+0x14ed5)[0x555b0a00bed5]
[fv-az1490-855:04626] *** End of error message ***
</pre>
{% endraw %}
