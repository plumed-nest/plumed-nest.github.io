**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=r ATOMS=1,2,3 IMPORT=curvature FUNCTION=r
Maybe a missing space or a typo?
[fv-az883-206:06509] *** Process received signal ***
[fv-az883-206:06509] Signal: Aborted (6)
[fv-az883-206:06509] Signal code:  (-6)
[fv-az883-206:06509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4fec242520]
[fv-az883-206:06509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4fec2969fc]
[fv-az883-206:06509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4fec242476]
[fv-az883-206:06509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4fec2287f3]
[fv-az883-206:06509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f4fec6a2b9e]
[fv-az883-206:06509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f4fec6ae20c]
[fv-az883-206:06509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f4fec6ae277]
[fv-az883-206:06509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4fec6ae52b]
[fv-az883-206:06509] [ 8] plumed(+0x12f48)[0x5584cfa38f48]
[fv-az883-206:06509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4fec229d90]
[fv-az883-206:06509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4fec229e40]
[fv-az883-206:06509] [11] plumed(+0x131e5)[0x5584cfa391e5]
[fv-az883-206:06509] *** End of error message ***
</pre>
{% endraw %}
