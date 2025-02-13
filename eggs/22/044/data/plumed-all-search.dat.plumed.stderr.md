**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[fv-az2035-366:07455] *** Process received signal ***
[fv-az2035-366:07455] Signal: Aborted (6)
[fv-az2035-366:07455] Signal code:  (-6)
[fv-az2035-366:07455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5178045330]
[fv-az2035-366:07455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f517809eb2c]
[fv-az2035-366:07455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f517804527e]
[fv-az2035-366:07455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51780288ff]
[fv-az2035-366:07455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51784a5ff5]
[fv-az2035-366:07455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51784bb0da]
[fv-az2035-366:07455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51784a5a55]
[fv-az2035-366:07455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51784a5a6f]
[fv-az2035-366:07455] [ 8] plumed(+0x146dd)[0x55b0206476dd]
[fv-az2035-366:07455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f517802a1ca]
[fv-az2035-366:07455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f517802a28b]
[fv-az2035-366:07455] [11] plumed(+0x15365)[0x55b020648365]
[fv-az2035-366:07455] *** End of error message ***
</pre>
{% endraw %}
