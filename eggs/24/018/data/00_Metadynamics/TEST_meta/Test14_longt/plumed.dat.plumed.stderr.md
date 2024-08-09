**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
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
[fv-az1567-223:04070] *** Process received signal ***
[fv-az1567-223:04070] Signal: Aborted (6)
[fv-az1567-223:04070] Signal code:  (-6)
[fv-az1567-223:04070] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3ce1442520]
[fv-az1567-223:04070] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3ce14969fc]
[fv-az1567-223:04070] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3ce1442476]
[fv-az1567-223:04070] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3ce14287f3]
[fv-az1567-223:04070] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3ce18a2b9e]
[fv-az1567-223:04070] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3ce18ae20c]
[fv-az1567-223:04070] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3ce18ae277]
[fv-az1567-223:04070] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3ce18ae52b]
[fv-az1567-223:04070] [ 8] plumed(+0x12f48)[0x565192940f48]
[fv-az1567-223:04070] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3ce1429d90]
[fv-az1567-223:04070] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3ce1429e40]
[fv-az1567-223:04070] [11] plumed(+0x131e5)[0x5651929411e5]
[fv-az1567-223:04070] *** End of error message ***
</pre>
{% endraw %}
