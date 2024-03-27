**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
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
[fv-az1433-905:70740] *** Process received signal ***
[fv-az1433-905:70740] Signal: Aborted (6)
[fv-az1433-905:70740] Signal code:  (-6)
[fv-az1433-905:70740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0fe0842520]
[fv-az1433-905:70740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0fe08969fc]
[fv-az1433-905:70740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0fe0842476]
[fv-az1433-905:70740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0fe08287f3]
[fv-az1433-905:70740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f0fe0ca4f26]
[fv-az1433-905:70740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f0fe0cb6d9c]
[fv-az1433-905:70740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f0fe0cb6e07]
[fv-az1433-905:70740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0fe0cb70bb]
[fv-az1433-905:70740] [ 8] plumed(+0x12f48)[0x56202cc56f48]
[fv-az1433-905:70740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0fe0829d90]
[fv-az1433-905:70740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0fe0829e40]
[fv-az1433-905:70740] [11] plumed(+0x131e5)[0x56202cc571e5]
[fv-az1433-905:70740] *** End of error message ***
</pre>
{% endraw %}
