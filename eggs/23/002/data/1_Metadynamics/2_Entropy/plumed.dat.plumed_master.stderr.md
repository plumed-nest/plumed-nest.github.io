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
[fv-az1215-453:04985] *** Process received signal ***
[fv-az1215-453:04985] Signal: Aborted (6)
[fv-az1215-453:04985] Signal code:  (-6)
[fv-az1215-453:04985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8df7842520]
[fv-az1215-453:04985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8df78969fc]
[fv-az1215-453:04985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8df7842476]
[fv-az1215-453:04985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8df78287f3]
[fv-az1215-453:04985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8df7ca2b9e]
[fv-az1215-453:04985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8df7cae20c]
[fv-az1215-453:04985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8df7cae277]
[fv-az1215-453:04985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8df7cae52b]
[fv-az1215-453:04985] [ 8] plumed_master(+0x14274)[0x557a5a4e0274]
[fv-az1215-453:04985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8df7829d90]
[fv-az1215-453:04985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8df7829e40]
[fv-az1215-453:04985] [11] plumed_master(+0x14ed5)[0x557a5a4e0ed5]
[fv-az1215-453:04985] *** End of error message ***
</pre>
{% endraw %}
