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
[runnervmi13qx:33842] *** Process received signal ***
[runnervmi13qx:33842] Signal: Aborted (6)
[runnervmi13qx:33842] Signal code:  (-6)
[runnervmi13qx:33842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bd1445330]
[runnervmi13qx:33842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bd149eb2c]
[runnervmi13qx:33842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bd144527e]
[runnervmi13qx:33842] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bd14288ff]
[runnervmi13qx:33842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bd18a5ff5]
[runnervmi13qx:33842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bd18bb0da]
[runnervmi13qx:33842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bd18a5a55]
[runnervmi13qx:33842] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bd18a5a6f]
[runnervmi13qx:33842] [ 8] plumed(+0x146dd)[0x5576c92176dd]
[runnervmi13qx:33842] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bd142a1ca]
[runnervmi13qx:33842] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bd142a28b]
[runnervmi13qx:33842] [11] plumed(+0x15365)[0x5576c9218365]
[runnervmi13qx:33842] *** End of error message ***
</pre>
{% endraw %}
