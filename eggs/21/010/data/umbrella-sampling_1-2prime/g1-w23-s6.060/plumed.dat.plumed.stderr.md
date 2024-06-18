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
[fv-az1215-453:07093] *** Process received signal ***
[fv-az1215-453:07093] Signal: Aborted (6)
[fv-az1215-453:07093] Signal code:  (-6)
[fv-az1215-453:07093] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f94e3a42520]
[fv-az1215-453:07093] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f94e3a969fc]
[fv-az1215-453:07093] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f94e3a42476]
[fv-az1215-453:07093] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f94e3a287f3]
[fv-az1215-453:07093] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f94e3ea2b9e]
[fv-az1215-453:07093] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f94e3eae20c]
[fv-az1215-453:07093] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f94e3eae277]
[fv-az1215-453:07093] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f94e3eae52b]
[fv-az1215-453:07093] [ 8] plumed(+0x12f48)[0x564e2f36bf48]
[fv-az1215-453:07093] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f94e3a29d90]
[fv-az1215-453:07093] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f94e3a29e40]
[fv-az1215-453:07093] [11] plumed(+0x131e5)[0x564e2f36c1e5]
[fv-az1215-453:07093] *** End of error message ***
</pre>
{% endraw %}
