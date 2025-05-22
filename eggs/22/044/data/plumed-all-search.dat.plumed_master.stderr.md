**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmf6wy0o8zjz:34987] *** Process received signal ***
[pkrvmf6wy0o8zjz:34987] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34987] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34987] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15b3845330]
[pkrvmf6wy0o8zjz:34987] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15b389eb2c]
[pkrvmf6wy0o8zjz:34987] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15b384527e]
[pkrvmf6wy0o8zjz:34987] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15b38288ff]
[pkrvmf6wy0o8zjz:34987] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15b3ca5ff5]
[pkrvmf6wy0o8zjz:34987] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15b3cbb0da]
[pkrvmf6wy0o8zjz:34987] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15b3ca5a55]
[pkrvmf6wy0o8zjz:34987] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15b3ca5a6f]
[pkrvmf6wy0o8zjz:34987] [ 8] plumed_master(+0x146dd)[0x561e6321e6dd]
[pkrvmf6wy0o8zjz:34987] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15b382a1ca]
[pkrvmf6wy0o8zjz:34987] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15b382a28b]
[pkrvmf6wy0o8zjz:34987] [11] plumed_master(+0x15365)[0x561e6321f365]
[pkrvmf6wy0o8zjz:34987] *** End of error message ***
</pre>
{% endraw %}
