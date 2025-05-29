**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmf6wy0o8zjz:62172] *** Process received signal ***
[pkrvmf6wy0o8zjz:62172] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62172] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62172] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ea0645330]
[pkrvmf6wy0o8zjz:62172] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ea069eb2c]
[pkrvmf6wy0o8zjz:62172] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ea064527e]
[pkrvmf6wy0o8zjz:62172] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ea06288ff]
[pkrvmf6wy0o8zjz:62172] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ea0aa5ff5]
[pkrvmf6wy0o8zjz:62172] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ea0abb0da]
[pkrvmf6wy0o8zjz:62172] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ea0aa5a55]
[pkrvmf6wy0o8zjz:62172] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ea0aa5a6f]
[pkrvmf6wy0o8zjz:62172] [ 8] plumed_master(+0x146dd)[0x55df2bcaa6dd]
[pkrvmf6wy0o8zjz:62172] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ea062a1ca]
[pkrvmf6wy0o8zjz:62172] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ea062a28b]
[pkrvmf6wy0o8zjz:62172] [11] plumed_master(+0x15365)[0x55df2bcab365]
[pkrvmf6wy0o8zjz:62172] *** End of error message ***
</pre>
{% endraw %}
