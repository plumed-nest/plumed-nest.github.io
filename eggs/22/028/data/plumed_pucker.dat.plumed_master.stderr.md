**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1215-453:05368] *** Process received signal ***
[fv-az1215-453:05368] Signal: Aborted (6)
[fv-az1215-453:05368] Signal code:  (-6)
[fv-az1215-453:05368] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8b82442520]
[fv-az1215-453:05368] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8b824969fc]
[fv-az1215-453:05368] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8b82442476]
[fv-az1215-453:05368] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8b824287f3]
[fv-az1215-453:05368] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8b828a2b9e]
[fv-az1215-453:05368] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8b828ae20c]
[fv-az1215-453:05368] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8b828ae277]
[fv-az1215-453:05368] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8b828ae52b]
[fv-az1215-453:05368] [ 8] plumed_master(+0x14274)[0x55ca7a374274]
[fv-az1215-453:05368] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8b82429d90]
[fv-az1215-453:05368] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8b82429e40]
[fv-az1215-453:05368] [11] plumed_master(+0x14ed5)[0x55ca7a374ed5]
[fv-az1215-453:05368] *** End of error message ***
</pre>
{% endraw %}
