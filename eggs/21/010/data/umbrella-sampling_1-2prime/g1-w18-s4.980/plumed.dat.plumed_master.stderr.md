**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
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
[fv-az1433-905:70433] *** Process received signal ***
[fv-az1433-905:70433] Signal: Aborted (6)
[fv-az1433-905:70433] Signal code:  (-6)
[fv-az1433-905:70433] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd378842520]
[fv-az1433-905:70433] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd3788969fc]
[fv-az1433-905:70433] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd378842476]
[fv-az1433-905:70433] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd3788287f3]
[fv-az1433-905:70433] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd378ca4f26]
[fv-az1433-905:70433] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd378cb6d9c]
[fv-az1433-905:70433] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd378cb6e07]
[fv-az1433-905:70433] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd378cb70bb]
[fv-az1433-905:70433] [ 8] plumed_master(+0x12e7f)[0x557524e3ee7f]
[fv-az1433-905:70433] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd378829d90]
[fv-az1433-905:70433] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd378829e40]
[fv-az1433-905:70433] [11] plumed_master(+0x13115)[0x557524e3f115]
[fv-az1433-905:70433] *** End of error message ***
</pre>
{% endraw %}
