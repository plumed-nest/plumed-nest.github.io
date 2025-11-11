**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmw9dnm:07329] *** Process received signal ***
[runnervmw9dnm:07329] Signal: Aborted (6)
[runnervmw9dnm:07329] Signal code:  (-6)
[runnervmw9dnm:07329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4324045330]
[runnervmw9dnm:07329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f432409eb2c]
[runnervmw9dnm:07329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f432404527e]
[runnervmw9dnm:07329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43240288ff]
[runnervmw9dnm:07329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43244a5ff5]
[runnervmw9dnm:07329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43244bb0da]
[runnervmw9dnm:07329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43244a5a55]
[runnervmw9dnm:07329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43244a5a6f]
[runnervmw9dnm:07329] [ 8] plumed(+0x146dd)[0x5565a30236dd]
[runnervmw9dnm:07329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f432402a1ca]
[runnervmw9dnm:07329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f432402a28b]
[runnervmw9dnm:07329] [11] plumed(+0x15365)[0x5565a3024365]
[runnervmw9dnm:07329] *** End of error message ***
</pre>
{% endraw %}
