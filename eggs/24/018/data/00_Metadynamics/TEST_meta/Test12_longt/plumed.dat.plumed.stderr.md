**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.005 W_STRIDE 150
Maybe a missing space or a typo?
[fv-az1567-223:04008] *** Process received signal ***
[fv-az1567-223:04008] Signal: Aborted (6)
[fv-az1567-223:04008] Signal code:  (-6)
[fv-az1567-223:04008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f476d842520]
[fv-az1567-223:04008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f476d8969fc]
[fv-az1567-223:04008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f476d842476]
[fv-az1567-223:04008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f476d8287f3]
[fv-az1567-223:04008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f476dca2b9e]
[fv-az1567-223:04008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f476dcae20c]
[fv-az1567-223:04008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f476dcae277]
[fv-az1567-223:04008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f476dcae52b]
[fv-az1567-223:04008] [ 8] plumed(+0x12f48)[0x562b7be08f48]
[fv-az1567-223:04008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f476d829d90]
[fv-az1567-223:04008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f476d829e40]
[fv-az1567-223:04008] [11] plumed(+0x131e5)[0x562b7be091e5]
[fv-az1567-223:04008] *** End of error message ***
</pre>
{% endraw %}
