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
[fv-az1269-668:06337] *** Process received signal ***
[fv-az1269-668:06337] Signal: Aborted (6)
[fv-az1269-668:06337] Signal code:  (-6)
[fv-az1269-668:06337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f225fe42520]
[fv-az1269-668:06337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f225fe969fc]
[fv-az1269-668:06337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f225fe42476]
[fv-az1269-668:06337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f225fe287f3]
[fv-az1269-668:06337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f22602a2b9e]
[fv-az1269-668:06337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f22602ae20c]
[fv-az1269-668:06337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f22602ae277]
[fv-az1269-668:06337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f22602ae52b]
[fv-az1269-668:06337] [ 8] plumed(+0x12f48)[0x55c38ff46f48]
[fv-az1269-668:06337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f225fe29d90]
[fv-az1269-668:06337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f225fe29e40]
[fv-az1269-668:06337] [11] plumed(+0x131e5)[0x55c38ff471e5]
[fv-az1269-668:06337] *** End of error message ***
</pre>
{% endraw %}
