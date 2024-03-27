**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w12-s3.684/plumed.dat   
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
[fv-az1433-905:70237] *** Process received signal ***
[fv-az1433-905:70237] Signal: Aborted (6)
[fv-az1433-905:70237] Signal code:  (-6)
[fv-az1433-905:70237] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f21ada42520]
[fv-az1433-905:70237] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f21ada969fc]
[fv-az1433-905:70237] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f21ada42476]
[fv-az1433-905:70237] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f21ada287f3]
[fv-az1433-905:70237] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f21adea4f26]
[fv-az1433-905:70237] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f21adeb6d9c]
[fv-az1433-905:70237] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f21adeb6e07]
[fv-az1433-905:70237] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f21adeb70bb]
[fv-az1433-905:70237] [ 8] plumed(+0x12f48)[0x558a3ebaaf48]
[fv-az1433-905:70237] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f21ada29d90]
[fv-az1433-905:70237] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f21ada29e40]
[fv-az1433-905:70237] [11] plumed(+0x131e5)[0x558a3ebab1e5]
[fv-az1433-905:70237] *** End of error message ***
</pre>
{% endraw %}
