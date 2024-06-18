**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w21-s5.628/plumed.dat   
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
[fv-az1215-453:07030] *** Process received signal ***
[fv-az1215-453:07030] Signal: Aborted (6)
[fv-az1215-453:07030] Signal code:  (-6)
[fv-az1215-453:07030] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0f8f842520]
[fv-az1215-453:07030] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0f8f8969fc]
[fv-az1215-453:07030] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0f8f842476]
[fv-az1215-453:07030] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0f8f8287f3]
[fv-az1215-453:07030] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0f8fca2b9e]
[fv-az1215-453:07030] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0f8fcae20c]
[fv-az1215-453:07030] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0f8fcae277]
[fv-az1215-453:07030] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0f8fcae52b]
[fv-az1215-453:07030] [ 8] plumed(+0x12f48)[0x562eaef77f48]
[fv-az1215-453:07030] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0f8f829d90]
[fv-az1215-453:07030] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0f8f829e40]
[fv-az1215-453:07030] [11] plumed(+0x131e5)[0x562eaef781e5]
[fv-az1215-453:07030] *** End of error message ***
</pre>
{% endraw %}
