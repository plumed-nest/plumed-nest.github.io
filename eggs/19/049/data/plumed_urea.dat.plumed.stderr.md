**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervmw9dnm:13628] *** Process received signal ***
[runnervmw9dnm:13628] Signal: Aborted (6)
[runnervmw9dnm:13628] Signal code:  (-6)
[runnervmw9dnm:13628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f5d245330]
[runnervmw9dnm:13628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f5d29eb2c]
[runnervmw9dnm:13628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f5d24527e]
[runnervmw9dnm:13628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f5d2288ff]
[runnervmw9dnm:13628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f5d6a5ff5]
[runnervmw9dnm:13628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f5d6bb0da]
[runnervmw9dnm:13628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f5d6a5a55]
[runnervmw9dnm:13628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f5d6a5a6f]
[runnervmw9dnm:13628] [ 8] plumed(+0x146dd)[0x55b95f35b6dd]
[runnervmw9dnm:13628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f5d22a1ca]
[runnervmw9dnm:13628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f5d22a28b]
[runnervmw9dnm:13628] [11] plumed(+0x15365)[0x55b95f35c365]
[runnervmw9dnm:13628] *** End of error message ***
</pre>
{% endraw %}
