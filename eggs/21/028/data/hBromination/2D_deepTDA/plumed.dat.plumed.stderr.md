**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az787-589:64106] *** Process received signal ***
[fv-az787-589:64106] Signal: Aborted (6)
[fv-az787-589:64106] Signal code:  (-6)
[fv-az787-589:64106] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd52b645330]
[fv-az787-589:64106] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd52b69eb2c]
[fv-az787-589:64106] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd52b64527e]
[fv-az787-589:64106] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd52b6288ff]
[fv-az787-589:64106] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd52baa5ff5]
[fv-az787-589:64106] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd52babb0da]
[fv-az787-589:64106] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd52baa5a55]
[fv-az787-589:64106] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd52baa5a6f]
[fv-az787-589:64106] [ 8] plumed(+0x146dd)[0x560de86af6dd]
[fv-az787-589:64106] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd52b62a1ca]
[fv-az787-589:64106] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd52b62a28b]
[fv-az787-589:64106] [11] plumed(+0x15365)[0x560de86b0365]
[fv-az787-589:64106] *** End of error message ***
</pre>
{% endraw %}
