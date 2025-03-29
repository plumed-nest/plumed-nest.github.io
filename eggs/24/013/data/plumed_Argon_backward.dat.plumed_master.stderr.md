**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1947-163:60829] *** Process received signal ***
[fv-az1947-163:60829] Signal: Aborted (6)
[fv-az1947-163:60829] Signal code:  (-6)
[fv-az1947-163:60829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff51a645330]
[fv-az1947-163:60829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff51a69eb2c]
[fv-az1947-163:60829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff51a64527e]
[fv-az1947-163:60829] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff51a6288ff]
[fv-az1947-163:60829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff51aaa5ff5]
[fv-az1947-163:60829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff51aabb0da]
[fv-az1947-163:60829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff51aaa5a55]
[fv-az1947-163:60829] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff51aaa5a6f]
[fv-az1947-163:60829] [ 8] plumed_master(+0x146dd)[0x55cba98fd6dd]
[fv-az1947-163:60829] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff51a62a1ca]
[fv-az1947-163:60829] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff51a62a28b]
[fv-az1947-163:60829] [11] plumed_master(+0x15365)[0x55cba98fe365]
[fv-az1947-163:60829] *** End of error message ***
</pre>
{% endraw %}
