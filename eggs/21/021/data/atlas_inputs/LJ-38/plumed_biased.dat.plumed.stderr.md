**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label n4 : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az1153-362:69884] *** Process received signal ***
[fv-az1153-362:69884] Signal: Aborted (6)
[fv-az1153-362:69884] Signal code:  (-6)
[fv-az1153-362:69884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f05fc242520]
[fv-az1153-362:69884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f05fc2969fc]
[fv-az1153-362:69884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f05fc242476]
[fv-az1153-362:69884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f05fc2287f3]
[fv-az1153-362:69884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f05fc6a4f26]
[fv-az1153-362:69884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f05fc6b6d9c]
[fv-az1153-362:69884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f05fc6b6e07]
[fv-az1153-362:69884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f05fc6b70bb]
[fv-az1153-362:69884] [ 8] plumed(+0x12f48)[0x556ef2d47f48]
[fv-az1153-362:69884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f05fc229d90]
[fv-az1153-362:69884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f05fc229e40]
[fv-az1153-362:69884] [11] plumed(+0x131e5)[0x556ef2d481e5]
[fv-az1153-362:69884] *** End of error message ***
</pre>
{% endraw %}
