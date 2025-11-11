**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervmw9dnm:13644] *** Process received signal ***
[runnervmw9dnm:13644] Signal: Aborted (6)
[runnervmw9dnm:13644] Signal code:  (-6)
[runnervmw9dnm:13644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f84de445330]
[runnervmw9dnm:13644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f84de49eb2c]
[runnervmw9dnm:13644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f84de44527e]
[runnervmw9dnm:13644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84de4288ff]
[runnervmw9dnm:13644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84de8a5ff5]
[runnervmw9dnm:13644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84de8bb0da]
[runnervmw9dnm:13644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84de8a5a55]
[runnervmw9dnm:13644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84de8a5a6f]
[runnervmw9dnm:13644] [ 8] plumed_master(+0x146dd)[0x55ddc43a56dd]
[runnervmw9dnm:13644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f84de42a1ca]
[runnervmw9dnm:13644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f84de42a28b]
[runnervmw9dnm:13644] [11] plumed_master(+0x15365)[0x55ddc43a6365]
[runnervmw9dnm:13644] *** End of error message ***
</pre>
{% endraw %}
