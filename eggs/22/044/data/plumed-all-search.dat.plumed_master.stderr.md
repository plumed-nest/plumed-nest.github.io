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
[fv-az1360-658:06847] *** Process received signal ***
[fv-az1360-658:06847] Signal: Aborted (6)
[fv-az1360-658:06847] Signal code:  (-6)
[fv-az1360-658:06847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa054845330]
[fv-az1360-658:06847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa05489eb2c]
[fv-az1360-658:06847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa05484527e]
[fv-az1360-658:06847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa0548288ff]
[fv-az1360-658:06847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa054ca5ff5]
[fv-az1360-658:06847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa054cbb0da]
[fv-az1360-658:06847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa054ca5a55]
[fv-az1360-658:06847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa054ca5a6f]
[fv-az1360-658:06847] [ 8] plumed_master(+0x146dd)[0x5631035c76dd]
[fv-az1360-658:06847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa05482a1ca]
[fv-az1360-658:06847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa05482a28b]
[fv-az1360-658:06847] [11] plumed_master(+0x15365)[0x5631035c8365]
[fv-az1360-658:06847] *** End of error message ***
</pre>
{% endraw %}
