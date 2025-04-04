**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az2207-973:13569] *** Process received signal ***
[fv-az2207-973:13569] Signal: Aborted (6)
[fv-az2207-973:13569] Signal code:  (-6)
[fv-az2207-973:13569] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34e9845330]
[fv-az2207-973:13569] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34e989eb2c]
[fv-az2207-973:13569] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34e984527e]
[fv-az2207-973:13569] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34e98288ff]
[fv-az2207-973:13569] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34e9ca5ff5]
[fv-az2207-973:13569] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34e9cbb0da]
[fv-az2207-973:13569] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34e9ca5a55]
[fv-az2207-973:13569] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34e9ca5a6f]
[fv-az2207-973:13569] [ 8] plumed(+0x146dd)[0x55751e7fc6dd]
[fv-az2207-973:13569] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34e982a1ca]
[fv-az2207-973:13569] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34e982a28b]
[fv-az2207-973:13569] [11] plumed(+0x15365)[0x55751e7fd365]
[fv-az2207-973:13569] *** End of error message ***
</pre>
{% endraw %}
