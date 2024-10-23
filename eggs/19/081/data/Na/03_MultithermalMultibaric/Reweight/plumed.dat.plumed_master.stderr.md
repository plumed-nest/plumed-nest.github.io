**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az1215-275:10256] *** Process received signal ***
[fv-az1215-275:10256] Signal: Aborted (6)
[fv-az1215-275:10256] Signal code:  (-6)
[fv-az1215-275:10256] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb9e9442520]
[fv-az1215-275:10256] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb9e94969fc]
[fv-az1215-275:10256] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb9e9442476]
[fv-az1215-275:10256] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb9e94287f3]
[fv-az1215-275:10256] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb9e98a2b9e]
[fv-az1215-275:10256] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb9e98ae20c]
[fv-az1215-275:10256] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb9e98ae277]
[fv-az1215-275:10256] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb9e98ae52b]
[fv-az1215-275:10256] [ 8] plumed_master(+0x14254)[0x563f87a3d254]
[fv-az1215-275:10256] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb9e9429d90]
[fv-az1215-275:10256] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb9e9429e40]
[fv-az1215-275:10256] [11] plumed_master(+0x14eb5)[0x563f87a3deb5]
[fv-az1215-275:10256] *** End of error message ***
</pre>
{% endraw %}
