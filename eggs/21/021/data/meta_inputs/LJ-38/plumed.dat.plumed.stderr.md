**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  meta_inputs/LJ-38/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az1215-453:06678] *** Process received signal ***
[fv-az1215-453:06678] Signal: Aborted (6)
[fv-az1215-453:06678] Signal code:  (-6)
[fv-az1215-453:06678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3c03242520]
[fv-az1215-453:06678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3c032969fc]
[fv-az1215-453:06678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3c03242476]
[fv-az1215-453:06678] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3c032287f3]
[fv-az1215-453:06678] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3c036a2b9e]
[fv-az1215-453:06678] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3c036ae20c]
[fv-az1215-453:06678] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3c036ae277]
[fv-az1215-453:06678] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3c036ae52b]
[fv-az1215-453:06678] [ 8] plumed(+0x12f48)[0x560be7382f48]
[fv-az1215-453:06678] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3c03229d90]
[fv-az1215-453:06678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3c03229e40]
[fv-az1215-453:06678] [11] plumed(+0x131e5)[0x560be73831e5]
[fv-az1215-453:06678] *** End of error message ***
</pre>
{% endraw %}
