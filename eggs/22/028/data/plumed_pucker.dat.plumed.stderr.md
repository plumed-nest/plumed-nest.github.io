**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1215-453:05360] *** Process received signal ***
[fv-az1215-453:05360] Signal: Aborted (6)
[fv-az1215-453:05360] Signal code:  (-6)
[fv-az1215-453:05360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0bba442520]
[fv-az1215-453:05360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0bba4969fc]
[fv-az1215-453:05360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0bba442476]
[fv-az1215-453:05360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0bba4287f3]
[fv-az1215-453:05360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0bba8a2b9e]
[fv-az1215-453:05360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0bba8ae20c]
[fv-az1215-453:05360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0bba8ae277]
[fv-az1215-453:05360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0bba8ae52b]
[fv-az1215-453:05360] [ 8] plumed(+0x12f48)[0x55e24f82df48]
[fv-az1215-453:05360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0bba429d90]
[fv-az1215-453:05360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0bba429e40]
[fv-az1215-453:05360] [11] plumed(+0x131e5)[0x55e24f82e1e5]
[fv-az1215-453:05360] *** End of error message ***
</pre>
{% endraw %}
