**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervmmklqx:11520] *** Process received signal ***
[runnervmmklqx:11520] Signal: Aborted (6)
[runnervmmklqx:11520] Signal code:  (-6)
[runnervmmklqx:11520] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fadf7245330]
[runnervmmklqx:11520] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fadf729eb2c]
[runnervmmklqx:11520] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fadf724527e]
[runnervmmklqx:11520] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fadf72288ff]
[runnervmmklqx:11520] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fadf76a5ff5]
[runnervmmklqx:11520] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fadf76bb0da]
[runnervmmklqx:11520] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fadf76a5a55]
[runnervmmklqx:11520] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fadf76a5a6f]
[runnervmmklqx:11520] [ 8] plumed_master(+0x146dd)[0x55d288c066dd]
[runnervmmklqx:11520] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fadf722a1ca]
[runnervmmklqx:11520] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fadf722a28b]
[runnervmmklqx:11520] [11] plumed_master(+0x15365)[0x55d288c07365]
[runnervmmklqx:11520] *** End of error message ***
</pre>
{% endraw %}
