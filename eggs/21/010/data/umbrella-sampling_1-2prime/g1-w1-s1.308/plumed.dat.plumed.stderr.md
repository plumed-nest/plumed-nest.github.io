**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
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
[fv-az1215-453:06621] *** Process received signal ***
[fv-az1215-453:06621] Signal: Aborted (6)
[fv-az1215-453:06621] Signal code:  (-6)
[fv-az1215-453:06621] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa52f842520]
[fv-az1215-453:06621] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa52f8969fc]
[fv-az1215-453:06621] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa52f842476]
[fv-az1215-453:06621] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa52f8287f3]
[fv-az1215-453:06621] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa52fca2b9e]
[fv-az1215-453:06621] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa52fcae20c]
[fv-az1215-453:06621] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa52fcae277]
[fv-az1215-453:06621] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa52fcae52b]
[fv-az1215-453:06621] [ 8] plumed(+0x12f48)[0x56184b7b3f48]
[fv-az1215-453:06621] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa52f829d90]
[fv-az1215-453:06621] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa52f829e40]
[fv-az1215-453:06621] [11] plumed(+0x131e5)[0x56184b7b41e5]
[fv-az1215-453:06621] *** End of error message ***
</pre>
{% endraw %}
