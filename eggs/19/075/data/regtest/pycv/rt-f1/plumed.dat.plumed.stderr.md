**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=dAB2 ARG=dAB IMPORT=pythonfunction FUNCTION=square PERIODIC=NO
Maybe a missing space or a typo?
[fv-az883-206:06384] *** Process received signal ***
[fv-az883-206:06384] Signal: Aborted (6)
[fv-az883-206:06384] Signal code:  (-6)
[fv-az883-206:06384] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa659e42520]
[fv-az883-206:06384] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa659e969fc]
[fv-az883-206:06384] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa659e42476]
[fv-az883-206:06384] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa659e287f3]
[fv-az883-206:06384] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa65a2a2b9e]
[fv-az883-206:06384] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa65a2ae20c]
[fv-az883-206:06384] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa65a2ae277]
[fv-az883-206:06384] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa65a2ae52b]
[fv-az883-206:06384] [ 8] plumed(+0x12f48)[0x55ff2b36cf48]
[fv-az883-206:06384] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa659e29d90]
[fv-az883-206:06384] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa659e29e40]
[fv-az883-206:06384] [11] plumed(+0x131e5)[0x55ff2b36d1e5]
[fv-az883-206:06384] *** End of error message ***
</pre>
{% endraw %}
