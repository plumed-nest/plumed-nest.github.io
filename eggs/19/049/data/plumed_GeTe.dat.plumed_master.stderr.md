**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1215-453:08606] *** Process received signal ***
[fv-az1215-453:08606] Signal: Aborted (6)
[fv-az1215-453:08606] Signal code:  (-6)
[fv-az1215-453:08606] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb1fdc42520]
[fv-az1215-453:08606] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb1fdc969fc]
[fv-az1215-453:08606] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb1fdc42476]
[fv-az1215-453:08606] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb1fdc287f3]
[fv-az1215-453:08606] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb1fe0a2b9e]
[fv-az1215-453:08606] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb1fe0ae20c]
[fv-az1215-453:08606] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb1fe0ae277]
[fv-az1215-453:08606] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb1fe0ae52b]
[fv-az1215-453:08606] [ 8] plumed_master(+0x14274)[0x55e4d0404274]
[fv-az1215-453:08606] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb1fdc29d90]
[fv-az1215-453:08606] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb1fdc29e40]
[fv-az1215-453:08606] [11] plumed_master(+0x14ed5)[0x55e4d0404ed5]
[fv-az1215-453:08606] *** End of error message ***
</pre>
{% endraw %}
