**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
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
[fv-az1433-905:70150] *** Process received signal ***
[fv-az1433-905:70150] Signal: Aborted (6)
[fv-az1433-905:70150] Signal code:  (-6)
[fv-az1433-905:70150] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8fcec42520]
[fv-az1433-905:70150] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8fcec969fc]
[fv-az1433-905:70150] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8fcec42476]
[fv-az1433-905:70150] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8fcec287f3]
[fv-az1433-905:70150] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f8fcf0a4f26]
[fv-az1433-905:70150] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f8fcf0b6d9c]
[fv-az1433-905:70150] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f8fcf0b6e07]
[fv-az1433-905:70150] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8fcf0b70bb]
[fv-az1433-905:70150] [ 8] plumed_master(+0x12e7f)[0x562d96acce7f]
[fv-az1433-905:70150] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8fcec29d90]
[fv-az1433-905:70150] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8fcec29e40]
[fv-az1433-905:70150] [11] plumed_master(+0x13115)[0x562d96acd115]
[fv-az1433-905:70150] *** End of error message ***
</pre>
{% endraw %}
