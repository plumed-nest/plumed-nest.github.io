**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCES with label m1 : cannot understand the following words from the input line : LOCATION1=1, LOCATION2=9, COMPONENTS
[fv-az1215-453:08662] *** Process received signal ***
[fv-az1215-453:08662] Signal: Aborted (6)
[fv-az1215-453:08662] Signal code:  (-6)
[fv-az1215-453:08662] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fafe8042520]
[fv-az1215-453:08662] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fafe80969fc]
[fv-az1215-453:08662] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fafe8042476]
[fv-az1215-453:08662] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fafe80287f3]
[fv-az1215-453:08662] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fafe84a2b9e]
[fv-az1215-453:08662] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fafe84ae20c]
[fv-az1215-453:08662] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fafe84ae277]
[fv-az1215-453:08662] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fafe84ae52b]
[fv-az1215-453:08662] [ 8] plumed(+0x12f48)[0x5644ee484f48]
[fv-az1215-453:08662] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fafe8029d90]
[fv-az1215-453:08662] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fafe8029e40]
[fv-az1215-453:08662] [11] plumed(+0x131e5)[0x5644ee4851e5]
[fv-az1215-453:08662] *** End of error message ***
</pre>
{% endraw %}
