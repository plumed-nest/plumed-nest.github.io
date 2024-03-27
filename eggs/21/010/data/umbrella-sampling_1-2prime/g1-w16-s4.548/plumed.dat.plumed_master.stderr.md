**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az1433-905:70371] *** Process received signal ***
[fv-az1433-905:70371] Signal: Aborted (6)
[fv-az1433-905:70371] Signal code:  (-6)
[fv-az1433-905:70371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd3d2242520]
[fv-az1433-905:70371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd3d22969fc]
[fv-az1433-905:70371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd3d2242476]
[fv-az1433-905:70371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd3d22287f3]
[fv-az1433-905:70371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd3d26a4f26]
[fv-az1433-905:70371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd3d26b6d9c]
[fv-az1433-905:70371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd3d26b6e07]
[fv-az1433-905:70371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd3d26b70bb]
[fv-az1433-905:70371] [ 8] plumed_master(+0x12e7f)[0x5615190e4e7f]
[fv-az1433-905:70371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd3d2229d90]
[fv-az1433-905:70371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd3d2229e40]
[fv-az1433-905:70371] [11] plumed_master(+0x13115)[0x5615190e5115]
[fv-az1433-905:70371] *** End of error message ***
</pre>
{% endraw %}
