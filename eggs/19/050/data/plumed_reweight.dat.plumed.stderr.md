**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE_FROM_CONTOUR with label cont : keyword DATA is compulsory for this action
[fv-az1215-453:08352] *** Process received signal ***
[fv-az1215-453:08352] Signal: Aborted (6)
[fv-az1215-453:08352] Signal code:  (-6)
[fv-az1215-453:08352] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd6d7242520]
[fv-az1215-453:08352] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd6d72969fc]
[fv-az1215-453:08352] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd6d7242476]
[fv-az1215-453:08352] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd6d72287f3]
[fv-az1215-453:08352] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd6d76a2b9e]
[fv-az1215-453:08352] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd6d76ae20c]
[fv-az1215-453:08352] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd6d76ae277]
[fv-az1215-453:08352] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd6d76ae52b]
[fv-az1215-453:08352] [ 8] plumed(+0x12f48)[0x5587f94faf48]
[fv-az1215-453:08352] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd6d7229d90]
[fv-az1215-453:08352] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd6d7229e40]
[fv-az1215-453:08352] [11] plumed(+0x131e5)[0x5587f94fb1e5]
[fv-az1215-453:08352] *** End of error message ***
</pre>
{% endraw %}
