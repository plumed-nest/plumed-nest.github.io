**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az1433-905:70612] *** Process received signal ***
[fv-az1433-905:70612] Signal: Aborted (6)
[fv-az1433-905:70612] Signal code:  (-6)
[fv-az1433-905:70612] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0232a42520]
[fv-az1433-905:70612] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0232a969fc]
[fv-az1433-905:70612] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0232a42476]
[fv-az1433-905:70612] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0232a287f3]
[fv-az1433-905:70612] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f0232ea4f26]
[fv-az1433-905:70612] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f0232eb6d9c]
[fv-az1433-905:70612] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f0232eb6e07]
[fv-az1433-905:70612] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0232eb70bb]
[fv-az1433-905:70612] [ 8] plumed(+0x12f48)[0x5646d5d23f48]
[fv-az1433-905:70612] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0232a29d90]
[fv-az1433-905:70612] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0232a29e40]
[fv-az1433-905:70612] [11] plumed(+0x131e5)[0x5646d5d241e5]
[fv-az1433-905:70612] *** End of error message ***
</pre>
{% endraw %}
