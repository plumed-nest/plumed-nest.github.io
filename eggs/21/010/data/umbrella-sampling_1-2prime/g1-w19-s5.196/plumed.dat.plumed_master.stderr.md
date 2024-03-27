**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w19-s5.196/plumed.dat   
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
[fv-az1433-905:70465] *** Process received signal ***
[fv-az1433-905:70465] Signal: Aborted (6)
[fv-az1433-905:70465] Signal code:  (-6)
[fv-az1433-905:70465] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f335e042520]
[fv-az1433-905:70465] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f335e0969fc]
[fv-az1433-905:70465] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f335e042476]
[fv-az1433-905:70465] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f335e0287f3]
[fv-az1433-905:70465] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f335e4a4f26]
[fv-az1433-905:70465] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f335e4b6d9c]
[fv-az1433-905:70465] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f335e4b6e07]
[fv-az1433-905:70465] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f335e4b70bb]
[fv-az1433-905:70465] [ 8] plumed_master(+0x12e7f)[0x564939ee1e7f]
[fv-az1433-905:70465] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f335e029d90]
[fv-az1433-905:70465] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f335e029e40]
[fv-az1433-905:70465] [11] plumed_master(+0x13115)[0x564939ee2115]
[fv-az1433-905:70465] *** End of error message ***
</pre>
{% endraw %}
