**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervmmklqx:11504] *** Process received signal ***
[runnervmmklqx:11504] Signal: Aborted (6)
[runnervmmklqx:11504] Signal code:  (-6)
[runnervmmklqx:11504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b13845330]
[runnervmmklqx:11504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b1389eb2c]
[runnervmmklqx:11504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b1384527e]
[runnervmmklqx:11504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b138288ff]
[runnervmmklqx:11504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b13ca5ff5]
[runnervmmklqx:11504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b13cbb0da]
[runnervmmklqx:11504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b13ca5a55]
[runnervmmklqx:11504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b13ca5a6f]
[runnervmmklqx:11504] [ 8] plumed(+0x146dd)[0x55af918186dd]
[runnervmmklqx:11504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b1382a1ca]
[runnervmmklqx:11504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b1382a28b]
[runnervmmklqx:11504] [11] plumed(+0x15365)[0x55af91819365]
[runnervmmklqx:11504] *** End of error message ***
</pre>
{% endraw %}
