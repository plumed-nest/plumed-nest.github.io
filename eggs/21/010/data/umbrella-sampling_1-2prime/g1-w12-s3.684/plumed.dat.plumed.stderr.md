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
[fv-az1019-654:06773] *** Process received signal ***
[fv-az1019-654:06773] Signal: Aborted (6)
[fv-az1019-654:06773] Signal code:  (-6)
[fv-az1019-654:06773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fedd9642520]
[fv-az1019-654:06773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fedd96969fc]
[fv-az1019-654:06773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fedd9642476]
[fv-az1019-654:06773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fedd96287f3]
[fv-az1019-654:06773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fedd9aa2b9e]
[fv-az1019-654:06773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fedd9aae20c]
[fv-az1019-654:06773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fedd9aae277]
[fv-az1019-654:06773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fedd9aae52b]
[fv-az1019-654:06773] [ 8] plumed(+0x12f48)[0x5643bf3e3f48]
[fv-az1019-654:06773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fedd9629d90]
[fv-az1019-654:06773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fedd9629e40]
[fv-az1019-654:06773] [11] plumed(+0x131e5)[0x5643bf3e41e5]
[fv-az1019-654:06773] *** End of error message ***
</pre>
{% endraw %}
