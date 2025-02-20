**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[fv-az1372-996:08528] *** Process received signal ***
[fv-az1372-996:08528] Signal: Aborted (6)
[fv-az1372-996:08528] Signal code:  (-6)
[fv-az1372-996:08528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4ac445330]
[fv-az1372-996:08528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4ac49eb2c]
[fv-az1372-996:08528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4ac44527e]
[fv-az1372-996:08528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4ac4288ff]
[fv-az1372-996:08528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4ac8a5ff5]
[fv-az1372-996:08528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4ac8bb0da]
[fv-az1372-996:08528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4ac8a5a55]
[fv-az1372-996:08528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4ac8a5a6f]
[fv-az1372-996:08528] [ 8] plumed(+0x146dd)[0x55f87c4b16dd]
[fv-az1372-996:08528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4ac42a1ca]
[fv-az1372-996:08528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4ac42a28b]
[fv-az1372-996:08528] [11] plumed(+0x15365)[0x55f87c4b2365]
[fv-az1372-996:08528] *** End of error message ***
</pre>
{% endraw %}
