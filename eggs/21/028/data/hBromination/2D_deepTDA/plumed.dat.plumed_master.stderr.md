**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:461) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[fv-az789-879:65875] *** Process received signal ***
[fv-az789-879:65875] Signal: Aborted (6)
[fv-az789-879:65875] Signal code:  (-6)
[fv-az789-879:65875] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff182c45330]
[fv-az789-879:65875] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff182c9eb2c]
[fv-az789-879:65875] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff182c4527e]
[fv-az789-879:65875] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff182c288ff]
[fv-az789-879:65875] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1830a5ff5]
[fv-az789-879:65875] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1830bb0da]
[fv-az789-879:65875] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1830a5a55]
[fv-az789-879:65875] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1830a5a6f]
[fv-az789-879:65875] [ 8] plumed_master(+0x146dd)[0x55eb8fb746dd]
[fv-az789-879:65875] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff182c2a1ca]
[fv-az789-879:65875] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff182c2a28b]
[fv-az789-879:65875] [11] plumed_master(+0x15365)[0x55eb8fb75365]
[fv-az789-879:65875] *** End of error message ***
</pre>
{% endraw %}
