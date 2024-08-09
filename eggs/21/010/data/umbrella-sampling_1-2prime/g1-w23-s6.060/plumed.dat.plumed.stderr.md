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
[fv-az1019-654:07151] *** Process received signal ***
[fv-az1019-654:07151] Signal: Aborted (6)
[fv-az1019-654:07151] Signal code:  (-6)
[fv-az1019-654:07151] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5d92642520]
[fv-az1019-654:07151] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5d926969fc]
[fv-az1019-654:07151] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5d92642476]
[fv-az1019-654:07151] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5d926287f3]
[fv-az1019-654:07151] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5d92aa2b9e]
[fv-az1019-654:07151] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5d92aae20c]
[fv-az1019-654:07151] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5d92aae277]
[fv-az1019-654:07151] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5d92aae52b]
[fv-az1019-654:07151] [ 8] plumed(+0x12f48)[0x561c4e118f48]
[fv-az1019-654:07151] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5d92629d90]
[fv-az1019-654:07151] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5d92629e40]
[fv-az1019-654:07151] [11] plumed(+0x131e5)[0x561c4e1191e5]
[fv-az1019-654:07151] *** End of error message ***
</pre>
{% endraw %}
