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
[fv-az1372-996:08544] *** Process received signal ***
[fv-az1372-996:08544] Signal: Aborted (6)
[fv-az1372-996:08544] Signal code:  (-6)
[fv-az1372-996:08544] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8701645330]
[fv-az1372-996:08544] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f870169eb2c]
[fv-az1372-996:08544] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f870164527e]
[fv-az1372-996:08544] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f87016288ff]
[fv-az1372-996:08544] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8701aa5ff5]
[fv-az1372-996:08544] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8701abb0da]
[fv-az1372-996:08544] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8701aa5a55]
[fv-az1372-996:08544] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8701aa5a6f]
[fv-az1372-996:08544] [ 8] plumed_master(+0x146dd)[0x55cbbb9376dd]
[fv-az1372-996:08544] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f870162a1ca]
[fv-az1372-996:08544] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f870162a28b]
[fv-az1372-996:08544] [11] plumed_master(+0x15365)[0x55cbbb938365]
[fv-az1372-996:08544] *** End of error message ***
</pre>
{% endraw %}
