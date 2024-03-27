**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az1487-606:73879] *** Process received signal ***
[fv-az1487-606:73879] Signal: Aborted (6)
[fv-az1487-606:73879] Signal code:  (-6)
[fv-az1487-606:73879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3b3fc42520]
[fv-az1487-606:73879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3b3fc969fc]
[fv-az1487-606:73879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3b3fc42476]
[fv-az1487-606:73879] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3b3fc287f3]
[fv-az1487-606:73879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f3b400a4f26]
[fv-az1487-606:73879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f3b400b6d9c]
[fv-az1487-606:73879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f3b400b6e07]
[fv-az1487-606:73879] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3b400b70bb]
[fv-az1487-606:73879] [ 8] plumed(+0x12f48)[0x558633853f48]
[fv-az1487-606:73879] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3b3fc29d90]
[fv-az1487-606:73879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3b3fc29e40]
[fv-az1487-606:73879] [11] plumed(+0x131e5)[0x5586338541e5]
[fv-az1487-606:73879] *** End of error message ***
</pre>
{% endraw %}
