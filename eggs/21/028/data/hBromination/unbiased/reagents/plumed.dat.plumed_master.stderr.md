**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:476) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[fv-az787-589:64289] *** Process received signal ***
[fv-az787-589:64289] Signal: Aborted (6)
[fv-az787-589:64289] Signal code:  (-6)
[fv-az787-589:64289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f483d045330]
[fv-az787-589:64289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f483d09eb2c]
[fv-az787-589:64289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f483d04527e]
[fv-az787-589:64289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f483d0288ff]
[fv-az787-589:64289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f483d4a5ff5]
[fv-az787-589:64289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f483d4bb0da]
[fv-az787-589:64289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f483d4a5a55]
[fv-az787-589:64289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f483d4a5a6f]
[fv-az787-589:64289] [ 8] plumed_master(+0x146dd)[0x55ced5f986dd]
[fv-az787-589:64289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f483d02a1ca]
[fv-az787-589:64289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f483d02a28b]
[fv-az787-589:64289] [11] plumed_master(+0x15365)[0x55ced5f99365]
[fv-az787-589:64289] *** End of error message ***
</pre>
{% endraw %}
