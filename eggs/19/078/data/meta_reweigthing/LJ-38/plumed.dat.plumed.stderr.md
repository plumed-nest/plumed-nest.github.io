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
[fv-az1272-851:10518] *** Process received signal ***
[fv-az1272-851:10518] Signal: Aborted (6)
[fv-az1272-851:10518] Signal code:  (-6)
[fv-az1272-851:10518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f30fe842520]
[fv-az1272-851:10518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f30fe8969fc]
[fv-az1272-851:10518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f30fe842476]
[fv-az1272-851:10518] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f30fe8287f3]
[fv-az1272-851:10518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f30feca2b9e]
[fv-az1272-851:10518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f30fecae20c]
[fv-az1272-851:10518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f30fecae277]
[fv-az1272-851:10518] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f30fecae52b]
[fv-az1272-851:10518] [ 8] plumed(+0x12f48)[0x558871cb1f48]
[fv-az1272-851:10518] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f30fe829d90]
[fv-az1272-851:10518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f30fe829e40]
[fv-az1272-851:10518] [11] plumed(+0x131e5)[0x558871cb21e5]
[fv-az1272-851:10518] *** End of error message ***
</pre>
{% endraw %}
