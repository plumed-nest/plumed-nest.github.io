**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: HBOND_COORD SPECIES=2665-10353:4 HYDROGENS=2666-10354:4,2667-10355:4 RCUTOO=0.324 RCUTOH=0.25 ACUT=0.20pi LABEL=hb
Maybe a missing space or a typo?
[fv-az1490-855:10394] *** Process received signal ***
[fv-az1490-855:10394] Signal: Aborted (6)
[fv-az1490-855:10394] Signal code:  (-6)
[fv-az1490-855:10394] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8e18442520]
[fv-az1490-855:10394] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8e184969fc]
[fv-az1490-855:10394] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8e18442476]
[fv-az1490-855:10394] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8e184287f3]
[fv-az1490-855:10394] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8e188a2b9e]
[fv-az1490-855:10394] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8e188ae20c]
[fv-az1490-855:10394] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8e188ae277]
[fv-az1490-855:10394] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8e188ae52b]
[fv-az1490-855:10394] [ 8] plumed(+0x12f48)[0x5587959b7f48]
[fv-az1490-855:10394] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8e18429d90]
[fv-az1490-855:10394] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8e18429e40]
[fv-az1490-855:10394] [11] plumed(+0x131e5)[0x5587959b81e5]
[fv-az1490-855:10394] *** End of error message ***
</pre>
{% endraw %}
