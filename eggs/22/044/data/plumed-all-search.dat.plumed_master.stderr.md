**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervmi13qx:33858] *** Process received signal ***
[runnervmi13qx:33858] Signal: Aborted (6)
[runnervmi13qx:33858] Signal code:  (-6)
[runnervmi13qx:33858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6286c45330]
[runnervmi13qx:33858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6286c9eb2c]
[runnervmi13qx:33858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6286c4527e]
[runnervmi13qx:33858] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6286c288ff]
[runnervmi13qx:33858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62870a5ff5]
[runnervmi13qx:33858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62870bb0da]
[runnervmi13qx:33858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62870a5a55]
[runnervmi13qx:33858] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62870a5a6f]
[runnervmi13qx:33858] [ 8] plumed_master(+0x146dd)[0x562c27f2f6dd]
[runnervmi13qx:33858] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6286c2a1ca]
[runnervmi13qx:33858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6286c2a28b]
[runnervmi13qx:33858] [11] plumed_master(+0x15365)[0x562c27f30365]
[runnervmi13qx:33858] *** End of error message ***
</pre>
{% endraw %}
