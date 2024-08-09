**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w11-s3.468/plumed.dat   
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
[fv-az1019-654:06742] *** Process received signal ***
[fv-az1019-654:06742] Signal: Aborted (6)
[fv-az1019-654:06742] Signal code:  (-6)
[fv-az1019-654:06742] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd1a3e42520]
[fv-az1019-654:06742] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd1a3e969fc]
[fv-az1019-654:06742] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd1a3e42476]
[fv-az1019-654:06742] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd1a3e287f3]
[fv-az1019-654:06742] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd1a42a2b9e]
[fv-az1019-654:06742] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd1a42ae20c]
[fv-az1019-654:06742] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd1a42ae277]
[fv-az1019-654:06742] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd1a42ae52b]
[fv-az1019-654:06742] [ 8] plumed(+0x12f48)[0x55702a3e4f48]
[fv-az1019-654:06742] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd1a3e29d90]
[fv-az1019-654:06742] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd1a3e29e40]
[fv-az1019-654:06742] [11] plumed(+0x131e5)[0x55702a3e51e5]
[fv-az1019-654:06742] *** End of error message ***
</pre>
{% endraw %}
