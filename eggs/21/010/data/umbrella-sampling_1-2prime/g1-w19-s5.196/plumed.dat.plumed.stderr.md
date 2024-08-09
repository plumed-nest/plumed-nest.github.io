**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w19-s5.196/plumed.dat   
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
[fv-az1019-654:06994] *** Process received signal ***
[fv-az1019-654:06994] Signal: Aborted (6)
[fv-az1019-654:06994] Signal code:  (-6)
[fv-az1019-654:06994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3ad9642520]
[fv-az1019-654:06994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3ad96969fc]
[fv-az1019-654:06994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3ad9642476]
[fv-az1019-654:06994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3ad96287f3]
[fv-az1019-654:06994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3ad9aa2b9e]
[fv-az1019-654:06994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3ad9aae20c]
[fv-az1019-654:06994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3ad9aae277]
[fv-az1019-654:06994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3ad9aae52b]
[fv-az1019-654:06994] [ 8] plumed(+0x12f48)[0x55b8c62e9f48]
[fv-az1019-654:06994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3ad9629d90]
[fv-az1019-654:06994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3ad9629e40]
[fv-az1019-654:06994] [11] plumed(+0x131e5)[0x55b8c62ea1e5]
[fv-az1019-654:06994] *** End of error message ***
</pre>
{% endraw %}
