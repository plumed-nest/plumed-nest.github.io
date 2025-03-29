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
[fv-az789-879:63882] *** Process received signal ***
[fv-az789-879:63882] Signal: Aborted (6)
[fv-az789-879:63882] Signal code:  (-6)
[fv-az789-879:63882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67eca45330]
[fv-az789-879:63882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67eca9eb2c]
[fv-az789-879:63882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67eca4527e]
[fv-az789-879:63882] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67eca288ff]
[fv-az789-879:63882] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67ecea5ff5]
[fv-az789-879:63882] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67ecebb0da]
[fv-az789-879:63882] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67ecea5a55]
[fv-az789-879:63882] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67ecea5a6f]
[fv-az789-879:63882] [ 8] plumed(+0x146dd)[0x563870c126dd]
[fv-az789-879:63882] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67eca2a1ca]
[fv-az789-879:63882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67eca2a28b]
[fv-az789-879:63882] [11] plumed(+0x15365)[0x563870c13365]
[fv-az789-879:63882] *** End of error message ***
</pre>
{% endraw %}
