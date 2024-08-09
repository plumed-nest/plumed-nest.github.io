**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT0R_Reactif_Methanal_and_Hydrogen-Cyanide_and_Amoniac/plumed.dat   
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
[fv-az1567-223:04198] *** Process received signal ***
[fv-az1567-223:04198] Signal: Aborted (6)
[fv-az1567-223:04198] Signal code:  (-6)
[fv-az1567-223:04198] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7ebf442520]
[fv-az1567-223:04198] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7ebf4969fc]
[fv-az1567-223:04198] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7ebf442476]
[fv-az1567-223:04198] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7ebf4287f3]
[fv-az1567-223:04198] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7ebf8a2b9e]
[fv-az1567-223:04198] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7ebf8ae20c]
[fv-az1567-223:04198] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7ebf8ae277]
[fv-az1567-223:04198] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7ebf8ae52b]
[fv-az1567-223:04198] [ 8] plumed(+0x12f48)[0x563423855f48]
[fv-az1567-223:04198] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7ebf429d90]
[fv-az1567-223:04198] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7ebf429e40]
[fv-az1567-223:04198] [11] plumed(+0x131e5)[0x5634238561e5]
[fv-az1567-223:04198] *** End of error message ***
</pre>
{% endraw %}
