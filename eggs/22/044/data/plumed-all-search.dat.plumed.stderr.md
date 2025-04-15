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
[fv-az1910-428:62527] *** Process received signal ***
[fv-az1910-428:62527] Signal: Aborted (6)
[fv-az1910-428:62527] Signal code:  (-6)
[fv-az1910-428:62527] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb754245330]
[fv-az1910-428:62527] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb75429eb2c]
[fv-az1910-428:62527] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb75424527e]
[fv-az1910-428:62527] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7542288ff]
[fv-az1910-428:62527] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7546a5ff5]
[fv-az1910-428:62527] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7546bb0da]
[fv-az1910-428:62527] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7546a5a55]
[fv-az1910-428:62527] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7546a5a6f]
[fv-az1910-428:62527] [ 8] plumed(+0x146dd)[0x5566aa3266dd]
[fv-az1910-428:62527] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb75422a1ca]
[fv-az1910-428:62527] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb75422a28b]
[fv-az1910-428:62527] [11] plumed(+0x15365)[0x5566aa327365]
[fv-az1910-428:62527] *** End of error message ***
</pre>
{% endraw %}
