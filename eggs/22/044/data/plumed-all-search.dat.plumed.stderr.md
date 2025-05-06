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
[fv-az1781-652:63668] *** Process received signal ***
[fv-az1781-652:63668] Signal: Aborted (6)
[fv-az1781-652:63668] Signal code:  (-6)
[fv-az1781-652:63668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa6e4045330]
[fv-az1781-652:63668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa6e409eb2c]
[fv-az1781-652:63668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa6e404527e]
[fv-az1781-652:63668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa6e40288ff]
[fv-az1781-652:63668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa6e44a5ff5]
[fv-az1781-652:63668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa6e44bb0da]
[fv-az1781-652:63668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa6e44a5a55]
[fv-az1781-652:63668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa6e44a5a6f]
[fv-az1781-652:63668] [ 8] plumed(+0x146dd)[0x55d6c508b6dd]
[fv-az1781-652:63668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa6e402a1ca]
[fv-az1781-652:63668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa6e402a28b]
[fv-az1781-652:63668] [11] plumed(+0x15365)[0x55d6c508c365]
[fv-az1781-652:63668] *** End of error message ***
</pre>
{% endraw %}
