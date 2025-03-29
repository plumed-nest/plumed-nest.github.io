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
[fv-az789-879:63898] *** Process received signal ***
[fv-az789-879:63898] Signal: Aborted (6)
[fv-az789-879:63898] Signal code:  (-6)
[fv-az789-879:63898] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1343845330]
[fv-az789-879:63898] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f134389eb2c]
[fv-az789-879:63898] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f134384527e]
[fv-az789-879:63898] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13438288ff]
[fv-az789-879:63898] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1343ca5ff5]
[fv-az789-879:63898] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1343cbb0da]
[fv-az789-879:63898] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1343ca5a55]
[fv-az789-879:63898] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1343ca5a6f]
[fv-az789-879:63898] [ 8] plumed_master(+0x146dd)[0x5603153746dd]
[fv-az789-879:63898] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f134382a1ca]
[fv-az789-879:63898] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f134382a28b]
[fv-az789-879:63898] [11] plumed_master(+0x15365)[0x560315375365]
[fv-az789-879:63898] *** End of error message ***
</pre>
{% endraw %}
