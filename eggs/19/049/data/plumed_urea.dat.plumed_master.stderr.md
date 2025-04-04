**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az2207-973:13585] *** Process received signal ***
[fv-az2207-973:13585] Signal: Aborted (6)
[fv-az2207-973:13585] Signal code:  (-6)
[fv-az2207-973:13585] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f1b045330]
[fv-az2207-973:13585] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f1b09eb2c]
[fv-az2207-973:13585] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f1b04527e]
[fv-az2207-973:13585] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f1b0288ff]
[fv-az2207-973:13585] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f1b4a5ff5]
[fv-az2207-973:13585] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f1b4bb0da]
[fv-az2207-973:13585] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f1b4a5a55]
[fv-az2207-973:13585] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f1b4a5a6f]
[fv-az2207-973:13585] [ 8] plumed_master(+0x146dd)[0x55c2fb4b46dd]
[fv-az2207-973:13585] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f1b02a1ca]
[fv-az2207-973:13585] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f1b02a28b]
[fv-az2207-973:13585] [11] plumed_master(+0x15365)[0x55c2fb4b5365]
[fv-az2207-973:13585] *** End of error message ***
</pre>
{% endraw %}
