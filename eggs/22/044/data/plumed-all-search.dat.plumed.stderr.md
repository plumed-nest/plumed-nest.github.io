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
[fv-az1391-351:62784] *** Process received signal ***
[fv-az1391-351:62784] Signal: Aborted (6)
[fv-az1391-351:62784] Signal code:  (-6)
[fv-az1391-351:62784] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0eaf645330]
[fv-az1391-351:62784] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0eaf69eb2c]
[fv-az1391-351:62784] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0eaf64527e]
[fv-az1391-351:62784] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0eaf6288ff]
[fv-az1391-351:62784] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0eafaa5ff5]
[fv-az1391-351:62784] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0eafabb0da]
[fv-az1391-351:62784] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0eafaa5a55]
[fv-az1391-351:62784] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0eafaa5a6f]
[fv-az1391-351:62784] [ 8] plumed(+0x146dd)[0x5648c3f2a6dd]
[fv-az1391-351:62784] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0eaf62a1ca]
[fv-az1391-351:62784] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0eaf62a28b]
[fv-az1391-351:62784] [11] plumed(+0x15365)[0x5648c3f2b365]
[fv-az1391-351:62784] *** End of error message ***
</pre>
{% endraw %}
